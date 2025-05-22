# 仿造maimai DX Prism Plus 官网的动态背景

## 项目简介
本项目提供了一个类似于 maimai DX Prism Plus 游戏官网的动态背景效果。该效果通过 HTML 和 CSS 实现，适用于个人网站、项目展示或其他需要动态视觉效果的场景。

## 功能特点
- **动态装饰效果**：模拟游戏官网的动态装饰背景，包括闪烁的星星、流星、彩虹等。
- **兼容性**：兼容主流浏览器，包括 Chrome、Firefox、Safari 和 Edge。

## 使用方法
### 1. 下载本项目
1. 下载本项目文件并解压到你所在的项目目录中。
   - 如果你使用的是 Git，可以通过以下命令克隆项目：
     ```bash
     git clone https://github.com/your-repo-url/maimai-dx-prism-plus-background.git
     ```
   - 如果你直接下载 ZIP 文件，请解压到你的项目目录中。

### 2. 添加 CSS 文件
在你的 HTML 文件的 `<head>` 部分，添加以下代码以引入项目中的 CSS 文件：
```html
<link rel="stylesheet" href="lib/site.css">
<style>
  html, body { width: 100vw; height: 100vh; margin: 0; padding: 0; overflow: hidden; }
  body { background: transparent; }
</style>
```

### 3. 添加 HTML 结构
在你的 HTML 文件的 `<body>` 部分，添加以下代码以创建动态背景的 HTML 结构：
```html
<div class="maiDecorationBg">
  <div class="shines-layer">
    <div class="shines">
      <div class="shine diamond-pink"></div>
      <div class="shine diamond-yellow"></div>
      <div class="shine diamond-white"></div>
      <div class="shine star-white"></div>
      <div class="shine star-yellow-left"></div>
      <div class="shine star-yellow-right"></div>
    </div>
  </div>
  <div class="background-layer">
    <div class="pattern-layer"></div>
    <div class="decoration-container">
      <div class="auroras">
        <div class="aurora aurora-front"></div>
        <div class="aurora aurora-back"></div>
      </div>
      <div class="clouds">
        <div class="cloud front-left"></div>
        <div class="cloud front-right"></div>
        <div class="cloud front-center"></div>
        <div class="cloud back-left"></div>
        <div class="cloud back-right"></div>
        <div class="cloud back-center"></div>
      </div>
      <div class="moon"></div>
    </div>
    <div class="shooting-stars">
      <div class="shooting-star shooting-star1">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail green"></div>
          <div class="shooting-star-head green"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star2">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail"></div>
          <div class="shooting-star-head"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star3">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail pink"></div>
          <div class="shooting-star-head pink"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star4">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail green"></div>
          <div class="shooting-star-head green"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star5">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail pink"></div>
          <div class="shooting-star-head pink"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star6">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail"></div>
          <div class="shooting-star-head"></div>
        </div>
      </div>
      <div class="shooting-star shooting-star7">
        <div class="shooting-star-inner">
          <div class="shooting-star-tail"></div>
          <div class="shooting-star-head"></div>
        </div>
      </div>
    </div>
    <div class="rainbow"></div>
    <div class="rainbow-bottom"></div>
  </div>
</div>
```

## 示例
你可以访问项目文件夹下的"index.html" 查看动态背景效果的实际运行情况。

## 贡献
欢迎提交 Issues 或 Pull Requests 来帮助改进此项目。

## 许可
本项目遵循 [MIT License](LICENSE)。
