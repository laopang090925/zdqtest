# zdqtest
简介
ZDQ Prompt Studio 是一款面向 B 端产品经理的 AI 提示词生成工具，帮助你快速、结构化地构建高质量的高保真原型生成指令。
传统的 Prompt 写作依赖个人经验，输出质量参差不齐。ZDQ Prompt Studio 将原型设计中的核心变量——AI 角色、工具选型、端类型、功能需求、设计风格——抽象为可交互的配置面板，最终生成一份可直接投喂给 Claude、Cursor、Figma Make 等 AI 工具的结构化 Prompt，大幅降低"提示词质量"对原型输出的干扰。

核心功能
🎭 AI 角色定义
选择或自定义 AI 在本次设计中的专业身份，影响输出的视角与侧重点：

资深 UI 设计师
全栈前端工程师
B 端产品设计专家
交互体验设计师
自定义角色

🛠️ AI 工具选择
根据目标工具的特性自动调整 Prompt 结构：
工具适用场景Claude单文件 HTML，可直接在浏览器运行或粘贴到 Artifacts 预览Cursor多文件项目结构，适合工程化场景Figma Make可编辑组件与布局，适合设计协作场景
📱 端类型适配
一键切换目标平台，自动注入对应平台的设计规范预设：

管理后台（PC 端 Web）
小程序（微信 WeChat，375px，底部 TabBar）
移动 App（iOS / Android）
H5（移动端网页 / 可嵌入）

📋 页面信息填写

页面名称：明确设计对象
目标用户：限定受众，引导 AI 做出合理的信息架构决策
核心功能需求：逐条描述功能点，结构化输入保障输出精度

🎨 设计风格配置

视觉风格 & 主色调（最多各选 2 项，可折叠）
UI 组件：按需勾选，可折叠
设计风格描述：用自然语言补充期望的视觉细节，AI 据此调整表现

🖼️ 上传参考截图
支持上传最多 8 张参考图片（JPG / PNG / WebP），作为设计风格参考注入 Prompt。
⚡ 交互说明
描述特殊交互、动效要求、状态说明及已有设计规范等，确保 AI 输出符合实际交互预期。
🤖 智能解析（自动填写）
粘贴已有 Prompt，系统自动解析并回填各配置项，支持对存量 Prompt 的结构化迭代。
📤 输出方式

生成 Prompt：一键输出完整结构化提示词，可直接复制使用
导出 .MD：将配置与 Prompt 导出为 Markdown 文件，便于存档与团队共享


使用场景

产品经理独立产出高保真原型，无需设计师介入
快速验证页面方案，缩短需求→原型的交付周期
统一团队 Prompt 规范，减少 AI 输出的随机性
管理和复用历史 Prompt 资产


技术栈

纯前端实现（HTML + CSS + JavaScript），无需后端
零依赖，可直接在浏览器运行或嵌入 Claude Artifacts 预览


快速开始
bash# 克隆项目
git clone https://github.com/laopang090925/zdqtest.git

# 直接用浏览器打开
open index.html
或将 index.html 粘贴到 Claude Artifacts 中直接预览。

贡献
欢迎提交 Issue 和 PR。如果这个工具对你有帮助，欢迎 Star ⭐


Overview
ZDQ Prompt Studio is an AI prompt generation tool designed specifically for B2B product managers. It helps you quickly build structured, high-quality prompts for generating high-fidelity UI prototypes with AI.
Traditional prompt writing relies heavily on personal experience, resulting in inconsistent output quality. ZDQ Prompt Studio abstracts the core variables of prototype design — AI role, tool selection, platform type, functional requirements, and design style — into an interactive configuration panel. The result is a structured prompt ready to feed directly into Claude, Cursor, Figma Make, and other AI tools, significantly reducing the impact of "prompt quality" on prototype output.

Features
🎭 AI Role Definition
Select or customize the AI's professional identity for the current design session, influencing the output's perspective and focus:

Senior UI Designer
Full-stack Frontend Engineer
B2B Product Design Expert
UX / Interaction Designer
Custom role

🛠️ AI Tool Selection
Automatically adjusts the prompt structure based on the characteristics of the target tool:
ToolBest ForClaudeSingle-file HTML, runs directly in browser or Claude ArtifactsCursorMulti-file project structure, ideal for engineering workflowsFigma MakeEditable components and layouts, ideal for design collaboration
📱 Platform Targeting
Switch target platforms with one click — design presets for each platform are automatically injected:

Admin Dashboard (PC Web)
Mini Program (WeChat, 375px, bottom TabBar)
Mobile App (iOS / Android)
H5 (Mobile Web / Embeddable)

📋 Page Information

Page Name: Define the design subject clearly
Target Users: Constrain the audience to guide better IA decisions
Core Functional Requirements: List feature points line by line for structured, precise output

🎨 Design Style Configuration

Visual Style & Color Palette (up to 2 each, collapsible)
UI Components: Select as needed, collapsible
Design Style Description: Add natural language details; the AI adjusts visual expression accordingly

🖼️ Reference Screenshots
Upload up to 8 reference images (JPG / PNG / WebP) to inject visual style references into the prompt.
⚡ Interaction Notes
Describe special interactions, animation requirements, state logic, and existing design system constraints — ensuring AI output aligns with real interaction expectations.
🤖 Smart Parsing (Auto-fill)
Paste an existing prompt and the system automatically parses and backfills all configuration fields, enabling structured iteration on legacy prompts.
📤 Output Options

Generate Prompt: One-click output of the complete structured prompt, ready to copy and use
Export .MD: Export the full configuration and prompt as a Markdown file for archiving or team sharing


Use Cases

Product managers independently producing high-fidelity prototypes without designer involvement
Rapidly validating page concepts to shorten the requirements → prototype delivery cycle
Standardizing team prompt conventions to reduce AI output variance
Managing and reusing a library of historical prompt assets


Tech Stack

Pure frontend (HTML + CSS + JavaScript) — no backend required
Zero dependencies — runs directly in a browser or embedded in Claude Artifacts


Getting Started
bash# Clone the repo
git clone https://github.com/laopang090925/zdqtest.git

# Open directly in browser
open index.html
Or paste index.html into Claude Artifacts for instant preview.

Contributing
Issues and PRs are welcome. If this tool is useful to you, feel free to give it a Star ⭐

Built for B2B PMs who move fast and prototype alone.
