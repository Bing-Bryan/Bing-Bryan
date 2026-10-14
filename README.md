<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/github-header-dark.gif">
  <source media="(prefers-color-scheme: light)" srcset="assets/github-header-light.gif">
  <img src="assets/github-header-light.gif" alt="Hi, I'm Bing 👋 — 把 AI 放进具体场景，让工具更好用。" width="960">
</picture>

我在做 AI 阅读工具，也把日常使用 Agent 时遇到的问题，做成可复用的 Skills 和小工具。这里记录我的产品实验与实现。

Building AI reading tools, reusable agent skills, and small improvements to everyday workflows.

## 产品实践 · Got it

### [Got it · 读到不懂的地方，就在原文旁弄明白](https://github.com/Bing-Bryan/Got-it)

阅读时，查一个概念常常意味着离开原文、切换工具，再找回刚才读到的位置。Got it 把解释、来源查找和提问留在原文旁，让阅读可以继续。

[![Got it：原文、目录和知识贴并排显示](https://raw.githubusercontent.com/Bing-Bryan/Got-it/main/docs/images/reading.png)](https://github.com/Bing-Bryan/Got-it)

- **材料放在一起：** Markdown、PDF 和网页文章共用一个本地阅读库。
- **围绕原文理解：** 选中文字或 PDF 区域，解释概念、查找来源、提出问题。
- **留下阅读积累：** 知识贴、译文和进度保存在本机，方便继续和回看。

目前是早期试用版，需要已安装并登录的 Codex；已验证 macOS Apple Silicon。本地保存，AI 功能需要联网。

[查看项目与安装说明 →](https://github.com/Bing-Bryan/Got-it#快速开始)

### 这个项目里的产品取舍

| 选择 | 对用户的意义与代价 |
| --- | --- |
| 在原文旁解释与提问 | 保留阅读上下文；围绕选区回答，也需要明确上下文覆盖范围。 |
| 本地保存阅读材料与积累 | 不改写原文件，方便回看；当前没有云同步或多人协作。 |
| 区分“找到来源”和“主张得到支持” | 让用户看见证据边界，避免把有链接的回答直接当成事实。 |

**当前验证边界：** 已有可试用版本、界面示例和发布检查记录；这些能说明实现与功能检查，尚不能证明学习效果或用户留存提升。

[查看发布验证记录](https://github.com/Bing-Bryan/Got-it/blob/main/docs/release-results.md)

## 工具与工作流实践

| 项目 | 解决的问题 |
| --- | --- |
| [Skills by Bing](https://github.com/Bing-Bryan/skills-by-bing) | 把重复的 Agent 工作整理成可复用技能：批量生图、Skill 发布检查、闲鱼发布流程。 |
| [Codex External Subagent Runtime](https://github.com/Bing-Bryan/codex-external-subagent-runtime) | 为 Codex 的多 Agent 与 Skill/MCP 路由增加明确规则，并在调用前检查配置与验证记录。 |
| [DSH Unread Dot](https://github.com/Bing-Bryan/dsh-unread-dot) | 离开 DSH 窗口后，用 macOS Dock 角标和提示音区分“还在运行”与“结果待看”。 |
| [手势交互 3D 实验](https://github.com/Bing-Bryan/Vision-pro-Gemini-) | 用摄像头识别手势，探索旋转和缩放 3D 球体的交互。 |

## 交流与合作

希望围绕 AI 产品岗位和项目合作交流，尤其是 AI 阅读、知识工具和 Agent 工作流。欢迎通过下方社交主页联系我。

产品使用问题与反馈，请留在对应项目的 Issues，方便结合具体场景讨论。

[X / Twitter](https://x.com/Bing_Bryan_BRN) · [小红书](https://www.xiaohongshu.com/user/profile/5dc82d29000000000100a6d8)
