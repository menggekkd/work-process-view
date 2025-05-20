# How to Use This Project

## Import into Your Website

1. Add the `script.js` and `style.css` files to your website directory

2. In the HTML file where you want to use the component (for example, `works.html`), include the following

```

<link rel="stylesheet" href="./style.css"> <script src="./script.js"></script>

```

3. Copy the example markup from index.html into your target HTML file

4. Replace the placeholder paths and labels with your own image URLs and descriptions

```

<div class="fade-img" data-label="Description of this stage">
    <img src="path/to/your-image.jpg" alt="Your image description">
</div>

```

## Customizable Options

### Change the Number of Images and Labels

Simply add or remove the following blocks in your HTML file as needed

```

<div class="fade-img" data-label="Stage 1 Description">
    <img src="image-1.jpg" alt="Image 1">
</div>
<div class="fade-img" data-label="Stage 2 Description">
    <img src="image-2.jpg" alt="Image 2">
</div>
<div class="fade-img" data-label="Stage 3 Description">
    <img src="image-3.jpg" alt="Image 3">
</div>
...
<div class="fade-img" data-label="Stage n Description">
    <img src="image-n.jpg" alt="Image n">
</div>

```

### Module Colors

You can edit the following CSS variables in style.css to adjust colors ~~and blur effect~~

```

:root {
    --image-container-bg: #00000033;
    --slider-btn-bg: #0f0f0f;
    --slider-btn-shadow: #0f0f0faa;
    --slider-bg-top: #151515;
    --slider-bg-bottom: #eee;
    --text-color: #eee;
    --text-box-bg: #0f0f0faa;
    --icon-color: #eee;
    --icon-bg: #0f0f0faa;
    --glass-blur: 20px;
}

```

## What’s Next?
### Enjoy using it~ (✿◠‿◠)
### Hope you have fun! ( •̀ ω •́ )✧

---

# 如何使用这个项目？

## 导入到你的网站

1. 将 ``script.js`` ``style.css`` 文件导入到你的网站目录里

2. 在你需要的 .html 文件（例如 ``works.html``）里以下代码

```

<link rel="stylesheet" href="./style.css">

```

```

<script  src="./script.js"></script>

```

3. 在你需要的 .html 文件（例如 ``works.html``）里使用 ``index.html`` 里所提供的代码

4. 将你的网站或网络图片的路径写入这个部分

```

<div class="fade-img" data-label=" 这里是你目前图片阶段的描述 ">
    <img src="这里是你的图片文件" alt="这里是你的图片文件的 alt">
</div>

```

## 可以自定义的部分

### 改变要切换的图片数量和文本数量

只需要改变你在你的网站 .html 文件 里写入的这个部分就可以了

```
works.html

<div class="fade-img" data-label=" 这里是你目前图片阶段的描述-1 ">
    <img src="这里是你的图片文件-1" alt="这里是你的图片文件的-1 alt">
</div>
<div class="fade-img" data-label=" 这里是你目前图片阶段的描述-2 ">
    <img src="这里是你的图片文件-2" alt="这里是你的图片文件的-2 alt">
</div>
<div class="fade-img" data-label=" 这里是你目前图片阶段的描述-3 ">
    <img src="这里是你的图片文件-3" alt="这里是你的图片文件的-3 alt">
</div>
...
<div class="fade-img" data-label=" 这里是你目前图片阶段的描述-n ">
    <img src="这里是你的图片文件-n" alt="这里是你的图片文件的-n alt">
</div>

```

### 模块的颜色

在 ``style.css`` 文件里更改这些代码就可以更改模块的颜色~~和磨砂玻璃的模糊度~~

```
style.css

:root {
    --image-container-bg: #00000033;
    --slider-btn-bg: #0f0f0f;
    --slider-btn-shadow:#0f0f0faa ;
    --slider-bg-top: #151515;
    --slider-bg-bottom: #eee;
    --text-color:#eee;
    --text-box-bg: #0f0f0faa;
    --icon-color:#eee;
    --icon-bg: #0f0f0faa;
    --glass-blur:20px;
}

```

## 都做完了还需要干什么吗？

### 当然是好好享受啦~ (✿◠‿◠)
### 祝你用的开心！( •̀ ω •́ )✧
