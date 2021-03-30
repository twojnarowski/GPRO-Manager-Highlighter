# Instructions:

1. Open the Extension Management page by navigating to chrome://extensions.
2. The Extension Management page can also be opened by clicking on the Chrome menu, hovering over More Tools then selecting Extensions.
3. Enable Developer Mode by clicking the toggle switch next to Developer mode.
4. Click the LOAD UNPACKED button and select the extension directory.

# Features

1. Use commas (',') to seperate Managers.


# Reference:
- http://james.padolsey.com/javascript/replacing-text-in-the-dom-solved/
- http://stackoverflow.com/questions/2582831/how-can-i-highlight-the-text-of-the-dom-range-object
- https://chrome.google.com/webstore/detail/multi-highlight/pfgfgjlejbbpfmcfjhdmikihihddeeji
- https://developer.chrome.com/docs/extensions/mv2/getstarted/

# Forked from:
https://github.com/WindzCUHK/chrome-highlight-extension

# Bug:
- There may be change in DOM structure if the keyword spans across multi HTML tag.
- When page init, no content in body. Currently, hard-coded a delay, may investigate using MutationObserver() to solve it.
