# Awesome Xiaohongshu Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/1sh1ro/awesome-xiaohongshu-skills?style=flat-square)](https://github.com/1sh1ro/awesome-xiaohongshu-skills/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/1sh1ro/awesome-xiaohongshu-skills?style=flat-square)](https://github.com/1sh1ro/awesome-xiaohongshu-skills/commits/main)

**A curated list of Agent Skills, CLIs, MCP servers, and content tools for Xiaohongshu / RED / RedNote.**

作为一个小红书内容创作者，总是想用办法美化内容，但是一下子又找不到好的 Skills，要一个个试。

所以这里收录了一部分高星、实用、和小红书内容创作相关的 Skills 与工具：从选题研究、爆款拆解，到标题正文、图文卡片、封面设计，再到发布前检查和账号运营。欢迎提 Issue 推荐你正在使用的项目。

截至 2026-08-02，首版精选目录已扩展到 43 个项目。

> **English keywords:** awesome Xiaohongshu skills, awesome RedNote skills, Agent Skills for Xiaohongshu, Claude Code Xiaohongshu, Codex Xiaohongshu, OpenClaw Xiaohongshu, Xiaohongshu carousel cards, social card generator, RedNote content creation, Xiaohongshu MCP.

## Why this list

小红书相关项目很容易混在一起：有的负责内容创作，有的负责图片渲染，有的负责抓取研究，还有的会直接操作真实账号。

这个列表按能力拆开，尽量让你先找到适合自己的工具，而不是把“自动发布”误当成“内容创作”。项目的 Star、更新时间和平台兼容性都会变化；收录不代表安全、稳定、合规或商业授权背书。

## Start here

