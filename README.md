# VSCode-settings

## Hotkeys
	editor.action.copyLinesDownAction = ctrl + d
  	editor.action.commentLine = strg + w
	workbench.action.togglePanel = F5

## Settings.json
	"terminal.integrated.defaultProfile.windows": "Command Prompt",
	"editor.minimap.enabled": false,  
	"editor.smoothScrolling": true,
	"editor.parameterHints": false,
	"vim.handleKeys": {
	  	"<C-c>": false,
		"<C-v>": false,},
	"vim.useSystemClipboard": false,  
	
## Extensions
* Arduino
* Better TOML
* c/C++
* crates
* marcros
* One Dark Pro
* Path Intellisense
* Python
* rust-analyzer
* Tabnine
* Vim
* CodeTogether
* Error Lens

## cmd Makro
mit f6 automatisch "main.py" in cmd ausführen <br>
diese Extension installieren:
https://marketplace.visualstudio.com/items?itemName=geddski.macros

### Settings.json
	"macros": {
            "commentCMD": [
            	"workbench.action.terminal.toggleTerminal",
            	{"command": "workbench.action.terminal.sendSequence","args": { "text": "main.py\u000D" }}
            ]
   	},
### keybindings.json
	{
        	"key": "f6",
        	"command": "macros.commentCMD"
	},
	
