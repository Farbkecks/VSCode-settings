# VSCode-settings

## Hotkeys
	editor.action.copyLinesDownAction = ctrl + d
  	editor.action.commentLine = strg + w

## Settings.json
	  "terminal.integrated.defaultProfile.windows": "Command Prompt",
	  "editor.minimap.enabled": false,  
	  "editor.smoothScrolling": true,
	  "editor.parameterHints": false,

## cmd Makro
mit f6 automatisch "main.py" in cmd ausführen
diese Extension installieren:
https://marketplace.visualstudio.com/items?itemName=geddski.macros

### Settings.json
	"macros": {
            "commentCMD": [
            	"workbench.action.togglePanel",
            	{"command": "workbench.action.terminal.sendSequence","args": { "text": "main.py\u000D" }}
            ]
   	},
### keybindings.json
	{
        	"key": "f6",
        	"command": "macros.commentCMD"
        },
	
