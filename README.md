# 闵雨涵｜运营作品集网站

## 文件结构

- `index.html`：网页主体
- `style.css`：样式文件
- `script.js`：交互动效
- `assets/Yuhan_Min_Resume.pdf`：简历

## 上传 GitHub Pages

1. 解压本压缩包。
2. 将解压后的所有文件上传至 GitHub 仓库根目录。
3. 进入仓库 `Settings` → `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/(root)`。
6. 保存后等待 1–5 分钟。

## 替换头像

当前使用 “YM” 字母头像占位。若要换真人照片：

1. 把照片命名为 `avatar.jpg`，放入 `assets` 文件夹。
2. 打开 `index.html`。
3. 将：
   `<div class="portrait-placeholder"><span>YM</span></div>`
   替换为：
   `<img class="portrait-placeholder" src="assets/avatar.jpg" alt="闵雨涵头像">`

## 修改联系方式

在 `index.html` 搜索：
- `1091319281@qq.com`
- `15851566196`

直接替换即可。
