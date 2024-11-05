# wpgtk-theme
A VS Code theme that supports [wpgtk](https://github.com/deviantfero/wpgtk)
  
  
![screenshot](/img/screenshot.jpg)
_Theme still in development._
  
## Installation 
- First make sure you have [wpgtk](https://github.com/deviantfero/wpgtk) and [VScode](https://code.visualstudio.com/) installed

- Grab the latest .vsix (Packadge file) from [release](https://github.com/GeoDerp/vscode-wpgtk-theme/releases) 

- Install the theme with vscode
  ```bash
  code  --install-extension ./wpgtk-theme*.vsix
  ```
  
- Add the theme as a wpgtk template
  _Linux example:_
  ```bash
  wpg -ta  ~/.vscode/extensions/$(ls ~/.vscode/extensions/ | grep wpgtk-theme)/themes/wpgtk-theme-color-theme.json
  ```
  
- Apply a wpg color scheme 
  ```bash
  wpg -m
  ```

- Lastly select the theme in VS Code  
  ```
  (Ctrl+K Ctrl+T) > wpgtk-theme
  ```

