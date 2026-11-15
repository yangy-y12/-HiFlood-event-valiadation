# Event Validation Report

This static report contains validation results for 27 macro-event windows and 173 sub-events, with evidence links, status filters and summary charts.

- `index.html`: English report and website landing page.
- `.nojekyll`: serves the HTML file without Jekyll processing.

All styles, charts, data and scripts needed to display the report are embedded in the HTML file. No installation, build step or external resource folder is required. Evidence links open the original external sources, which may be unavailable independently of this website.

## 发布到 GitHub Pages

1. 新建 GitHub 仓库，例如 `event-validation`。
2. 将本文件夹中的文件上传到仓库根目录，不要再套一层 GitHub 文件夹。
3. 在 Settings → Pages 中选择 Deploy from a branch，分支选择 main，目录选择 / (root)，保存。
4. 等待部署完成，使用 Pages 页面显示的链接访问。英文版报告为首页。

不需要上传原始 Word、历史报告、内部 JSON 或工作脚本。此发布包仅包含当前英文版报告。
