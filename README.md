# Example Webextension dev environment
## Requirements
* [Visual Studio Code](https://code.visualstudio.com/Download)
* [Debugger for Firefox (VSCode extension)](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-firefox-debug)
* [Firefox](https://www.mozilla.org/en-GB/firefox/new/) or [Firefox Developer Edition](https://www.mozilla.org/en-GB/firefox/developer/) 63+
(Will possibly work in 48+ but I haven't tested)

## Setup
* [Enable add-on debugging](https://developer.mozilla.org/en-US/docs/Tools/about:debugging)
* Start Firefox with [`--start-debugger-server`](https://developer.mozilla.org/en-US/docs/Tools/Remote_Debugging/Debugging_Firefox_Desktop#Firefox_37_onwards) option

## Writing addon
Addon code goes in `addon` folder.  The contents of this folder will be pushed to Firefox
when running `Launch addon` from VSCode debugger.

### Resources
* [MDN documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions)
* [MDN example extensions](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Examples)

### Working examples
Based on this template
* [borderify](https://github.com/XuluWarrior/webextensions-vsc-dev-example/tree/borderify)
* [chill-out](https://github.com/XuluWarrior/webextensions-vsc-dev-example/tree/chill-out)