# Purrweb Extension Pack

## Extensions Included
* [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer-2)
* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
* [Docker](https://marketplace.visualstudio.com/items?itemName=peterjausovec.vscode-docker)
* [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
* [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
* [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
* [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.ruby)
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare)
* [file-icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons)
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
* [Babel JavaScript](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)
* [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
* [Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)
* [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
# Further steps
### Install `Fira Code` font
#### [Download v1.206](https://github.com/tonsky/FiraCode/releases/download/1.206/FiraCode_1.206.zip) · [How to install](https://github.com/tonsky/FiraCode/wiki) · [Troubleshooting](https://github.com/tonsky/FiraCode/wiki#troubleshooting) · [News & updates](https://twitter.com/FiraCode)
Fira Code is an extension of the Fira Mono font containing a set of ligatures for common programming multi-character combinations. This is just a font rendering feature: underlying code remains ASCII-compatible. This helps to read and understand code faster. For some frequent sequences like `..` or `//`, ligatures allow us to correct spacing.
### Code examples

Ruby:
<img src="https://raw.githubusercontent.com/supostat/purrweb-extension-pack/master/ruby.png">
JavaScript:
<img src="https://raw.githubusercontent.com/supostat/purrweb-extension-pack/master/javascript.png">
### VSCode user config
```json
{
    "editor.fontSize": 16,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.fontWeight": "500",
    "javascript.validate.enable": false,
    "eslint.autoFixOnSave": true,
    "eslint.alwaysShowStatus": true,
    "javascript.implicitProjectConfig.experimentalDecorators": true,
    "files.trimTrailingWhitespace": true,
    "terminal.integrated.fontFamily": "Fira Code",
    "terminal.integrated.fontSize": 14,
    "editor.tabSize": 2,
    "editor.renderWhitespace": "all",
    "git.autofetch": true,
    "window.zoomLevel": 0,
    "npm.enableScriptExplorer": true,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "javascript.updateImportsOnFileMove.enabled": "never",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.iconTheme": "file-icons",
    "workbench.colorTheme": "Atom One Dark"
}
```
* TODO


**Enjoy!**
