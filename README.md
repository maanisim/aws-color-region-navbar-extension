<h1 align="center">
  <img src="./icon.png" width="64">
  <br>
  AWS Navbar Region Color Extension
  <br>
</h1>

<h4 align="center">An OSS version of the "AWS console regions color" extension, a browser extension that changes the color of the AWS navbar depending on the region</h4>

<p align="center">
<img src="https://raw.githubusercontent.com/corollari/aws-color-region-navbar-extension/master/screenshot.png">
</p>

## Reasons for the fork
- Other extension was broken by an update on AWS' side
- Adds new regions that were missing (including gov)
- Fixed support for Firefox

## Philosophy
All the extension code is kept extremely simple in order to allow anyone to contribute easily, this means:
- Uses no transpilation tools, only basic HTML and Javascript
- Only include minimal number of files
- Keep code extremely simple
  
## Development
On Firefox:
1. Open the Debugging page by navigating to `about:debugging#/runtime/this-firefox`.
2. Click on the "Load Temporary Add-on..." button and select the extension directory.

On Chrome (untested, likely to be broken):
1. Open the Extension Management page by navigating to `chrome://extensions`.
2. Enable Developer Mode by clicking the toggle switch next to Developer mode.
3. Click the LOAD UNPACKED button and select the extension directory.


## License
MIT

## Acknowledgements
- Thanks to u/Geeno2 for coming up with the idea and building it.
- Thanks to u/thehandsomezebra for fixing the script for the new ribbon behaviour

# Updates in the fork (u/maanisim):
- Modified it from sleep to mutation observer as, sleep takes too long on fast connection
- Added additional AWS regions (including GOV)
- Added flag emojis on the pop-up UI

