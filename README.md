# Example Webextension dev environment
## Requirements
* [Visual Studio Code](https://code.visualstudio.com/Download)
* [Debugger for Firefox (VSCode extension)](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-firefox-debug)
* [Firefox](https://www.mozilla.org/en-GB/firefox/new/) or [Firefox Developer Edition](https://www.mozilla.org/en-GB/firefox/developer/) 63+
(Will possibly work in 48+ but I haven't tested)

## Setup
* [Enable add-on debugging](https://developer.mozilla.org/en-US/docs/Tools/about:debugging)
* Start Firefox with [`--start-debugger-server`](https://developer.mozilla.org/en-US/docs/Tools/Remote_Debugging/Debugging_Firefox_Desktop#Firefox_37_onwards) option

## Debugging
### Breakpoints
Breakpoints will not be hit in `popup.js` unless the code has been loaded at least once and the addon is then reloaded in `about:debugging`.

See https://github.com/hbenl/vscode-firefox-debug#troubleshooting