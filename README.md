# WFD GitHub Pages

网页入口是 `index.html`，可进入 `reading.html` 移动阅读版或 `dictation.html` 听写训练版。两种模式共用 `data/P1.md` 至 `data/P9.md`。

## 修改音标

1. 打开需要修改的 `data/P*.md`。
2. 找到对应题号，例如 `### P1-04`。
3. 只修改 `<rt>/音标/</rt>` 中的内容。
4. 点击 **Commit changes** 保存。
5. 等待 GitHub Pages 更新后刷新网页。

请保留题号以及 `中文：`、`英文：`、`备注：` 三个字段。阅读版读取 Markdown 失败时会使用内置备用数据；听写版会明确提示缺少哪份题库，方便排错。
