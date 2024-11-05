{ "workbench.colorCustomizations": {

    //Editor
    "editor.background": "#1a1c1f",
    "editor.foreground": "#DCDEDF",


    //Sidebar
    "sideBar.border": "#000000",
    "sideBarSectionHeader.border": "#00000000",
    "sideBarTitle.background": "#141517",  // Ändrar bakgrundsfärgen på rubrikfältet 
    "sideBarTitle.foreground": "#141517",
    "sideBarSectionHeader.foreground": "#ACACAC",
    "sideBar.foreground": "#ACACAC",
    "sideBar.background": "#141517",
    "sideBarSectionHeader.background": "#141517",  // Bakom Outline, timeline

    "list.hoverBackground": "#323d4c",
    "list.inactiveSelectionBackground": "#323d4c",
    "list.focusOutline": "#00000000",
    "list.activeSelectionBackground": "#323d4c",

    "focusBorder": "#00000000",

    //Activity bar
    "activityBar.border": "#00000000",
    "activityBar.background": "#141517",
    "activityBar.foreground": "#DCDEDF",
    "activityBar.inactiveForeground": "#8C8C8C",


    //Editor number
    "editorLineNumber.activeForeground": "#AEAEAE", //Editor nummer
    "editorLineNumber.foreground": "#5a6672a2",


    //Tab
    "tab.border": "#00000000",
    "tab.activeBorderTop": "#00000000",
    "tab.activeBorder": "#00000000",
    "tab.hoverBorder": "#00000000",
    "tab.inactiveBorder": "#00000000",
    "editorGroupHeader.tabsBorder": "#00000000",

    "tab.hoverBackground": "#00000000",
    "tab.hoverForeground": "#ffffff",

    "tab.activeBackground": "#141517", 
    "tab.inactiveBackground": "#141517",
    "tab.activeForeground": "#FFFFFF",
    "tab.inactiveForeground": "#6a6a6ac8",
    "editorGroupHeader.tabsBackground": "#141517", //Bakgrund bakom tabs


    //Statusbar
    "statusBar.border": "#000000",
    "statusBar.background": "#141517",
    "statusBar.foreground": "#AEAEAE",
    "statusBar.noFolderBackground": "#141517",


    //Panel
    "panel.border": "#5a6672a2",


    //Title bar
    "titleBar.activeBackground": "#141517", 
    "titleBar.activeForeground": "#141517",
    "titleBar.inactiveBackground": "#141517",
    "titleBar.inactiveForeground": "#141517",
    "titleBar.border": "#000000",


    //Scroll
    "scrollbar.shadow": "#00000000",
    "scrollbarSlider.background": "#434A5650",
    "scrollbarSlider.hoverBackground": "#434A5670",
    "scrollbarSlider.activeBackground": "#434A5690",
    "scrollbarSlider.border": "#00000000",


    //Command center
    "quickInput.background": "#141517",
    "quickInput.foreground": "#DCDEDF", 


    //Terminal
    "terminal.background": "#141517",
    "terminal.foreground": "#DCDEDF", 
    "panel.background": "#141517",
    "terminal.border": "#00000000" ,
    "editorOverviewRuler.border": "#00000000",
},


//Text color
"editor.tokenColorCustomizations": {
"comments": "#0282c7b8",           // Kommentarers färg
"keywords": "#fda9eb",           // Nyckelord (t.ex. if, for, return)
"strings": "#98e7ac",            // Strängar (text inom citationstecken)
"variables": "#87dbff",          // Variabelnamn
"textMateRules": [
  {
    "scope": "entity.name.type.class", // Klasser (t.ex. Sorting)
    "settings": {
      "foreground": "#fffd89"
    }
  },
  {
    "scope": "entity.name.function", // Metoder (t.ex. not_efficient_sorting)
    "settings": {
      "foreground": "#c8acff"
    }
  },
  {
    "scope": "variable.parameter", // Parametrar i metoder (t.ex. int[] array)
    "settings": {
      "foreground": "#ff528f"
    }
  },
  {
    "scope": "punctuation.section.block.begin", // För "{" (öppningsmåsvingen)
    "settings": {
      "foreground": "#ffffff"  // Färgen du vill ha för "{"
    }
  },
  {
    "scope": "punctuation.section.block.end", // För "}" (stängningsmåsvingen)
    "settings": {
      "foreground": "#ffffff"  // Färgen du vill ha för "}"
    }
  },
  {
    "scope": "keyword.operator.assignment", // För "=" tecknet
    "settings": {
      "foreground": "#ffffff"  // Färgen du vill ha för "="
    }
  },
  {
    "scope": "constant.numeric", // Matchar siffror
    "settings": {
      "foreground": "#4d90b2" // Färgen för siffror (röd i detta fall)
    }
  },
]

},


//Editor
"editor.folding": true,
"editor.hideCursorInOverviewRuler": false,
"editor.cursorStyle": "block",
"editor.cursorWidth": 0,
"editor.cursorBlinking": "solid",
"editor.bracketPairColorization.enabled": false,
"editor.guides.indentation": false,
"editor.renderLineHighlight": "none",
"editor.padding.top": 15,
"editor.snippetSuggestions": "top",
"editor.lightbulb.enabled": "off",
"editor.minimap.enabled": false,
"editor.minimap.showSlider": "always",
        //Text
        "editor.fontFamily": "Source Code Pro",
        "editor.fontSize": 12,
        "editor.fontLigatures": false,
        "editor.lineHeight": 1.5,
        "editor.tabSize": 4,   
        "editor.lineNumbers":"on", //<-------------
        "editor.renderWhitespace":"none",
        "editor.semanticHighlighting.enabled": true,


//Window
"window.zoomLevel": 1,

//Explorer
"explorer.compactFolders": false,


//Breadcrumbs
"breadcrumbs.enabled": false,

//Statusbar
"workbench.statusBar.visible": true,
"workbench.tree.renderIndentGuides":"none",


//Scroll
"editor.stickyScroll.enabled": false,
"editor.scrollbar.horizontal":"hidden",
"editor.scrollbar.vertical":"hidden",
"editor.scrollbar.verticalScrollbarSize": 20,

//Tab
"workbench.editor.showTabs": "none",


//Command center
"window.commandCenter": false,  


//Terminal
"terminal.integrated.cursorStyleInactive": "underline",
"terminal.integrated.fontSize": 18,
"terminal.integrated.fontFamily": "Source Code Pro",
"terminal.integrated.tabs.enabled": false,


//Titlebar
"window.titleBarStyle":"custom",
"workbench.editor.editorActionsLocation": "hidden", //tar bort knapparna längst till höger


//Extentions
"redhat.telemetry.enabled": false,
"extensions.ignoreRecommendations": true,
"workbench.iconTheme": "vscode-icons",


//Startup screen
"workbench.startupEditor": "none",
"window.restoreWindows": "none",
"workbench.layoutControl.enabled": false,
"workbench.activityBar.location": "hidden",
"editor.minimap.renderCharacters": false,
"workbench.colorTheme": "Visual Studio Dark",


}
