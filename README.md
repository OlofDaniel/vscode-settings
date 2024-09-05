# vscode-settings
vscode-settings

Settings:

    {
    "workbench.iconTheme": "vscode-icons",

    //Orientering/Barer/Streck
    "workbench.statusBar.visible": true,
    "workbench.sideBar.location": "left",
    "workbench.editor.showTabs": "multiple",
    "editor.minimap.enabled": true,
    "editor.linkedEditing": true,
    "editor.renderLineHighlight": "none",
    "editor.guides.indentation": false, //For-loop streck
    //"editor.scrollbar.verticalScrollbarSize": 10,
    "editor.padding.top": 25,
    "workbench.startupEditor": "none",
    "breadcrumbs.enabled": false,


    //Under kodning
    "editor.snippetSuggestions": "top",


    //Färger
    "workbench.colorCustomizations": {
        "editor.background": "#272c31", //Bakgrund

        "titleBar.activeBackground": "#272c31", //Titel-bar
        "titleBar.activeForeground": "#ffffff82",
        "titleBar.inactiveBackground": "#272c31",
        "titleBar.border": "#272c3100", //Border över tabs

        "sideBar.background": "#1a1d21", //Sidbaren
        "activityBar.background": "#1a1d21",
        "activityBar.foreground": "#405363",
        "sideBar.border": "#1a1d21",        //Mellan öppen o editor
        "activityBar.border": "#1a1d21",   // Mellan ikoner o öppen
        "sideBarSectionHeader.background": "#1a1d21",  // Bakom Outline, timeline
        "sideBarSectionHeader.border": "#1a1d21",


        "scrollbar.shadow": "#272c31",    //Skroll-bar
        "scrollbarSlider.background": "#4d4d4d",
        "scrollbarSlider.hoverBackground": "#4d4d4d",
        "scrollbarSlider.activeBackground": "#4d4d4d",
        


        "editorLineNumber.activeForeground": "#ffffff", //Editor nummer
        "editorLineNumber.foreground": "#5a6672",

        "focusBorder":"#1d1f21fe", //Ram när vald (sidbar)

        "tab.activeBackground": "#384048",  //Tabs
        "tab.inactiveBackground": "#272c31",
        "tab.activeForeground": "#ffffff",
        "tab.inactiveForeground": "#5a6672",
        "tab.border": "#384048",
        "tab.activeBorderTop": "#384048",
        "editorGroupHeader.tabsBackground": "#272c31", //Bakgrund bakom tabs
        "editorGroupHeader.tabsBorder": "#272c3100", // Border runt tabs

        "statusBar.background": "#272c31",    //Statusbaren
        "statusBar.foreground": "#FFFFFF",
        "statusBar.border": "#1d1f21fe",
        "statusBar.noFolderBackground": "#1d1f21fe",
        "statusBar.noFolderForeground": "#FFFFFF",
        "statusBar.debuggingBackground": "#1d1f21fe",
        "statusBar.debuggingForeground": "#FFFFFF",
        "statusBarItem.remoteBackground": "#272c31",
        

        "quickInput.background": "#1d1f21fe",   // Command center
        "quickInput.foreground": "#FFFFFF", 

        "terminal.background": "#1a1d21",       // Terminalen
        "terminal.foreground": "#CCCCCC", 
        "panel.background": "#1a1d21",          // Bakgrundsfärgen för själva panelområdet (terminalen, output etc.)



    },
    "workbench.colorTheme": "Visual Studio Dark",
    "terminal.integrated.cursorStyleInactive": "underline",

    "editor.hideCursorInOverviewRuler":false,

    "editor.scrollbar.horizontal": "hidden", //scrollbar borta
    "editor.scrollbar.vertical":"hidden",
    "editor.scrollbar.verticalScrollbarSize": 0,

    "editor.lightbulb.enabled": "off",

    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "string",
                "settings": {
                    "foreground": "#87e4b8"  // Exempel på en orange färg för strängar
                }
            }
        ]
    },
    "window.commandCenter": false,
    "editor.minimap.showSlider": "always"
    



    }
    
