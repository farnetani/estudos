# Eslint e Extensões para Visual Studio Code

``` js

ctrl+alt+f no windows
ctrl+shit+p e selecionar ESLint: Fix all problems

Para evitar isso, ativar o autoFixOnSave

Ir em: File>Preferences>Settings

    "eslint.autoFixOnSave": true,
    "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
    "vetur.format.defaultFormatter.js": "vscode-typescript",
    "vetur.format.defaultFormatter.html": "js-beautify-html",
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "typescript",
        {
            "language": "vue",
            "autoFix": true
        },
        {
            "language": "html",
            "autoFix": true
        },
        {
            "language": "javascript",
            "autoFix": true
        }
    ]
```

Fonte: http://www.vuejs-brasil.com.br/deixe-o-eslint-trabalhar-para-voce-no-visual-studio-code/

```
