# VSCode

### Font - [Fira Code](https://github.com/tonsky/FiraCode)

## Extenstions
```
2gua.rainbow-brackets
EQuimper.react-native-react-redux
HookyQR.beautify
Serge.vsc-material-theme-italicize
Zignd.html-css-class-completion
adrianhumphreys2.silverstripe
aeschli.vscode-css-formatter
alefragnani.project-manager
bierner.markdown-preview-github-styles
bradgashler.htmltagwrap
christian-kohler.path-intellisense
clinyong.vscode-css-modules
codezombiech.gitignore
cpylua.language-postcss
cssho.vscode-svgviewer
dbaeumer.vscode-eslint
dmitriy-lodyanov.vscode-stylefmt--pr-320
dzannotti.vscode-babel-coloring
eamodio.gitlens
ecmel.vscode-html-css
eg2.vscode-npm-script
erichbehrens.pull-request-monitor
esbenp.prettier-vscode
felipecaputo.git-project-manager
flowtype.flow-for-vscode
formulahendry.auto-close-tag
formulahendry.auto-rename-tag
gayanhewa.referenceshelper
gerane.Theme-Solarized-dark
hosseinagha.vscode-open-react-component-style
ionutvmi.path-autocomplete
joshpeng.sublime-babel-vscode
karyfoundation.theme-karyfoundation-themes
leveluptutorials.theme-levelup
mhmadhamster.postcss-language
mikestead.dotenv
mrcrowl.hg
mrmlnc.vscode-less
ms-mssql.mssql
ms-python.python
ms-vsliveshare.vsliveshare
naumovs.color-highlight
octref.vetur
oderwat.indent-rainbow
pranaygp.vscode-css-peek
ricard.postcss
robertohuertasm.vscode-icons
shinnn.stylelint
spywhere.guides
stubailo.ignore-gitignore
thenikso.github-plus-theme
tht13.python
tungvn.wordpress-snippet
```

## Configuration
```
{
	"editor.minimap.enabled": true,
	"files.exclude": {
		"**/tmp": true,
		"**/node_modules": true,
		"**/bower_components": true,
		"**/build": true,
		"**/.git": true,
		"**/.svn": true,
		"**/.hg": true,
		"**/CVS": true,
		"**/.DS_Store": true
	},
	"files.watcherExclude": {
		"**/tmp/**": true,
		"**/node_modules/**": true,
		"**/bower_components/**": true,
		"**/build/**": true
	},
	"workbench.colorTheme": "Solarized Dark",
	"editor.insertSpaces": false,
	"editor.renderWhitespace": "all",
	"javascript.referencesCodeLens.enabled": true,
	"javascript.validate.enable": false,
	"editor.cursorStyle": "line",
	"editor.smoothScrolling": true,
	"editor.formatOnPaste": false,
	"window.zoomLevel": 0,
	"stylelint.config": {
		"extends": "/Users/luangjokaj/staticweb-build/tools/stylelintrc.json"
	},
	"editor.formatOnSave": false,
	"files.associations": {
		"*.css": "postcss",
		"*.js": "javascriptreact"
	},
	"path-intellisense.showHiddenFiles": true,
	"postcss.validate": false,
	"workbench.iconTheme": "vscode-icons",
	"workbench.startupEditor": "newUntitledFile",
	"git.confirmSync": false,
	"emmet.triggerExpansionOnTab": true,
	"editor.wordWrap": "on",
	"git.enableSmartCommit": true,
	"eslint.autoFixOnSave": true,
	"emmet.includeLanguages": {
		"ocaml": "html",
		"reason": "html"
	},
	"gitlens.codeLens.recentChange.enabled": false,
	"gitlens.codeLens.authors.enabled": false,
	"editor.renderIndentGuides": false,
	"projectManager.openInNewWindowWhenClickingInStatusBar": true,
	"terminal.integrated.fontFamily": "Inconsolata for Powerline",
	"flow.useNPMPackagedFlow": true,
	"gitlens.advanced.messages": {
		"suppressCommitHasNoPreviousCommitWarning": false,
		"suppressCommitNotFoundWarning": false,
		"suppressFileNotUnderSourceControlWarning": false,
		"suppressGitVersionWarning": false,
		"suppressLineUncommittedWarning": false,
		"suppressNoRepositoryWarning": false,
		"suppressResultsExplorerNotice": true,
		"suppressShowKeyBindingsNotice": true,
		"suppressUpdateNotice": false,
		"suppressWelcomeNotice": true
	},
	"indentRainbow.colors": [
		"rgba(64,64,16,0.3)",
		"rgba(32,64,32,0.3)",
		"rgba(64,32,64,0.3)",
		"rgba(16,48,48,0.3)",
		"rgba(128,32,32,0.3)"
	],
	"git.autofetch": true,
	"flow.enabled": false,
	"gitlens.currentLine.enabled": true,
	"gitlens.hovers.currentLine.enabled": true,
	"gitlens.keymap": "chorded",
	"telemetry.enableTelemetry": false,
	"gitlens.advanced.telemetry.enabled": false,
	"editor.tabSize": 4,
	"editor.detectIndentation": false,
	"gitlens.historyExplorer.enabled": true,
	"editor.fontLigatures": true,
	"editor.fontFamily": "Fira Code",
	"gitlens.gitExplorer.files.layout": "tree",
	"prettier.stylelintIntegration": true,
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"prettier.printWidth": 100,
	"prettier.trailingComma": "es5",
}
```