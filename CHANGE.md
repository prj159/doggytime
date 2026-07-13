- 2026/07/09/20:31
1. 增加 site-title 的动画效果

- 2026/07/13/19:41
1. 首页改用 Grid 布局，支持标题与博客入口卡片分别定位。
2. 增加 h1 的 Grid 定位与 top/left 微调注释。
3. 将首页 p 改为可点击的博客入口卡片，增加圆角边框、可调字体和鼠标悬停文字上下切换动画。
4. 博客入口链接使用 GitHub Pages 子路径 `/doggytime/blog`，确保可正确跳转。

- 2026/07/13/20:59
1. 新增 `AverageSans-Regular.ttf` 及转换后的 `AverageSans-Regular.woff2`，在 Astro 字体配置中注册并预加载 Average Sans。
2. 首页全部 `p` 和页头 `.site-title` 改用 Average Sans，并调整字体大小、粗细、颜色、字距及行距等样式。
3. 首页新增左下说明文本 `.longtext` 和自动显示当前年份的版权信息 `.rights`，使用 Grid 分别定位，并提供宽高、对齐和边距等可调配置。
4. 博客入口文字调整为 `/ BLOG` 和 `/ VISIT`，保留鼠标悬停与键盘聚焦时的文字切换动画，并优化卡片显示样式。
5. 统一整理 `index.astro` 和 `MyHeader.astro` 的中文注释，标明可修改的定位、字体及动画参数。
