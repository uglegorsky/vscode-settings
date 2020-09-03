# VS Code Settings

# Font

* [JetBrains Mono](https://www.jetbrains.com/lp/mono/)

# Extensions

## Themes/Color

* Original theme I use in most videos:
  * [Theme - Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)
* I've been using this darker modification of the above theme lately:
  * [Seti-Black](https://marketplace.visualstudio.com/items?itemName=bobsparadox.seti-black)
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  * Matching parenthesis and curly brackets to with colors
* [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

## Workflow

* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
  * Adds the ability to create files anywhere in your workspace.
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.
* [Toggle Quotes](https://marketplace.visualstudio.com/items?itemName=BriteSnow.vscode-toggle-quotes)
  * cmd ' (ctrl ' on win/linux) will cycle the first quote pair found (from the start/end of the section) between ', ", `

## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling

## Style/Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Beautify](https://marketplace.visualstudio.com/items?itemName=hookyqr.beautify)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.

## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Evaluate code/logs inline and show results in the editor
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code

# Settings

```json
{
  "explorer.confirmDelete": false,
  "editor.fontFamily": "JetBrains Mono, Anonymous Pro, 'Courier New', monospace",
  "workbench.colorTheme": "Seti Black",
  "editor.fontSize": 14,
  "explorer.openEditors.visible": 0,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "window.zoomLevel": 1,
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 14,
  "files.autoSave": "onFocusChange",
  "editor.tabSize": 2,
  "editor.lineHeight": 0,
  "editor.formatOnSave": true,
  "markdown.preview.fontSize": 36,
  "editor.minimap.enabled": false,
  "eslint.enable": true,
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "editor.tabCompletion": "on",
  "workbench.iconTheme": "material-icon-theme",
  "editor.wordWrap": "on",
  "workbench.colorCustomizations": {
    "activityBar.background": "#ffee00",
    "activityBar.inactiveForeground": "#000000",
    "activityBar.foreground": "#ffffff",
    "activityBar.activeBackground": "#000000",
    "statusBar.background": "#ffee00",
    "statusBar.noFolderBackground": "#ffee00",
    "statusBar.border": "#ffffff",
    "statusBar.foreground": "#000000"
  },
  "explorer.confirmDragAndDrop": false,
  "bracketPairColorizer.colorMode": "Independent",
  "bracketPairColorizer.independentPairColors": [
    ["()", ["Gold", "Tomato", "LightSkyBlue"], "Red"],
    ["[]", ["Gold", "Tomato", "LightSkyBlue"], "Red"],
    ["{}", ["Gold", "Tomato", "LightSkyBlue"], "Red"]
  ],
  "bracketPairColorizer.timeOut": 0,
  "prettier.singleQuote": true,
  "typescript.preferences.quoteStyle": "single",
  "javascript.preferences.quoteStyle": "single",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "window.menuBarVisibility": "compact",
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "python.languageServer": "Microsoft"
}

```
