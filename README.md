# Pluggable UI Designer Showcase (开源前端模板市场与提示词中心)

> **告别同质化 AI Slop · 基于“通用审美底座 + 细节点积木式插拔（Slot Mixins）”的前端交互原型市场与 AI 提示词工坊。**

[![Spec v1.0 Compliant](https://img.shields.io/badge/Spec-v1.0-blue.svg)](https://github.com/Ikaros-521/pluggable-skills)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Zero-Config HTML](https://img.shields.io/badge/Delivery-Single--File%20HTML-orange.svg)]()
[![Prompt Cookbook](https://img.shields.io/badge/Cookbook-20%20Recipes-indigo.svg)](06_design_system_cookbook.html)

[English Documentation (README_EN.md)](README_EN.md) | [主规范核心技能库 (pluggable-ui-designer)](https://github.com/Ikaros-521/pluggable-ui-designer)

---

## 💡 为什么需要本项目？

### 传统 AI 生成前端原型的痛点
1. **千篇一律的 "AI Slop" 审美同质化**：纯白底 + 突兀的紫色粉色渐变 + 毫无节制的泡泡大圆角，缺乏真实工业级设计系统的约束。
2. **难以精准复刻与微调**：往往改一个阴影或换个配色，传统单体 Prompt 就会引发整体布局雪崩。

### 我们的解决方案：模板市场 + 积木配方库
* **开箱即用的模板市场 (`index.html`)**：提供 4 款涵盖 DevTools、知识库、云监控、创作者的多业务产品级原型，开箱即览。
* **一键复制 AI 提示词 (Copy Prompt)**：每个模板均提炼出专属的 Prompt 配方，点击直接复制给任何大模型（Claude、GPT-4o、Gemini 等）秒级复刻同款产品。
* **20 款主流效果工坊 (`06_design_system_cookbook.html`)**：收录 Linear 聚光灯、Apple VisionOS 毛玻璃、Magic UI 流动边框、动态岛导航、Cmd+K 面板等 20 个大厂高频效果，单点提取提示词与代码。

---

## 🛒 核心模板一览 (Showcase Matrix)

| 编号 | 模板名称 | 业务场景定位 | 挂载细节点插件 (Slot Mixins) | 在线原型文件 |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **Chronos Review** | AI 智能代码审查与漏洞巡检工作台 | • `elevation`: `fine_hairline` (精工发丝线)<br>• `layout`: `dock` (左侧紧凑导航栏)<br>• `palette`: `cold_slate` (冷调工业灰)<br>• `interaction`: `subtle_glow` (呼吸脉冲) | [`01_chronos_review.html`](01_chronos_review.html) |
| **02** | **Aether Garden** | 思考花园与灵感知识空间 | • `elevation`: `soft_diffusion` (柔和轻弥散)<br>• `layout`: `bento_grid` (错落便签网格)<br>• `palette`: `warm_stone` (人文暖石纸质底)<br>• `interaction`: `tactile_bounce` (弹性触感) | [`02_aether_garden.html`](02_aether_garden.html) |
| **03** | **PulseOps Edge** | 边缘云节点与实时吞吐监控大盘 | • `elevation`: `flat_zen` (功能纯扁平零阴影)<br>• `layout`: 响应式高密网格 + 遥测表<br>• `palette`: 极简中性黑白 + 翡翠绿点睛<br>• `interaction`: `tactile_bounce` | [`03_pulseops_edge.html`](03_pulseops_edge.html) |
| **04** | **Lumina Studio** | 多维创作者灵感与内容工作台 | • `elevation`: `soft_diffusion` (轻盈悬浮)<br>• `layout`: `bento_grid` (便签模块流)<br>• `palette`: `multi_accent_pastel` (5重低饱和多维色彩系统)<br>• `interaction`: `tactile_bounce` | [`04_lumina_studio.html`](04_lumina_studio.html) |

---

## 🔬 前沿实验室与设计工坊

### 1. 微交互实验室 (`05_spotlight_and_glassmorphism.html`)
* **指针跟随流光聚光灯 (Spotlight Border)**：通过 `mask-composite: exclude` 遮罩与原生坐标跟踪，在鼠标附近 350px 扇区实时点亮 1px 光纤发丝边框与表面漫反射。
* **VisionOS 液态高斯毛玻璃 (Frosted Glassmorphism)**：底层衬托多颗低速呼吸起伏的多色 Mesh Glow Orbs 环境漫反射光球，呈现逼真的物理折射与晶体切身高光边缘。

### 2. 20 款主流效果与组件 AI 提示词工坊 (`06_design_system_cookbook.html`)
收录 20 个开箱即用的细节点配方，每个均支持 **「复制 AI 提示词」** 与 **「复制代码」**：
1. **精工发丝线与顶部微高光** (Linear 风格)
2. **柔和双层大弥散轻投影** (Apple / Stripe 风格)
3. **素雅功能纯扁平** (零阴影高信噪比)
4. **VisionOS 液态环境毛玻璃** (双层高斯模糊 20px+)
5. **炫彩渐变旋转流动边框** (Magic UI 流光光纤)
6. **极客渐变微点阵网格背景** (SaaS 工业底纹)
7. **磨砂胶片微噪点质感** (消除数字塑料感)
8. **指针跟随流光聚光灯描边** (动态计算坐标 1px 跟随)
9. **3D 悬浮透视鼠标跟随倾斜** (立体景深倾角)
10. **物理按压弹性微凹陷** (机械回弹按键触感)
11. **流光呼吸渐变标题字体** (Apple Intelligence 光带扫过)
12. **双层状态脉冲发光环** (实时探活与在线涟漪)
13. **悬浮毛玻璃胶囊动态岛导航** (居中悬浮药丸 Navbar)
14. **Cmd+K 极客快捷全局命令面板** (Raycast 搜索弹窗)
15. **等宽指标与数据微趋势卡** (tabular-nums 对齐与微条形柱)
16. **代码审查 Diff 差异对比行** (红绿半透明高亮与行号对齐)
17. **无缝微过渡手风琴折叠卡** (展开收起与图标平滑旋转)
18. **悬浮磨砂状态反馈浮窗** (Toast 状态通知)
19. **多色相微粉彩标签体系** (紫/绿/橙/蓝 WCAG AA 4.5:1 低饱和系统)
20. **Bento Grid 错落智能模块网格** (主角卡跨列跨行便签流)

---

## 🚀 如何使用？

### 方式 1：本地即开即用
所有页面均为 **Zero-Config 单文件自包含 HTML**，头部已内置 Tailwind CSS CDN 与 Lucide 图标库。
无需安装 Node.js、npm 或任何打包工具，直接在本地双击任意 `.html` 文件即可在现代浏览器中查看！

### 方式 2：一键部署为 GitHub Pages 静态网站
1. Fork 本仓库并进入仓库设置（`Settings` -> `Pages`）；
2. Source 选择 `Deploy from a branch`，Branch 选择 `main` / `/(root)` 并保存；
3. 即可免费获得一个属于您自己的在线前端模板市场！

### 方式 3：结合 AI Agent 迁移与复刻
在浏览模板或工坊时，点击卡片上的 **`[复制 Prompt]`** 按钮，直接将提示词黏贴给 AI，告诉它：“*请为我的 [输入您的项目名称] 应用该设计风格*”，AI 即可快速输出同款高颜值界面。

---

## 📂 仓库目录结构

```text
ui-designer-showcase/
├── index.html                           # 🛒 开源模板市场门户主页（分类筛选 + 一键复制 Prompt）
├── 01_chronos_review.html               # 🛠️ 模板 01：AI 代码审查与漏洞巡检大盘（极客暗黑发丝线）
├── 02_aether_garden.html                # 📖 模板 02：思考花园与灵感空间（人文暖石纸质 + Bento）
├── 03_pulseops_edge.html                # ⚡ 模板 03：边缘节点监控大盘（素雅纯扁平 + 高密数据流）
├── 04_lumina_studio.html                # 🎨 模板 04：多维创作者工作台（保留简约 + 5重微粉彩系统）
├── 05_spotlight_and_glassmorphism.html  # 🔬 实验室：鼠标跟随流光聚光灯与 VisionOS 液态毛玻璃
├── 06_design_system_cookbook.html       # 📚 配方库：20款主流效果与组件 AI 提示词工坊
├── LICENSE                              # MIT 开源协议
├── README.md                            # 中文说明文档
├── README_EN.md                         # 英文说明文档
└── .gitignore                           # 忽略文件
```

---

## 📄 开源许可

本项目遵循 [MIT License](LICENSE) 开源协议。欢迎 Fork、Star 并提交新的优质细节点模板！
