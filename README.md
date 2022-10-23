# ub-logo-on-activity-bar

This VSCode extension replaces the default file explorer icon on the activity pane with Unibuddy Logo.

![UB Logo](https://github.com/unibuddy-labs/ub-logo-vscode-extension/blob/fd379b62f4948f02f7ea689780b1646a1b3979b7/productIconSnap.png?raw=true)

## VSCode Version Compatibility

`1.72.0` and onwards

## Enable

If you are reading this from VSCode's extension, you have installed the extension. So once extension is installed, to enable the Icon, press ``` cmd + shift + p ``` to open the command palette and type `product icon theme` and select `Unibuddy Logo`

## Note

Any custom product icon theme that is already installed other than default, will be replaced to default vscode product icon theme.

## Build

Executing this ```npm run generate-vsix``` command from the root of this project will generate `.vsix` extension file with the following file name convention `ub-logo-on-activity-bar-x.x.x.vsix`, where `x.x.x` is the npm package version of this project.

Once the `.vsix` file is built, use the following commands to install the extension.

## Install

If you have enabled vscode on global path and enabled `code` on terminal, run ```code --install-extension ub-logo-on-activity-bar-0.0.1.vsix``` from your terminal.

If not, open vscode extensions folder,

- Windows %USERPROFILE%\.vscode\extensions
- macOS ~/.vscode/extensions
- Linux ~/.vscode/extensions

and copy all the files and folders from this repo and paste it in a folder `ub-logo-on-activity-bar-0.0.1`.

Open VSCode and see `Enable` section.
