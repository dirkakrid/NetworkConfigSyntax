# Network syntax package for Sublime Text 2

Sublime Text Syntax Definitition for Cisco/Arista/HP/Dell router/switch/firewall configurations. This package will highlight Cisco configuration and commands within Sublime Text 2.

## Installing

**Without Git:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `Network`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/IPyandy/sublime-network-syntax.git

## Usage
Once installed navigate to View->Syntax->Network to apply the Network syntax to the document.

This syntax definition will automatically be applied to .txt files and .cfg files.

## Customizing
Once Network syntax is turned on you can then try different color schemes by going to Preferences -> Color Schemes.

If you wish to customize this even further for your own needs navigate to the Network package (Preferences -> Browse Packages). Edit the `Network Definitions.json-tmlanguage` file within Sublime Text. After your changes go to Tools -> Build, to rebuild the syntax definitions.
