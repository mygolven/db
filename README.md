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
业务背景：为了更高的安全性、便捷性，进行权限管理和账户管理，管控具体人对
库、表、列的操作权限，高风险操作的判断和转变为低风险操作的技术手段。用户无需感
知数据库账号密码，使用更便捷、更安全。提供数据管理、结构设计、数据变更、追踪、
回滚、权限管理、资源申请等数据库解决方案一站式服务。
 系统特点：开发者服务项目（Kool-DB）是一种易用、稳定、快速、安全
的数据库服务。它可以支持SQL查询，集群管理，系统管理，权限管理。支持集
群和元数据的全量同步和增量同步。
Kool-DB系统的基本功能模块有：SQL查询，权限管理，集群管理，日志管理，owner
库表。
1. SQL查询：用户可以查询自己拥有权限的集群,库表列的数据,可以增加,修改,删除表
数据,可以直接在查询结果集进行编辑
2. 权限管理：供用户管理权限，用户可以申请数据库的权限，然后在我的工单里面可
以查看申请记录，审批通过后，可以在我的权限里面看到自己拥有的权限
3. 集群&库管理：给用户提供集群以及数据库的管理，用户能看到并使用所有已有权限
查看和变更导出的集群以及数据库，包括表列索引的查看和变更。
4. 系统管理：全量同步RDS系统中MySQL、Mongo、PostgreSQL集群、实例相关信
息，全量采集MySQL、PostgreSQL库表列索引数据，为后续操作提供数据支
撑。
文档名称 文档密级
2021-1-8 华为保密信息,未经授权禁止扩散 第 5 页, 共 25 页
5. 日志管理：进行SQL查询后，可以在日志管理看到对应的查询记录，可以根据搜索
条件筛选对应的日志记录
6. Owner库表：用户可以通过进入集群，数据库，数据表三大模块菜单，根据名称进行
模糊搜索，高级搜索数据，可以查看权限管理和权限详情

地址：
线上：http://kool-db.his.huawei.com/kooldb/#
beta: http://kool-db.his-beta.huawei.com/kooldb_beta/#/page/workbench
