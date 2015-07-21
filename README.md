# Chrome JSON Formatter

This is the Flat Design modified version of [callumlocke's JSON Formatter](https://github.com/callumlocke/json-formatter) Chrome Plugin

### How to install
To install it, you need to have Google Chrome:
- Clone/Download this repo, unzip it to somewhere you can find
- Open Chrome and go to `chrome://extensions`
- Enable `Developer Mode`
- Click `Load unpacked extension`
- Select the folder you unzipped before

### How to develop
Based on the original source, if you want to create your own styles, you can modify the `css\content.css`, then use some CSS minifier to compress it and copy them all to `jfStyleEl.insertAdjacentHTML` call in `js\content.js` 

