# React-TS-UI

## 流程
- 规范文件目录结构
- 添加`VS Code`对`typescript`的检查
  ```js
  // 第一步 新建文件 /项目根目录/.vscode/settings.json
  // 第二部 输入内容
  {
    "eslint.validate": [
      "javascript",
      "javascriptreact",
      {
        "language": "typescript",
        "autoFix": true
      },
      {
        "language": "typescriptreact",
        "autoFix": true
      }
    ]
  }
  ```
- 样式解决方案
  * 内联CSS
  * CSS IN JS(如`styled-components`)
  * SCSS等预处理器(`推荐`)
- 安装`cnpm i -S node-sass`


## 参考链接
- [慕课教程](https://coding.imooc.com/class/428.html)