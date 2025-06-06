``` bash
{
  // 默认格式化工具选择prettier
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  // 保存的时候自动格式化
  "editor.formatOnSave": true,
  //开启自动修复
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.fixAll.eslint": "explicit",
    "source.fixAll.stylelint": "explicit"
  },
  // 配置stylelint检查的文件类型范围
  "stylelint.validate": ["css", "scss", "vue", "html"], // 与package.json的scripts对应
  "stylelint.enable": true,
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[dotenv]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  // 配置语言的文件关联
  "files.associations": {
    "pages.json": "jsonc", // pages.json 可以写注释
    "manifest.json": "jsonc" // manifest.json 可以写注释
  },
  "cSpell.words": [
    "Aplipay",
    "climblee",
    "commitlint",
    "dcloudio",
    "iconfont",
    "qrcode",
    "refresherrefresh",
    "scrolltolower",
    "tabbar",
    "Toutiao",
    "unibest",
    "uvui",
    "Wechat",
    "WechatMiniprogram",
    "Weixin"
  ],
  "typescript.tsdk": "node_modules\\typescript\\lib",
  "explorer.fileNesting.enabled": true,
  "explorer.fileNesting.expand": false,
  "explorer.fileNesting.patterns": {
    "package.json": "pnpm-lock.yaml,pnpm-workspace.yaml,LICENSE,.gitattributes,.gitignore,.gitpod.yml,CNAME,.npmrc,.browserslistrc",
    ".eslintrc.cjs": ".eslintignore,.prettierignore,.stylelintignore,.commitlintrc.*,.prettierrc.*,.stylelintrc.*,.eslintrc-auto-import.json,.editorconfig,.commitlint.cjs"
  },
  "editor.fontFamily": "'Maple Mono NF CN Medium'", //,'Sarasa Mono TC',Consolas,'Sarasa Fixed Slab HC','Fira Code','JetBrains Mono','Cascadia Code','Intel One Mono','HarmonyOS Sans','LXGW WenKai Mono'
  "editor.tabSize": 2,
  "editor.fontLigatures": true,
  //控制台字体
  "terminal.integrated.fontFamily": "'Maple Mono NF CN Medium'",
  "editor.semanticTokenColorCustomizations": {
    "rules": {
      "interface": {
        "italic": true
      },
      "selfParameter": {
        "italic": true
      },
      "keyword": {
        "italic": true
      },
      "*.static": {
        "italic": true
      }
    }
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          // "comment",//注释
          // "function",//函数
          "constant.language.undefined",
          "constant.language.null",
          "constant.language.nullptr",
          "meta.type keyword.operator.expression.typeof",
          "meta.type keyword.operator.expression.keyof",
          "keyword.control",
          "keyword.function",
          "keyword.operator.new",
          "keyword.operator.borrow.and.rust",
          "storage.type",
          "storage.modifier",
          "variable.language.this",
          "markup.italic"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  }
}

```