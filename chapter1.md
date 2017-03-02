# About Visul Studio Code

1. vetur : support vue
2. eslint

about configuration:

```
// 将设置放入此文件中以覆盖默认设置
{
    "workbench.colorTheme": "Monokai",
    "workbench.iconTheme": "vs-seti",
    // 控制已更新文件的自动保存。接受的值:“off”、"afterDelay”、"onFocusChange”(编辑器失去焦点)、"onWindowChange”(窗口失去焦点)。如果设置为“afterDelay”，则可在 "files.autoSaveDelay" 中配置延迟。
    "files.autoSave": "onWindowChange",
    // 控制是否显示 minimap
    "editor.minimap.enabled": true,
    // Render the actual characters on a line (as opposed to color blocks)
    "editor.minimap.renderCharacters": false,
    // Controls if the editor should allow to move selections via drag and drop.
    "editor.dragAndDrop": true,
    // 控制是否应换行。换行依据为 min(editor.wrappingColumn, viewportWidthInColumns)。
    "editor.wordWrap": "on",
    // 控制光标样式，接受的值为 "block"、"line" 和 "underline"
    "editor.cursorStyle": "block",
    // 控制光标动画样式，可能的值为 "blink"、"smooth"、"phase"、"expand" 和 "solid"
    "editor.cursorBlinking": "expand",
    // 配置语言的文件关联(如: "*.extension": "html")。这些关联的优先级高于已安装语言的默认关联。
    "files.associations": {
        "*.vue": "vue"
    },
    // 为指定的语法定义配置文件或使用带有特定规则的配置文件。
    "emmet.syntaxProfiles": {
        "vue-html": "html",
        "vue": "html"
    },
    // An array of language ids which should be validated by ESLint
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        { "language": "html", "autoFix": true },
        { "language": "vue", "autoFix": true }
    ],
    // Run the linter on save (onSave) or on type (onType)
    "eslint.run": "onSave",
    // Turns auto fix on save on or off.
    "eslint.autoFixOnSave": true
}
```



