# Runtong Wu — personal academic homepage

适用于 GitHub Pages 的静态主页，无依赖，无需安装或构建。

## 本地查看

双击 `index.html` 即可预览。也可以在此文件夹运行 `python -m http.server 8000`，然后打开 `http://localhost:8000`。

## 发布到 GitHub Pages

1. 登录 GitHub 账号 `Rts-Wu`，创建名为 `Rts-Wu.github.io` 的 **Public** 仓库；如果已有该仓库，请先检查已有内容。
2. 上传本文件夹中的文件及 `assets` 文件夹，使 `index.html` 位于仓库根目录。不要把外层 `runtong-wu-homepage` 文件夹一起作为一层上传。
3. 在仓库 **Settings → Pages → Build and deployment** 中，选择 **Deploy from a branch**，分支选择 `main`，目录选择 `/ (root)`，保存。
4. 等待 GitHub 完成发布，主页地址为 `https://rts-wu.github.io/`。

GitHub Free 支持通过公开仓库使用 Pages。默认 github.io 地址无需购买域名或服务器。

## 修改内容

- `index.html`：介绍、论文、状态、链接和经历。
- `styles.css`：配色和适配不同屏幕的布局。
- `assets/Resume_Runtong_Wu.docx`：原始简历的副本，提供下载。以后可换为 PDF 并同步修改网页链接。
- `.nojekyll`：让 Pages 直接提供静态文件。

页面事实来自用户提供的简历；未补写未提供的学历、录用、代码仓库或奖项。两篇在投论文统一标记为 `Under review`，不显示目标会议或期刊。未列出准备中工作的目标会议。

## 图片来源

- `assets/runtong-wu.jpg`：用户提供的个人照片副本，原始文件保持不变。
- `assets/piano-tennis.svg`：兴趣爱好区的钢琴与网球矢量插图。
- `assets/omniact3d-figure1.png`：从 [OmniAct3D 的 arXiv PDF](https://arxiv.org/pdf/2610.03015) 第 1 页截取的 Figure 1，展示单目、多视角与全景 3D 检测范式。
- `assets/narratives-figure1.png`：从 [Visually Grounded Narratives 的 arXiv PDF](https://arxiv.org/pdf/2509.00381) 第 1 页截取的 Figure 1，展示文本到故事图像的流程以及 member checking 对比。

配图按原始比例显示，可点击打开大图。两张截图均保留原图内容，来源记录在上方，网页通过论文标题和 Paper 链接提供原文入口。DDQN 条目没有新增配图。

当前版本为本地初稿，尚未创建远程仓库或发布。CV 原件包含联系电话，公开部署后下载者可见；如果需要精简公开简历，可替换该文件。
