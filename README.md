# IAT × PhysicsAI：汽车智能仿真四项研究提案

公开项目页：`https://made-gpt.github.io/IAT-PhysicsAI-ProjectPage/`

本仓库整理四项汽车 CFD/CAE 研究概念：风噪分析、除霜仿真、吹面/吹足和整车热害。每项包括离线交互 Demo、六页研究提案（前两页主文与四页技术附录）、矢量流程图和可编辑 Markdown。

## 重要边界

- 交互页面使用确定性合成公式，未接入真实 CAD、商业 CFD 求解器或训练后模型。
- 提案里的架构、数据预算、时间线、验收门槛和成本模型均为待验证研究设计。
- 工程结论必须通过原求解器、试验或两者的独立复核；页面不能用于设计、合规或安全批准。
- 参考图来自 DrivAerNet 公开论文 Fig. 6，仅用于说明工业 CFD 场表达；DynaSolver 作为方法对照；其本地稿件和原图未上传。许可与裁剪说明见 [ATTRIBUTION.md](ATTRIBUTION.md)。

## 目录

- `index.html`：项目首页与四项研究导航
- `demos/`：四个离线交互页面
- `pdf/`：四份提案 PDF 与可编辑 Markdown
- `assets/`：四份流程图（PDF/PNG）及公开 CFD 参考图
- `verification-v2.json`：交付检查记录

## 本地预览

可直接打开 `index.html`，或使用任意静态 HTTP 服务器提供仓库根目录。

## 参考

- [DynaSolver Project Page](https://github.com/Made-Gpt/DynaSolver-ProjectPage)
- [DrivAerNet](https://arxiv.org/abs/2403.08055)
- [Transolver](https://arxiv.org/abs/2402.02366)
- [Foam-Agent](https://arxiv.org/abs/2505.04997)

