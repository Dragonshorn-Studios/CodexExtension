Dragonshorn Codex Connector: Dragonshorn Codex Extension
==

This is a browser extension that integrates the Character Sheet from Dragonshorn Codex into Roll20, Foundry VTT & Discord.

# Install and Use

## Install 

### Chrome

To install Dragonshorn Codex Connector on Chrome, simply head over to `tbd` and click "Add to Chrome" to get it installed.

### Firefox

To install Dragonshorn Codex Connector on Firefox, simply head over to `tbd` and click "Add to Firefox" to get it installed.

## Use 

Open Roll20 or Foundry VTT in a tab of Chrome or Firefox then your character sheet in Dragonshorn Codex Connector in another tab. If you are using Chrome with Foundry VTT, then you need to click on the Dragonshorn Codex Connector icon in the Chrome window's toolbar to activate Dragonshorn Codex Connector for your FVTT installation.

If a spell/item/action/feat description contains a dice formula (`2d10 + 3` for example) or a modifier formula (`+ 3` for example), that text will be underlined and a Dragon Dice dice icon will appear next to it. Click on the formula or the dice to make the roll in the Roll20 tab.

If you click on the Dragonshorn Codex Connector button in the toolbar, it will pop open the quick settings menu. Note that the quick settings menu will be different whether you are on the VTT tab or D&D Beyond tab, and it will contain the per-character configuration.

# Build

You need to install the build dependencies by running in Dragonshorn Codex Connector's source directory: 
`npm install`

You can then build the files using the command `npm run build`

# Developer Mode Installation

All you need is to load the extension from the source :

0. If you already have Dragonshorn Codex Connector installed from the Chrome or Firefox stores, disable it.
1. Download the extension for either [Chrome](https://github.com/Dragonshorn-Studios/CodexExtension/releases/download/latest/chrome.zip) or [Firefox](https://github.com/Dragonshorn-Studios/CodexExtension/releases/download/latest/firefox.zip)
2. Extract the zip file in a directory of your choice

## Chrome

3. Go to Chrome Extensions page (Menu->More Tools->Extensions)
4. Enable Developer Mode (Top-right corner)
5. Click on the 'Load Unpacked' button
6. Select the Directory where you extracted this extension

## Firefox

3. Open "[about:debugging#/runtime/this-firefox](about:debugging#/runtime/this-firefox)" in Firefox
4. Click "Load Temporary Add-on"
5. Select the `manifest.json` file from the extension's directory

# License

# Credits 
This extension is based by fantastic work by KaKaRoTo with Beyond20 extension.

This extension is released under the GPL v3 license. Read the LICENSE file for more details.

The roll badge icons were designed and created by [Jerry Escandon](https://github.com/Jerryescandon) 

The options page was copied in part from the `D&D Beyond Toolbox` extension available [here](https://github.com/mouse0270/Beyonds-Toolbox/). The html and css files are licensed under the MIT license which is provided in the LICENSE.MIT file

The condition icons (FVTT-module/beyond20/conditions) are for the most part taken from https://game-icons.net/ and licensed under a Creative Common CC-BY 3.0 License. You can find each icon's source and respective license in the FVTT-module/beyond20/conditions/LICENSE file
