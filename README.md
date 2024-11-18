## 袁果锅生态

用于 git cz 提交规范

## 快速开始

1. 安装依赖

```bash
npm install -g commitizen  //全局安装  安装过可以不用安装

npm install cz-customizable
npm install @shixinde/guoguo-cz
```

2. 配置

在 package.json 中添加 `config.commitizen ` 配置

```js
  "scripts": {
     "gitcz": "git-cz"
    },
  "config": {
    "commitizen": {
      "path": "node_modules/cz-customizable"
    },
    "cz-customizable": {
      "config": "node_modules/@shixinde/guoguo-cz/commitlint.config.cjs"
    }
  }

```


## 扩展： 格式化工具  
    
    安装
      npm install -D prettier pretty-quick

     
    执行
      "scripts": {
        "lint": "pretty-quick --staged",
      },

    使用
      npm run lint | pnpm lint

