# fakeBlock
## Misinformation Blocking Browser Extension

RPI Software Design & Documentation S21

## Building fakeBlock from source
Extract the distilBERT model into the `ml/` folder.

Run the following commands:
 1. `npm install .`
 2. `npm run build`

There should be a new folder `dist/`. 

This is the unpacked extension that can be loaded into your browser. 

## Installing fakeBlock from `dist/`
To install on chrome:
 1. Visit `chrome://extensions` (via omnibox or menu -> Tools -> Extensions).
 2. Enable Developer mode by ticking the checkbox in the upper-right corner.
 3. Click on the "Load unpacked extension..." button.
 4. Select the `dist/` folder.

To install on firefox:
 1. Open the about:debugging page
 2. Click "This Firefox" (in newer versions of Firefox)
 3. Click "Load Temporary Add-on"
 4. Select any file in the `dist/` folder



Initial files based off [browser-extension-template](https://github.com/fregante/browser-extension-template)
