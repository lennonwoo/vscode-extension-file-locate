# VSCode - file-locate

VSCode Extension "file-locate". Easily locate file on your disk (even if it's out of your workspace) and open it in vscode.

![Preview](https://github.com/TwanoO67/vscode-extension-file-locate/raw/master/images/demo.gif)

## Features

Add the command "Locate File" in your palette, that use the selected word in editor to look for file on your disk and open it.

## Requirements

You should have the "locate" binary on your system.
Instead you can "sudo apt-get install locate" on ubuntu.

## Extension Settings

None

## Known Issues

Won't work on system who don't have locate

## Recording Demo

See here:
https://github.com/phw/peek

# Publication

## On new install of vcse
- `npm install -g vsce`
- `vsce login TwanoO67`
## Then
- `vi package.json`  to update version number
- `vsce publish`

## Release Notes

### 1.0.2

* Update description and add demo

### 1.0.1

* Filter search string with slashes and backslashes

### 1.0.0

Initial release