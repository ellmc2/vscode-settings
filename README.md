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
  "editor.fontFamily": "'Cascadia Code', Menlo, Monaco, 'Courier New', monospace", // 编辑器字体
  "editor.fontLigatures": true, // 编辑器字体启动连字
  "files.autoSave": "afterDelay", // 自动保存
  "git.confirmSync": false, // 当要同步Git远端存储库时，不需要再提问
  "git.autofetch": true, // VS Code 自动去检测 Git 远端是否有发生新的更改
  "tabnine.experimentalAutoImports": true, // tabnine插件自动导入
  "workbench.colorTheme": "Solarized-light-fjs", // 工作台颜色主题
  "workbench.iconTheme": "material-icon-theme", // 工作台文件图标主题
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode" // 指定vs code格式化js文件工具
  },
  "[jsonc]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint" // 指定vs code格式化jsonc文件工具
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode" // 指定vs code格式化ts文件工具
  }
}

```





[*PS: other settings*](https://www.wolai.com/s1bpqfpsgzsGnUGQMKRxMF)

