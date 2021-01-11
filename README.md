# setting.json 
{
  "breadcrumbs.enabled": false,
  "editor.fontFamily": "Menlo, Consolas, 'Courier New', monospace",
  "editor.formatOnSave": false,
  "editor.minimap.enabled": false,
  "editor.tabSize": 2,
  "editor.renameOnType": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "vetur.format": true,
  },
  "eslint.options": {
    "rules": {
      "one-var": "off",
      "no-mixed-operators": "off",
      "no-template-curly-in-string": "off",
      "space-before-function-paren": 1,
      "arrow-parens": "off",
      "generator-star-spacing": "off",
      "no-debugger": "off",
      "vue/require-prop-types": "off",
      "vue/max-attributes-per-line": "off",
      "vue/require-default-prop": "off",
      "vue/html-self-closing": "off",
      "vue/attributes-order": "off"
    }
  },
  "eslint.validate": [
    "javascript",
    "vue"
  ],
  "git.autofetch": true,
  "git.confirmSync": false,
  "git.enableSmartCommit": true,
  "html.format.extraLiners": "",
  "html.format.endWithNewline": true,
  "html.format.indentInnerHtml": true,
  "html.format.wrapLineLength": 0,
  "javascript.validate.enable": false,
  "javascript.implicitProjectConfig.checkJs": true,
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true, //让函数(名)和后面的括号之间加个空格
  "javascript.updateImportsOnFileMove.enabled": "always",
  "prettier.proseWrap": "never",
  "prettier.printWidth": 1000,
  "prettier.singleQuote": true,
  "prettier.semi": false,
  "prettier.trailingComma": "none",
  "terminal.integrated.rendererType": "dom",
  "vetur.format.defaultFormatter.html": "js-beautify-html",
  "vetur.format.defaultFormatter.js": "vscode-typescript",
  "vetur.format.defaultFormatterOptions": {
    "prettier": {
      "printWidth": 1000,
      "proseWrap": "never",
      "singleQuote": true,
      "semi": false,
      "trailingComma": "none",
      "wrapAttributes": false
    },
    "js-beautify-html": {
      "wrap_line_length": 0,
      "wrap_attributes": "auto"
    }
  },
  "workbench.startupEditor": "newUntitledFile",
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "todo-tree.tree.showScanModeButton": false,
  "workbench.colorTheme": "Monokai Dimmed",
  "editor.wordWrap": "on"
}
