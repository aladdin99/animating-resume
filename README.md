# 一个会动的简历模板

> This is my resume

[预览](https://aladdin99.github.io/animating-resume/public/)

## 使用方法

``` bash
git clone git@github.com:jirengu-inc/animating-resume.git
cd animating-resume
npm install
npm run dev
```

## 部署方法


1. 编辑 config/index.js，修改第 10 行的 assetsPublicPath，值为 `项目名/dist`。如果你没有修改项目名 animating-resume，则可跳过此步骤。

2. 编译、上传
    ``` bash
    npm run build
    git add .
    git commit -m "update"
    git push
    ```

3. 开启 GitHub Pages 功能
    ``` bash
    在当前项目下打开 settings
    下拉找到 GitHub Pages
    在 Source 项中选择 master branch
    然后生成一个地址，该地址+'/public' 就是预览该项目页面的网址
    ```

