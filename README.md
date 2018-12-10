# Cisco syntax package for Sublime Text 2/3

Sublime Text 2/3 Syntax Definitition for Cisco [router/]switch[/firewall] configurations. This package will highlight Cisco/ HPE Aruba configuration and commands within Sublime Text 2/3.

## Installing

**Using Package Control:** If you have [package control](https://sublime.wbond.net/) installed then installing this is a snap. Simply open the command palette (Tools->Command Palette). Then type "install" then search for this plugin by typing "Cisco/ HPE Aruba Syntax Highlighter". That's it. It should be installed.

**Without Git:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `Cisco-HPE-Aruba`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text 2/3.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/LaurentFough/sublime-cisco-hpe-aruba-syntax.git

## Usage
Once installed navigate to View->Syntax->Cisco to apply the Cisco syntax to the document.

This syntax definition will automatically be applied to .txt files and .cfg files.

Using control-/ will comment out any line that is highlighted.


## Customizing
Once Cisco syntax is turned on you can then try different color schemes by going to Preferences -> Color Schemes.

If you wish to customize this even further for your own needs navigate to the Cisco package (Preferences -> Browse Packages). Edit the `Cisco Definitions.json-tmlanguage` file within Sublime Text 2. Install AAAPackageDev. After your changes go to Tools -> Build, to rebuild the syntax definitions.

## Further Reading
See official website for further information and discussion.
[http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets](http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets)

