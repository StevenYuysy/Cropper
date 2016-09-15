# Amaze UI cropper
---

[Cropper 插件](https://github.com/stevenyuysy/Cropper) Amaze UI 样式移植。

- [使用示例]()
- [API 文档]()

**使用说明：**

1. 获取 Amaze UI cropper

  - [直接下载]
  - 使用 NPM: `npm install amazeui-cropper`

2. 在 Amaze UI 样式之后引入 cropper 样式（`dist` 目录下的 CSS）：

  Amaze UI cropper 依赖 Amaze UI 样式。

  ```html
  <link rel="stylesheet" href="path/to/amazeui.min.css"/>
  <link rel="stylesheet" href="path/to/amazeui.cropper.min.css"/>
  ```

3. 引入 cropper 插件（`dist` 目录下的 JS）：

  ```html
  <script src="path/to/jquery.min.js"></script>
  <script src="path/to/amazuui.min.js"></script>
  <script src="path/to/cropper.min.js"></script>
  ```

4. 初始化 cropper:

  ```js
  $(function() {
      $('#my-cropper').cropper();
  });
  ```
