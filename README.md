# DeepInfer 交互式技术报告

在线阅读：https://pharmaron-ai.github.io/deepinfer-illustration/

从模型生成的完整流程出发，介绍 Prefill/Decode、Attention、KV Cache、FlashMLA、专家并行、推测解码、SWA Bounded Replay 与结构化输出。

- 30 页可翻页 HTML，包含交互演示与动画。
- 页面右上角“全文 / 来源”保留完整技术调研报告和 61 个参考来源。
- 支持方向键、PageUp / PageDown 翻页，以及目录跳转。
- 图中构造的向量和演示数值用于教学，不是 DeepInfer 性能实测。
- 所有脚本、样式和图片都包含在 `index.html` 内。

## GitHub Pages

在仓库 Settings → Pages 中选择 **Deploy from a branch**，分支为 **main**，目录为 **/ (root)**。`.nojekyll` 让 Pages 直接提供静态文件。

之后更新 `index.html` 并提交，网站会随之更新。
