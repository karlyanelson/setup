# Visual Studio Code Setup

_see Ian's setup: https://iansdevblog.netlify.com/posts/my_visual_studio_code_setup_

## Theme
- Night Owl
    - install from Extensions

## Extensions
- Better TOML
- Bookmarks
- Bracket Pair Colorizer 2
- ESLint
- Jekyll Snippets
- Jekyll Syntax Support
- Liquid
- Markdown Preview Enhanced
- Night Owl
- Prettier - Code Formatter
- Svelte
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
    "workbench.colorTheme": "Night Owl",
    "window.zoomLevel": 1,
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
    "liquid.format": true
}

```