# xing-cong.github.io

这是个人网站的源码仓库，基于 Next.js、Tailwind CSS 和 TypeScript 构建，并通过静态导出部署到 GitHub Pages。

## 常用命令

```bash
npm install
npm run dev
npm run build
```

`npm run dev` 用于本地预览，默认地址为 `http://localhost:3000`。`npm run build` 会生成静态站点文件到 `out/` 目录。

## 内容结构

- `content/`：默认语言内容，包括站点配置、主页、论文、简历、教学、奖项和服务等。
- `content_zh/`：中文内容，与 `content/` 保持同名文件结构。
- `public/`：公开静态资源，例如头像、favicon 和论文图片。
- `src/`：网站源码，包括页面、组件、内容加载和多语言逻辑。

## 部署

仓库保留了 GitHub Pages 自动部署工作流：`.github/workflows/deploy.yml`。推送到 `main` 或 `ci` 分支后，GitHub Actions 会安装依赖、构建站点，并将 `out/` 发布到 GitHub Pages。

## 致谢

本网站基于开源项目 [PRISM](https://github.com/xyjoey/PRISM) 修改而来，感谢原项目提供的基础模板与实现。
