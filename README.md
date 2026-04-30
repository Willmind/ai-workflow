# mix_fe_plus AI 工作流演示稿

这是一个基于 [Slidev](https://sli.dev/) 的分享演示稿，用于介绍 `mix_fe_plus` 项目里的 AI 工作流实践。

分享重点不是单个工具的使用技巧，而是把「需求澄清 -> 计划 -> 规范沉淀 -> 编码 -> 审查 -> 提交」整理成一套可重复、可审计、可复用的协作流程。

## 内容概览

演示稿覆盖以下主题：

- 背景：效率瓶颈通常来自需求理解、上下文切换和收尾漏项
- superpowers：把探索、计划、验证结构化
- OpenSpec：沉淀需求、接口和边界条件
- Project Rules：让项目规范成为 AI 的默认行为
- Cursor / Codex：同一套方法在不同 AI 编程工具中的复用
- AI Review：基于 diff 的结构化审查
- AI Commit：自动化提交信息与收尾动作
- Figma MCP：把设计上下文接入实现流程
- Token 控制：减少无关上下文，而不是简单少说话

## 项目结构

```text
.
├── README.md
├── package.json
├── package-lock.json
├── slides.md
├── styles.css
└── public/
    ├── openspec.png
    ├── openspec.svg
    ├── superpowers-first-output.svg
    ├── superpowers.png
    ├── toolchain.png
    └── toolchain.svg
```

## 本地运行

安装依赖：

```bash
npm install
```

启动演示：

```bash
npm run dev
```

默认会打开 Slidev 本地预览页面。

## 构建

```bash
npm run build
```

构建产物会输出到 `dist/`，该目录已被 `.gitignore` 忽略。

## Vercel 部署

项目已提供 `vercel.json`，用于固定 Vercel 的构建配置：

- Build Command：`npm run build`
- Output Directory：`dist`
- Rewrites：所有路由回退到 `/index.html`

如果在 Vercel 控制台手动配置，也需要保持以上设置一致。否则可能出现部署成功但访问页面 404 的情况。

## 导出

```bash
npm run export
```

说明：

- `slidev export` 依赖 Playwright 浏览器环境。
- 如果当前网络或权限受限，可以先使用 `npm run dev` 进行现场演示。
- 需要导出 PDF 时，建议在网络可用的环境中安装 Playwright 浏览器：

```bash
npm install -D playwright
npx playwright install chromium
npm run export
```

## 资源说明

静态资源放在 `public/` 下，可在 `slides.md` 中通过根路径引用，例如：

```md
![toolchain](/toolchain.svg)
```

当前主要资源：

- `toolchain.svg` / `toolchain.png`：AI 工具链全景图
- `superpowers.png`：superpowers 相关示意图
- `superpowers-first-output.svg`：superpowers 第一轮产出示意
- `openspec.svg` / `openspec.png`：OpenSpec 相关示意图

## 常用脚本

| 命令 | 说明 |
| --- | --- |
| `npm run dev` | 启动 Slidev 预览 |
| `npm run build` | 构建静态站点 |
| `npm run export` | 导出演示稿 |

## 维护建议

- 更新演示内容优先修改 `slides.md`。
- 更新视觉样式优先修改 `styles.css`。
- 新增图片、截图或录屏放入 `public/`。
- 不提交 `dist/`、`node_modules/`、`.DS_Store` 等本地生成内容。
