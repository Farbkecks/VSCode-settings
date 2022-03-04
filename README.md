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
	"macros": {
         	commentCMD": [
        		"workbench.action.togglePanel",
         		{"command": "workbench.action.terminal.sendSequence","args": { "text": "main.py\u000D" }}]},

mit f6 automatisch "main.py" in cmd ausführen
diese Extension installieren:
https://marketplace.visualstudio.com/items?itemName=geddski.macros


	
