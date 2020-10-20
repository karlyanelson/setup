# Visual Studio Code Setup

_see Ian's setup: https://iansdevblog.netlify.com/posts/my_visual_studio_code_setup_

## Theme
- Night Owl
    - install from Extensions

## Extensions
- Better Haml
- Better TOML
- Bookmarks
- Bracket Pair Colorizer 2
- ESLint
- Handlebars
- Jekyll Snippets
- Jekyll Syntax Support
- JSON-Template
- Liquid
- Markdown Preview Enhanced
- MDX
- Night Owl
- Nunjucks Template
- Prettier - Code Formatter
- react-snippets
- Relative Path
- Ruby
- Sass
- stylelint
- Svelte
- Svelte for VS Code
- Tailwind CSS IntelliSense
- VSCode Ruby
- vscode-icons
- YAML

## Settings
settings.json

```json
{
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.shell.osx": "/bin/zsh",
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.fontFamily": "Menlo for Powerline",
    "window.zoomLevel": 0,
    "files.associations": {
        "*.template": "plaintext"
    },
    "[nunjucks]": {},
    "terminal.integrated.rendererType": "dom",
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "prettier.vueIndentScriptAndStyle": true,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "html.format.indentHandlebars": true,
    "html.format.indentInnerHtml": true,
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorCustomizations": {
        "[Night Owl]": {
            "activityBar.background": "#000C1D",
            "activityBar.border": "#102a44",
            "sideBar.background": "#001122",
            "sideBar.border": "#102a44",
            "sideBar.foreground": "#8BADC1"
        }
    },
    "liquid.format": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "vsicons.dontShowNewVersionMessage": true,
    "editor.tabSize": 2,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "[css]": {
        "editor.suggest.insertMode": "replace"
    },
    "css.validate": false, // for stylelint plugin
    "scss.validate": false // for stylelint plugin
}

```