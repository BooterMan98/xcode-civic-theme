# README
This theme is fusion between [smockle's *Xcode Default Theme*](https://marketplace.visualstudio.com/items?itemName=smockle.xcode-default-theme) extention and [Xavier Castro's *Civic*](https://marketplace.visualstudio.com/items?itemName=xavier-castro.civic) extention.
# Preview 
![Preview](https://github.com/CsarMan/xcode-civic-theme/assets/Preview.png)

## Full Xcode inmersion
Following smockle recomendation, a more complete theme can be achieved by adding some settings to your `settings.json`.  
I must add that it would be wise to read and test what are you copying to your settings.
```
{
  "editor.cursorStyle": "line-thin",
  "editor.fontFamily": "'SF Mono', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 12,
  "editor.fontWeight": "500",
  "editor.lineHeight": 17,
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.lineHeight": 1.23,
  "editor.minimap.enabled": false,
  "editor.minimap.renderCharacters": false,
  "editor.overviewRulerBorder": false,
  "editor.renderIndentGuides": false,
  "editor.renderLineHighlight": "all",
  "workbench.activityBar.visible": false,
  "workbench.editor.tabCloseButton": "left",
  "workbench.editor.showIcons": false,
  "window.nativeTabs": true,
  "editor.tokenColorCustomizations": {
    "[Xcode Partial (Light)]": {
      "textMateRules": [
        {
          "scope": "comment",
          "settings": {
            "foreground": "#536579",
            "fontStyle": "italic"
          }
        }
      ]
    },
    "[Xcode Partial (Dark)]": {
      "textMateRules": [
        {
          "scope": "source",
          "settings": {
            "foreground": "#D4D4D4"
          }
        },
        {
          "scope": "comment",
          "settings": {
            "foreground": "#6C7986",
            "fontStyle": "italic"
          }
        }
      ]
    }
  }
}
```