| 你想做什么 | 推荐先看 |
| --- | --- |
| 文章 → 小红书多图卡片 | [Guizang Social Card Skill](https://github.com/op7418/guizang-social-card-skill)、[BLCaptain Style Skill](https://github.com/dososo/blcaptain-style-skill)、[baoyu-skills](https://github.com/JimLiu/baoyu-skills) |
| 链接 / Markdown → 卡片 + 配套文案 | [XHS-link-to-card-pipeline](https://github.com/leefrane-creator/XHS-link-to-card-pipeline)、[xiaohongshu-article-cards](https://github.com/qianjiazheng2023/xiaohongshu-article-cards) |
| 搜索、阅读和拆解笔记 | [redbook](https://github.com/lucasygu/redbook)、[xhs-cli](https://github.com/jackwener/xhs-cli)、[xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill) |
| 发布前检查 | [media-publish-check](https://github.com/XshuiAi/media-publish-check) |
| 自动发布、评论和账号运营 | 先阅读下方的风险说明，再看 [XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) 或 [xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills) |

## Featured projects

这些项目在 GitHub 上相对活跃或关注度较高，但 Star 数不是质量保证。高星项目可先作为入口，具体仍请阅读源码、许可证和权限说明。

- [op7418/guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) [![Stars](https://img.shields.io/github/stars/op7418/guizang-social-card-skill?style=flat-square)](https://github.com/op7418/guizang-social-card-skill/stargazers) — Codex / Claude Skill；小红书轮播图和公众号封面，单文件 HTML → PNG，包含多套版式与主题。
- [JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) [![Stars](https://img.shields.io/github/stars/JimLiu/baoyu-skills?style=flat-square)](https://github.com/JimLiu/baoyu-skills/stargazers) — `baoyu-xhs-images` 将内容拆成 1–10 张小红书图文卡片，支持 Style × Layout。
- [white0dew/XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) [![Stars](https://img.shields.io/github/stars/white0dew/XiaohongshuSkills?style=flat-square)](https://github.com/white0dew/XiaohongshuSkills/stargazers) — 搜索、详情读取、发布、评论、点赞、收藏和数据看板，偏真实账号运营。
- [Xiangyu-CAS/xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) [![Stars](https://img.shields.io/github/stars/Xiangyu-CAS/xiaohongshu-ops-skill?style=flat-square)](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill/stargazers) — 小红书定位、选题、创作、复盘和运营助手。
- [autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills) [![Stars](https://img.shields.io/github/stars/autoclaw-cc/xiaohongshu-skills?style=flat-square)](https://github.com/autoclaw-cc/xiaohongshu-skills/stargazers) — 基于已登录浏览器的搜索、阅读、发布与互动 Skills。
- [jackwener/xhs-cli](https://github.com/jackwener/xhs-cli) [![Stars](https://img.shields.io/github/stars/jackwener/xhs-cli?style=flat-square)](https://github.com/jackwener/xhs-cli/stargazers) — 终端里的搜索、阅读、用户浏览和互动工具，并附带 `SKILL.md`。

## Content creation and visual cards

| Project | What it does | License |
| --- | --- | --- |
| [op7418/guizang-social-card-skill](https://github.com/op7418/guizang-social-card-skill) | 小红书轮播图、公众号封面；HTML → PNG；多版式、多主题 | AGPL-3.0 |
| [dososo/blcaptain-style-skill](https://github.com/dososo/blcaptain-style-skill) | 文章 → 海报级组图；Still Paper / Signal Proof / Bridge Canvas；支持 3:4、方形和横版 | 未声明 |
| [JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills) | `baoyu-xhs-images`：内容 → 1–10 张小红书图文卡片 | MIT |
| [qianjiazheng2023/xiaohongshu-article-cards](https://github.com/qianjiazheng2023/xiaohongshu-article-cards) | 文章、教程、知识内容 → 竖版轮播卡片，同时生成标题、正文和话题 | 未声明 |
| [Vivixiao980/xhs-cover-skill](https://github.com/Vivixiao980/xhs-cover-skill) | 小红书封面生成器，多种预设风格 | 未声明 |
| [leefrane-creator/XHS-link-to-card-pipeline](https://github.com/leefrane-creator/XHS-link-to-card-pipeline) | 链接或 Markdown → 摘要、知识卡、PNG 和标题/标签/正文/CTA | 未声明 |
| [pilipala5/RedBookCards](https://github.com/pilipala5/RedBookCards) | Markdown → 小红书竖版卡片；自动分页、主题和图片导出 | 未声明 |
| [NimaChu/xhs-imagen](https://github.com/NimaChu/xhs-imagen) | 面向科普类小红书图文内容的 Skill | MIT |
| [xue-feng-bai/xiaohongshu-card-builder-collection](https://github.com/xue-feng-bai/xiaohongshu-card-builder-collection) | 多种 Markdown → 小红书卡片构建器和本地 HTML 版本 | 未声明 |
| [nexu-io/html-anything](https://github.com/nexu-io/html-anything) | 多平台 HTML 设计 Skill 集合，包含 XHS / 社交卡片创作面 | Apache-2.0 |
| [bozhouDev/xhs-article-to-images](https://github.com/bozhouDev/xhs-article-to-images) | Agent-assisted Markdown 文章 → 小红书图片卡片工作流 | MIT |
| [manwithshit/xhs-images](https://github.com/manwithshit/xhs-images) | 小红书信息图系列生成器，面向 Claude Skill | MIT |
| [ponyodong2026/ponyo-cover-anchor-system](https://github.com/ponyodong2026/ponyo-cover-anchor-system) | 封面信息密度与视觉锚点设计 Skill | 未声明 |
| [mythkiven/rednote-director-skill](https://github.com/mythkiven/rednote-director-skill) | 图文轮播规划、视觉导演、封面内页、AI 生图提示词和发布文案 | MIT |
| [ioioiioo12138/xhs-note-creator](https://github.com/ioioiioo12138/xhs-note-creator) | 笔记内容创作工具包；多视觉主题和分页模式 | 未声明 |
| [QHaoQi/xhs-editorial](https://github.com/QHaoQi/xhs-editorial) | 用真实产品 UI 制作杂志感小红书轮播图、封面和 Demo GIF | MIT |
| [SuperMarioYL/coverlock](https://github.com/SuperMarioYL/coverlock) | 锁定账号级 style-pack，让后续封面保持视觉一致 | Apache-2.0 |
| [bethel-mark/travel-xhs-content](https://github.com/bethel-mark/travel-xhs-content) | 旅行主题：标题、正文、标签、图片提示词、封面建议和发布策略 | MIT |

## Research, reading and idea discovery

| Project | What it does | License |
| --- | --- | --- |
| [lucasygu/redbook](https://github.com/lucasygu/redbook) | 关键词研究、竞品分析、爆款拆解、模板提取、选题策划和图文卡片渲染 | MIT |
| [jackwener/xhs-cli](https://github.com/jackwener/xhs-cli) | 终端搜索、阅读笔记、浏览用户、点赞、收藏、评论和发布 | Apache-2.0 |
| [piekill/xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill) | 搜索并提取图文与评论，生成综合调研报告 | 未声明 |
| [chenxiachan/xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills) | 将小红书笔记提取到 Obsidian，适合资料归档和二次研究 | MIT |
| [DeliciousBuding/xiaohongshu-skill](https://github.com/DeliciousBuding/xiaohongshu-skill) | 基于 Playwright 的搜索、帖子详情和用户主页提取工具 | MIT |
| [vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills) | 覆盖内容创作、账号运营、互动、数据分析、电商和增长的技能集合 | 未声明 |
| [mini20201314-crypto/xhs-ai-tools-writer](https://github.com/mini20201314-crypto/xhs-ai-tools-writer) | 面向 AI 工具内容的小红书写作工作流 | MIT |
| [d-wwei/great-writer](https://github.com/d-wwei/great-writer) | 通用 AI 写作 Skill，覆盖小红书笔记、营销文案和反 AI 味改写 | MIT |
| [codewithwu/xiaohongshu-writer](https://github.com/codewithwu/xiaohongshu-writer) | 小红书帖子、种草、教程攻略、观点分享和生活记录写作 Skill | MIT |
| [aislinn-yang/rednote-writing-skill](https://github.com/aislinn-yang/rednote-writing-skill) | RedNote 文案写作；加入 AI 痕迹和平台风险词检查 | MIT |
| [coinluu/xhs-topic-strategist-skill](https://github.com/coinluu/xhs-topic-strategist-skill) | 选题规划、趋势匹配、评分和风险复核，无代码依赖 | MIT |
| [azlll/xhs-notes-skill](https://github.com/azlll/xhs-notes-skill) | 看图理解、选题、标题正文、标签、评论钩子和风险检查 | MIT |
| [zhangchitc/analyze-xiaohongshu](https://github.com/zhangchitc/analyze-xiaohongshu) | 分析小红书账号、笔记和封面，生成多维方法论报告与交互式面板 | 未声明 |
| [atian-create/xhs-profile-breakdown-skill](https://github.com/atian-create/xhs-profile-breakdown-skill) | 小红书 / RedNote 创作者主页拆解和清晰度检查 | MIT |
| [864536370dhy-png/xhs-account-diagnosis-skill](https://github.com/864536370dhy-png/xhs-account-diagnosis-skill) | 小红书账号流量与涨粉诊断 Skill | MIT |
| [PENGLEI8686/xhs-reader-view](https://github.com/PENGLEI8686/xhs-reader-view) | 小红书 / RedNote 笔记读者视角审稿 Skill | MIT |

## Publishing, operations and MCP

这些项目可能直接操作真实账号、浏览器会话、Cookie 或平台互动接口。建议先用测试账号、低频运行，并对最终内容人工复核。

| Project | What it does | License |
| --- | --- | --- |
| [white0dew/XiaohongshuSkills](https://github.com/white0dew/XiaohongshuSkills) | 自动发布、搜索、详情读取、评论、回复、点赞、收藏、用户页和数据看板 | MIT |
| [autoclaw-cc/xiaohongshu-skills](https://github.com/autoclaw-cc/xiaohongshu-skills) | 使用已登录浏览器进行搜索、阅读、发布和互动 | MIT |
| [Xiangyu-CAS/xiaohongshu-ops-skill](https://github.com/Xiangyu-CAS/xiaohongshu-ops-skill) | 小红书定位、选题、创作、复盘、复刻和运营助手 | 未声明 |
| [2975647277/xiaohongshu-mcp](https://github.com/2975647277/xiaohongshu-mcp) | 小红书 MCP Server；内容生成、发布和定时发布等能力 | 未声明 |
| [ibreez3/xiaohongshu-skill](https://github.com/ibreez3/xiaohongshu-skill) | 通过 MCP / API 适配器发布图文、视频，并执行搜索和互动 | MIT |

## QA and multi-platform content pipelines

| Project | What it does | License |
| --- | --- | --- |
| [XshuiAi/media-publish-check](https://github.com/XshuiAi/media-publish-check) | 面向小红书、抖音、视频号和快手的发布前审核 Skill | MIT |
| [yanhua1010/self-media-content-workflow](https://github.com/yanhua1010/self-media-content-workflow) | 模块化自媒体内容生产与经营 Skills | MIT |
| [OrangeViolin/content-pipeline](https://github.com/OrangeViolin/content-pipeline) | 一次输入、多平台内容生产与发布的 Claude Code Skill | MIT |
| [erafat/skills](https://github.com/erafat/skills) | 包含 `md-to-xhs-cards` 的可复用 Skills 集合，并覆盖直接发布 | MIT |
| [Jian21311/account-diagnosis-skill](https://github.com/Jian21311/account-diagnosis-skill) | 公开账号诊断规则：先判断手上有没有数据再定怎么判，六个维度分三档，不给总分，只指出最该改的一件；不抓取数据、不登录账号 | CC BY 4.0 |

## A practical creator workflow

1. 用 `redbook`、`xhs-cli` 或 `xiaohongshu-summarizer-skill` 做选题和参考笔记研究。
2. 用 `BLCaptain`、`Guizang Social Card Skill` 或 `baoyu-xhs-images` 做内容拆页和视觉卡片。
3. 优先使用自己的照片、截图或可核验的公开素材，并保留来源。
4. 用 `media-publish-check` 做发布前检查。
5. 最后人工上传和复核；自动发布、评论、点赞不作为默认步骤。

## Xiaohongshu discovery notes

我也尝试在小红书站内搜索 `小红书 skill`、`REDSkill`、`小红书卡片 Skill` 和 `AI 小红书内容创作`。公开未登录状态下，搜索页只显示登录入口，没有返回可以逐条核验的笔记结果，因此本列表不会把搜索不到正文的站内帖子伪装成项目来源。

目前已确认的一条站内线索是：[开源个skill | 小红书多画幅图文卡片](https://xhslink.cn/o/8VJBZcJcS7N)，其内容对应 [BLCaptain Style Skill](https://github.com/dososo/blcaptain-style-skill)。后续如果有已登录的站内搜索结果或笔记链接，可以继续补充到本节和目录中。

## Curation policy

- 项目公开可访问，且 README 或仓库结构能确认与小红书 / RED / RedNote 相关。
- 优先收录带 `SKILL.md`、CLI、MCP 或可复用渲染管线的项目。
- 区分“创作”“研究”“运营/发布”，不把自动化能力伪装成内容创作能力。
- 标注许可证；没有明确许可证时标为“未声明”，不推断其可商用。
- 不以 Star 数作为唯一标准；项目是否真的可运行、文档是否清楚、权限边界是否透明同样重要。
- 发现失效链接、过时项目、重复项目或安全问题，欢迎提交 Issue。

## Contributing

欢迎提交新的 Skill、CLI、MCP 或卡片生成器：

- 提交 GitHub 仓库地址
- 简述主要能力和适用场景
- 标注许可证
- 说明是否需要登录、Cookie、API Key 或本地浏览器
- 说明是否包含自动发布、评论、点赞等高风险操作

直接提交 [Issue](https://github.com/1sh1ro/awesome-xiaohongshu-skills/issues) 或 Pull Request 即可。

## Search keywords

`xiaohongshu` · `小红书` · `rednote` · `RED` · `xhs` · `agent-skills` · `claude-code` · `codex` · `openclaw` · `mcp` · `xiaohongshu-card` · `social-card` · `content-creation` · `content-automation` · `knowledge-cards` · `markdown-to-png`

## License

本列表本身未对所列项目授予额外许可证；每个项目的代码、素材和文档以其仓库声明为准。
