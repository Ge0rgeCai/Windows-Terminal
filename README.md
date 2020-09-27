# Make your Windows Terminal more beautiful

## Table of Contents

- [Final Product](#Final Product)
- [Install](#Install)
- [Beautify](#Beautify)
- [Configure Scheme](#Configure Scheme)

## Final Product
<img src="./picture/final_product.png" alt="Beautiful Terminal" style="zoom:40%;"/>
<img src="./picture/final_product2.png" alt="Beautiful Terminal" style="zoom:40%;"/>

## Install
Download `Windows Terminal` in Mircosoft Store
<img src="./picture/win_terminal.png" alt="WindowTerminal" style="zoom:67%;" />

## Beautify
Open the terminal Settings:
<img src="./picture/settings.png" alt="Settings" style="zoom:40%;"/>

### Beautify your Cmd:

```sh
                "name": "CMD",
                "commandline": "cmd.exe",
                "hidden": false,
				"acrylicOpacity" : 0.5,
            	"background" : "#000000",  
            	//if you want add picture to background
            	//"backgroundImage" :"path of picture",
            	"backgroundImageOpacity" : 0.9,  
            	"closeOnExit" : true,
            	"colorScheme" : "CMD",  
            	"cursorColor" : "#FFFFFF",
            	"cursorShape" : "bar",
            	"fontFace" : "Consolas",
            	"fontSize" : 12,
            	"historySize" : 9001,
            	"padding" : "0, 0, 0, 0",
            	"snapOnInput" : true,
            	"startingDirectory" : "%USERPROFILE%"
            	"useAcrylic" : true   
```

### Beautify your PowerShell

``` sh
                "name": "PowerShell",
                "commandline": "powershell.exe",
                "hidden": false,
            	"acrylicOpacity" : 0.75,
            	//if you want add picture to background
            	//"backgroundImage" :"path of picture",
            	"backgroundImageOpacity" : 0.9,
            	"closeOnExit" : true,
            	"colorScheme" : "CMD",
            	"cursorColor" : "#FFFFFF",
            	"cursorShape" : "bar",
            	"fontFace" : "Consolas",
            	"fontSize" : 12,  
				"historySize" : 9001,
            	"padding" : "0, 0, 0, 0",
            	"snapOnInput" : true,
            	"startingDirectory" : "%USERPROFILE%",
            	"useAcrylic" : true 
```

## Configure Scheme

```sh
    "schemes": [        {
	            "background" : "#000000",
	            "black" : "#0C0C0C",
	            "blue" : "#0037DA",
	            "brightBlack" : "#767676",
	            "brightBlue" : "#3B78FF",
	            "brightCyan" : "#61D6D6",
	            "brightGreen" : "#16C60C",
	            "brightPurple" : "#B4009E",
	            "brightRed" : "#E74856",
	            "brightWhite" : "#F2F2F2",
	            "brightYellow" : "#F9F1A5",
	            "cyan" : "#3A96DD",
	            "foreground" : "#FFFFFF",
	            "green" : "#13A10E",
	            "name" : "CMD",     
	            "purple" : "#881798",
	            "red" : "#C50F1F",
	            "white" : "#CCCCCC",
	            "yellow" : "#C19C00"
	        },],
```

Restart your terminol