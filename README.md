# Visual Studio Code UI Theme

This is a basic VS Code theme used to customize the UI appearance.

Right now it uses [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) to add custom CSS files. Hopefully we'll have an official API soon.

## How to Install

1. Clone the repo
2. Install the extension [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) and activate it
3. Go to your settings and add the following:
```json
"vscode_custom_css.imports": [
  "file:///path/to/repo/your-selected-theme.css",
  "file:///path/to/repo/theme.css"
]
```
4. Run the command `Enable Custom CSS and JS`.
  (Note: This edits core files and you will need to activate after every update)
5. Reload the VS Code Window

## Themes available

- Eagle Oceanic Next (Use with [Eagle Oceanic Next](https://marketplace.visualstudio.com/items?itemName=graf009.Eagle-Oceanic-Next))
- Want more? Create an issue or create a push request.

## To Do

- Create a extension to make installation easier
- Add more Themes
- Add more variables
- Fix missing theme details (for example)