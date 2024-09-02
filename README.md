## 袁果锅生态

用于 git cz 提交规范

## 快速开始

1. 安装依赖

```bash
npm install -D cz-git
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
      "path": "node_modules/cz-git",
      "czConfig": "node_modules/@shixinde/guoguo-cz/commitlint.config.cjs"
    }
  },

```
