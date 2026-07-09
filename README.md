# Astro 博客起步模板

```sh
npm create astro@latest -- --template blog
```

> 🧑‍🚀 **老宇航员？** 删掉这个文件，玩得开心！

特性：

- ✅ 极简样式（随你定制！）
- ✅ 100/100 Lighthouse 性能评分
- ✅ SEO 友好，支持 canonical URL 和 Open Graph
- ✅ 站点地图支持
- ✅ RSS 订阅支持
- ✅ Markdown & MDX 支持

## 🚀 项目结构

Astro 项目中，你会看到以下目录和文件：

```text
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro 会在 `src/pages/` 目录中查找 `.astro` 或 `.md` 文件，每个页面根据其文件名暴露为对应的路由。

`src/components/` 没什么特别的，只是我们习惯把 Astro/React/Vue/Svelte/Preact 组件放在这里。

`src/content/` 目录存放相关的 Markdown 和 MDX 文档"集合"。使用 `getCollection()` 从 `src/content/blog/` 中获取文章，并通过可选的 schema 对 frontmatter 进行类型检查。详见 [Astro 内容集合文档](https://docs.astro.build/en/guides/content-collections/)。

图片等静态资源可以放在 `public/` 目录中。

## 🧞 命令

所有命令都在项目根目录下的终端中运行：

| 命令                       | 操作                                      |
| :------------------------- | :---------------------------------------- |
| `npm install`              | 安装依赖                                  |
| `npm run dev`              | 启动本地开发服务器，地址 `localhost:4321` |
| `npm run build`            | 构建生产站点到 `./dist/`                  |
| `npm run preview`          | 部署前本地预览构建结果                    |
| `npm run astro ...`        | 运行 CLI 命令，如 `astro add`、`astro check` |
| `npm run astro -- --help`  | 获取 Astro CLI 使用帮助                   |
| `.\node_modules\.bin\astro.cmd dev stop` | 停止Astro |

## 👀 想了解更多？

查看[官方文档](https://docs.astro.build)或加入我们的 [Discord 服务器](https://astro.build/chat)。

## 致谢

本主题基于可爱的 [Bear Blog](https://github.com/HermanMartinus/bearblog/)。
