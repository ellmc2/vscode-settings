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
CodeInChinese.EnglishChineseDictionary
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
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Quiet Light",
  "git.confirmSync": false,
  "tabnine.experimentalAutoImports": true,
  "editor.fontFamily": "'Cascadia Code', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "[typescript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "editor.inlineSuggest.enabled": true,
  "github.copilot.enable": {
    "*": true,
    "yaml": false,
    "plaintext": false,
    "markdown": false,
    "javascript": false
  },
  "security.workspace.trust.untrustedFiles": "open",
  "git.autofetch": true,
  "[typescriptreact]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "fileheader.configObj": {
    "autoAdd": false // 默认开启
  },
  "peacock.favoriteColors": [
    {
      "name": "Angular Red",
      "value": "#dd0531"
    },
    {
      "name": "Azure Blue",
      "value": "#007fff"
    },
    {
      "name": "JavaScript Yellow",
      "value": "#f9e64f"
    },
    {
      "name": "Mandalorian Blue",
      "value": "#1857a4"
    },
    {
      "name": "Node Green",
      "value": "#215732"
    },
    {
      "name": "React Blue",
      "value": "#61dafb"
    },
    {
      "name": "Something Different",
      "value": "#832561"
    },
    {
      "name": "Svelte Orange",
      "value": "#ff3d00"
    },
    {
      "name": "Vue Green",
      "value": "#42b883"
    }
  ],
  "workbench.startupEditor": "none",
  "[javascriptreact]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "[markdown]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  },
  "gitlens.views.worktrees.files.layout": "tree",
  "files.autoSave": "afterDelay"
}

```







