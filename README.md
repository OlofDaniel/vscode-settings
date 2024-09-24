{
    "workbench.colorCustomizations": {


        //Editor
        "editor.background": "#232628", 
        "editor.foreground": "#DCDEDF",

    
        //Sidebar
        "sideBar.border": "#00000000",
        "sideBarSectionHeader.border": "#00000000",
        "sideBarTitle.background": "#191a1c",  // Ändrar bakgrundsfärgen på rubrikfältet 
        "sideBarTitle.foreground": "#AEAEAE",
        "sideBarSectionHeader.foreground": "#ACACAC",
        "sideBar.foreground": "#ACACAC",
        "sideBar.background": "#191a1c",
        "sideBarSectionHeader.background": "#191a1c",  // Bakom Outline, timeline

        "list.hoverBackground": "#323d4c",
        "list.inactiveSelectionBackground": "#323d4c",
        "list.focusOutline": "#00000000",
        "list.activeSelectionBackground": "#323d4c",

        "focusBorder": "#00000000",

        //Activity bar
        "activityBar.border": "#00000000",
        "activityBar.background": "#232628",
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
        "tab.hoverForeground": "#969696",

        "tab.activeBackground": "#232628", 
        "tab.inactiveBackground": "#191a1c",
        "tab.activeForeground": "#DCDEDF",
        "tab.inactiveForeground": "#969696",
        "editorGroupHeader.tabsBackground": "#191a1c", //Bakgrund bakom tabs


        //Statusbar
        "statusBar.border": "#00000000",
        "statusBar.background": "#191a1c",
        "statusBar.foreground": "#AEAEAE",


        //Panel
        "panel.border": "#00000000",


        //Title bar
        "titleBar.activeBackground": "#232628", 
        "titleBar.activeForeground": "#232628",
        "titleBar.inactiveBackground": "#232628",
        "titleBar.inactiveForeground": "#232628",
        "titleBar.border": "#00000000",


        //Scroll
        "scrollbar.shadow": "#00000000",
        "scrollbarSlider.background": "#434A5650",
        "scrollbarSlider.hoverBackground": "#434A5670",
        "scrollbarSlider.activeBackground": "#434A5690",
        "scrollbarSlider.border": "#00000000",


        //Command center
        "quickInput.background": "#191a1c",
        "quickInput.foreground": "#DCDEDF", 


        //Terminal
        "terminal.background": "#232628",
        "terminal.foreground": "#DCDEDF", 
        "panel.background": "#232628",
        "terminal.border": "#00000000" ,
    },


    //Text color
    "editor.tokenColorCustomizations": {
    "comments": "#00ff993c",           // Kommentarers färg
    "keywords": "#87dbff",           // Nyckelord (t.ex. if, for, return)
    "strings": "#40c6ff",            // Strängar (text inom citationstecken)
    "variables": "#dbdbdb",          // Variabelnamn
    "textMateRules": [
      {
        "scope": "entity.name.type.class", // Klasser (t.ex. Sorting)
        "settings": {
          "foreground": "#be9bff"
        }
      },
      {
        "scope": "entity.name.function", // Metoder (t.ex. not_efficient_sorting)
        "settings": {
          "foreground": "#00b3ff"
        }
      },
      {
        "scope": "variable.parameter", // Parametrar i metoder (t.ex. int[] array)
        "settings": {
          "foreground": "#00ebd4"
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
    ]
},


    //Editor
    "editor.bracketPairColorization.enabled": false,
    "editor.guides.indentation": false,
    "editor.renderLineHighlight": "none",
    "editor.padding.top": 15,
    "editor.snippetSuggestions": "top",
    "editor.lightbulb.enabled": "off",
    "editor.minimap.enabled": true,
    "editor.minimap.showSlider": "always",
            //Text
            "editor.fontFamily": "JetBrains Mono",
            "editor.fontSize": 15,
            "editor.fontLigatures": false,
            "editor.lineHeight": 1.5,
            "editor.tabSize": 10,   
            "editor.lineNumbers":"on", //<-------------
            "editor.renderWhitespace":"none",
            "editor.semanticHighlighting.enabled": true,


    //Breadcrumbs
    "breadcrumbs.enabled": false,


    //Statusbar
    "workbench.statusBar.visible": true,


    //Sidebar
    "workbench.sideBar.location": "left",
    "workbench.tree.renderIndentGuides":"none",

    //Scroll
    "editor.stickyScroll.enabled": false,
    "editor.scrollbar.horizontal":"hidden",
    "editor.scrollbar.vertical":"visible",
    "editor.scrollbar.verticalScrollbarSize": 0,


    //Command center
    "window.commandCenter": false,  


    //Terminal
    "terminal.integrated.cursorStyleInactive": "underline",


    //Titlebar
    "window.titleBarStyle":"custom",


    //Extentions
    "redhat.telemetry.enabled": false,
    "extensions.ignoreRecommendations": true,
    "workbench.iconTheme": "vscode-icons",


    //Startup screen
    "workbench.startupEditor": "none",
    "window.restoreWindows": "none",
    "workbench.layoutControl.enabled": false,
    "workbench.activityBar.location": "bottom",
    "editor.minimap.renderCharacters": false,
    "workbench.colorTheme": "Visual Studio Dark",
}