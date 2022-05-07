# vscode-settings

```bash
# 在VSCode（2016年5月）中，现在可以在命令行中列出已安装的扩展名
code --list-extensions
```

### extensions

```markdown
alefragnani.Bookmarks
alefragnani.project-manager
AT-9420.console-helper
bradgashler.htmltagwrap
cyberbiont.vscode-open-in-typora
dbaeumer.vscode-eslint
donjayamanne.githistory
DotJoshJohnson.xml
dsznajder.es7-react-js-snippets
eamodio.gitlens
EditorConfig.EditorConfig
esbenp.prettier-vscode
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
formulahendry.code-runner
GitHub.copilot
Gruntfuggly.todo-tree
IgorSbitnev.error-gutters
jasonnutter.search-node-modules
johnpapa.vscode-peacock
kisstkondoros.vscode-gutter-preview
MS-CEINTL.vscode-language-pack-zh-hans
naumovs.color-highlight
OBKoro1.korofileheader
oderwat.indent-rainbow
PKief.material-icon-theme
rvest.vs-code-prettier-eslint
shardulm94.trailing-spaces
SirTori.indenticator
streetsidesoftware.code-spell-checker
TabNine.tabnine-vscode
techer.open-in-browser
veggiemonk.theme-solarized-light-fjs
```

### settings.json

```json
{
  "editor.inlineSuggest.enabled": true,
  "fileheader.configObj": {
    "autoAdd": false
  },
  "files.autoSave": "afterDelay",
  "git.confirmSync": false,
  "git.autofetch": true,
  "tabnine.experimentalAutoImports": true,
  "workbench.colorTheme": "Solarized-light-fjs",
  "workbench.iconTheme": "material-icon-theme",
  "[javascript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  }
}
```







