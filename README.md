# wpgtk-theme README
A VS Code theme that supports [wpgtk](https://github.com/deviantfero/wpgtk)

## Installation 
- First make sure you have [wpgtk](https://github.com/deviantfero/wpgtk) and [VScode](https://code.visualstudio.com/) installed

- Grab the latest .vsix (Packadge file) from [release](https://github.com/GeoDerp/vscode-wpgtk-theme/releases) 

- Install the theme with vscode
  ```bash
  code  --install-extension ./*.vsix
  ```
  
- Add the theme as a wpgtk template
  _Linux example:_
  ```bash
  wpg -ta  ~/.vscode/extensions/$(ls | grep wpgtk-theme)/themes/wpgtk-theme-color-theme.json
  ```
  
- Lastly apply a wpg color scheme 
  ```bash
  wpg -m
  ```