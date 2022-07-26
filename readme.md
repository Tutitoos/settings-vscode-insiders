# Configuración Visual Studio Insiders - Tutitoos

Visual Studio Code recoge datos de telemetría

```json
{
    "telemetry.telemetryLevel": "off"
}
```

Para modificar la configuración del usuario, utilizarás el editor de configuración para revisar y cambiar la configuración de VS Code.

```json
{
    "editor.suggestSelection": "first",
    "editor.fontFamily": "'Cascadia Code', monospace",
    "editor.fontLigatures": true,
    "editor.inlineSuggest.enabled": true,
    "editor.linkedEditing": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.semanticHighlighting.enabled": true,
    "editor.guides.bracketPairs": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.wordWrap": "on",
    "editor.tabCompletion": "on",
    "editor.wordWrapColumn": 35,
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.codeActionsOnSave": {
        "source.fixAll": true
    }
}
```

```json
{
    "workbench.startupEditor": "welcomePageInEmptyWorkbench",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Andromeda Colorizer",
    "workbench.colorCustomizations": {}
}
```

```json
{
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue"
}
```

```json
{
    "files.autoSave": "onFocusChange"
}
```

```json
{
    "javascript.suggest.autoImports": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "typescript.suggest.autoImports": true,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "typescript.implementationsCodeLens.enabled": true,
    "typescript.locale": "es",
    "svelte.enable-ts-plugin": true
}
```

SonarLint se puede utilizar junto con SonarCloud, permitiendo a su equipo
estar siempre en la misma página cuando se trata de la calidad y la seguridad del código.

```json
{
    "sonarlint.output.showAnalyzerLogs": false,
    "sonarlint.disableTelemetry": false,
    "sonarlint.output.showVerboseLogs": false
}
```

ESLint analiza estáticamente su código para encontrar rápidamente los problemas. Está integrado en la mayoría de los editores de texto y puedes ejecutar ESLint como parte de tu canal de integración continua.

```json
{
    "eslint.codeAction.showDocumentation": {
        "enable": true
    }
}
```

Prettier es un formateador de código con opinión. Impone un estilo consistente analizando su código y reimprimiéndolo con sus propias reglas que tienen en cuenta la longitud máxima de la línea, envolviendo el código cuando es necesario.

```json
{
    "prettier.arrowParens": "always",
    "prettier.bracketSpacing": true,
    "prettier.embeddedLanguageFormatting": "auto",
    "prettier.htmlWhitespaceSensitivity": "css",
    "prettier.insertPragma": false,
    "prettier.jsxSingleQuote": false,
    "prettier.printWidth": 100,
    "prettier.proseWrap": "preserve",
    "prettier.quoteProps": "as-needed",
    "prettier.requirePragma": false,
    "prettier.semi": true,
    "prettier.singleQuote": false,
    "prettier.trailingComma": "es5",
    "prettier.useTabs": false,
    "prettier.tabWidth": 4
}
```
