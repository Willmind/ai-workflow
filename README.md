# mix_fe_plus AI 工作流演示稿（Slidev）

## 运行

在仓库根目录执行：

```bash
cd slides/ai-workflow-demo
npm i
npm run dev
```

## 导出

```bash
cd slides/ai-workflow-demo
npm run export
```

说明：
- `slidev export` 依赖 Playwright 下载浏览器。若你的网络/权限受限，先只用 `npm run dev` 演示即可。
- 需要导出 PDF 时，建议在非受限网络环境执行：

```bash
cd slides/ai-workflow-demo
npm i -D playwright
npx playwright install chromium
npm run export
```

## 资源放置

- `public/`：截图、录屏（建议）
  - `demo-git-diff-review.mp4`（兜底录屏）
  - `demo-figma-mcp.mp4`（兜底录屏）
  - `toolchain.png`（第 4 页全景图）

