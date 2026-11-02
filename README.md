# Shangyue Jiang — Personal Website

这是一个可直接打开的静态学术网站。页面内容以 Shangyue Jiang 的 Google Sites 为依据，视觉参考 lulinli.com 的白底、深蓝灰色、Georgia 衬线标题、细分隔线和双栏布局。

## 打开网站

直接用 Chrome、Edge 或其他浏览器打开 `index.html`。无需安装依赖或构建。所有页面、照片和 CV 均可在本地使用；访问论文的外部链接需要网络。

也可以在本文件夹内运行 `python -m http.server 4173 --bind 127.0.0.1`，然后访问 http://127.0.0.1:4173 。用 Ctrl+C 关闭服务器。

## 文件

- `index.html`：个人介绍、求职市场信息、照片、研究概览、教育信息。
- `research.html`：求职论文、发表论文、工作论文和研究项目；研究简介可展开。
- `teaching.html`：课程与学期。
- `cv.html`：CV 预览、打开和下载。
- `styles.css`：共享样式、手机布局、打印样式。
- `script.js`：手机导航菜单，包括 Escape 关闭。
- `assets/`：原站照片、原版 CV、CV 首页预览、SVG 网站图标。

修改页面内容可直接编辑相应 HTML。更换 CV 时，请同时更新 `assets/Shangyue_Jiang_CV.pdf` 和 `assets/cv-preview.png`。颜色及字体定义位于 `styles.css` 顶部。

## 内容来源与核对事项

本次整理日期：2026-11-01（America/New_York）。

- 主页：https://sites.google.com/view/shangyuejiang/home
- 研究：https://sites.google.com/view/shangyuejiang/research
- 教学：https://sites.google.com/view/shangyuejiang/teaching
- CV：https://drive.google.com/file/d/1CiuYxdk0u93j5wfjL74NItqYkLj7QrlZ/view
- 风格参考：https://lulinli.com/

原 CV 保持不变。它仍列有 Ph.D. May 2026 (expected) 与 M.S. Dec 2025 (expected) 等预计日期，不能据此确认学位已授予。网站首页采用原站当前的 Ph.D. candidate 和 2026–2027 academic job market 信息，仅列明确可支持的教育条目。教学页面采用网页中较新的 2026 年记录。

原研究页面的 Generalized Leontief 工作论文链接与 CV 链接完全相同，打开的是 CV。因此本网站保留论文标题和研究简介，未设置错误的论文下载按钮。取得正确论文文件后可添加链接。

研究内容为基于原站与 CV 的简短介绍，没有新增论文、奖项、结果或职位。照片、CV 来自上述公开个人网站，未改写 CV。

## 部署

可以把本文件夹整体上传到支持静态网站的托管服务，以本文件夹为发布目录；无需构建命令。所有内部链接均使用相对路径。当前交付为本地文件，没有绑定域名或创建公开站点。
