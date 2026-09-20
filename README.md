# 芙兰朵露 · 桌面伙伴

基于东方 Project 角色芙兰朵露的同人桌面宠物，配有角色主图、九组动画和十六个目光方向。图像素材使用内置 imagegen 生成。

<img src="./idle.gif" alt="芙兰朵露待机动画" width="192" height="208">

[下载桌面宠物皮肤](./flandre-pet.zip) · [查看主图](./flandre-main.png)

## 试玩

开启 GitHub Pages 后，打开仓库发布的网页，可以切换动作、深浅背景，并体验目光跟随鼠标。

也可以下载整个项目，解压后直接用浏览器打开 `index.html`；请保留各文件的位置关系。

## 桌面安装

1. 下载并解压 `flandre-pet.zip`。
2. 将其中的 `flandre-scarlet` 文件夹放到用户目录下的 `.codex/pets/`。
3. 在支持自定义宠物的桌面应用中打开 **设置 → 宠物 → 刷新**，选择 **芙兰朵露**。
4. 输入 `/pet` 显示或隐藏宠物。

[官方宠物说明](https://learn.chatgpt.com/docs/pets)

## 动作

待机眨眼、向右移动、向左移动、挥手、跳跃、沮丧、等待、思考和查看；另外包含十六个方向的目光。

## GitHub Pages

上传这些文件后，在仓库 **Settings → Pages** 中选择：

- Source：**Deploy from a branch**
- Branch：仓库的默认分支
- Folder：**/(root)**

保存后，GitHub 会提供网页地址。此项目是静态网页，无需安装依赖或填写 API 密钥。

[GitHub Pages 发布说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 在个人主页展示动画

将 `idle.gif` 一并放入你的个人主页仓库，在现有 README 中添加以下内容：

```markdown
![芙兰朵露桌面宠物](./idle.gif)
```

支持个人主页 README 的账号，可以使用与用户名同名的公开仓库显示该 README。[GitHub 个人主页说明](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)

## 文件

| 文件 | 用途 |
| --- | --- |
| `index.html` | 可交互的网页预览 |
| `flandre-pet.zip` | 桌面皮肤下载包 |
| `flandre-pet/pet.json` | 宠物配置 |
| `flandre-pet/spritesheet.webp` | 透明动画图集 |
| `idle.gif` / `waving.gif` | 动画展示 |
| `flandre-main.png` | 角色主图 |

图集使用 v2 桌面宠物格式：1536 × 2288 像素、8 列 × 11 行，单帧 192 × 208 像素。
