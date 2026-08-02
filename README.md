# Awesome Xiaohongshu Skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/1sh1ro/awesome-xiaohongshu-skills?style=flat-square)](https://github.com/1sh1ro/awesome-xiaohongshu-skills/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/1sh1ro/awesome-xiaohongshu-skills?style=flat-square)](https://github.com/1sh1ro/awesome-xiaohongshu-skills/commits/main)

**A curated list of Agent Skills, CLIs, MCP servers, and content tools for Xiaohongshu / RED / RedNote.**

作为一个小红书内容创作者，总是想用办法美化内容，但是一下子又找不到好的 Skills，要一个个试。

所以这里收录了一部分高星、实用、和小红书内容创作相关的 Skills 与工具：从选题研究、爆款拆解，到标题正文、图文卡片、封面设计，再到发布前检查和账号运营。欢迎提 Issue 推荐你正在使用的项目。

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

## Research, reading and idea discovery

| Project | What it does | License |
| --- | --- | --- |
| [lucasygu/redbook](https://github.com/lucasygu/redbook) | 关键词研究、竞品分析、爆款拆解、模板提取、选题策划和图文卡片渲染 | MIT |
| [jackwener/xhs-cli](https://github.com/jackwener/xhs-cli) | 终端搜索、阅读笔记、浏览用户、点赞、收藏、评论和发布 | Apache-2.0 |
| [piekill/xiaohongshu-summarizer-skill](https://github.com/piekill/xiaohongshu-summarizer-skill) | 搜索并提取图文与评论，生成综合调研报告 | 未声明 |
| [chenxiachan/xhs-claude-skills](https://github.com/chenxiachan/xhs-claude-skills) | 将小红书笔记提取到 Obsidian，适合资料归档和二次研究 | MIT |
| [DeliciousBuding/xiaohongshu-skill](https://github.com/DeliciousBuding/xiaohongshu-skill) | 基于 Playwright 的搜索、帖子详情和用户主页提取工具 | MIT |
| [vivy-yi/xiaohongshu-skills](https://github.com/vivy-yi/xiaohongshu-skills) | 覆盖内容创作、账号运营、互动、数据分析、电商和增长的技能集合 | 未声明 |

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

## A practical creator workflow

1. 用 `redbook`、`xhs-cli` 或 `xiaohongshu-summarizer-skill` 做选题和参考笔记研究。
2. 用 `BLCaptain`、`Guizang Social Card Skill` 或 `baoyu-xhs-images` 做内容拆页和视觉卡片。
3. 优先使用自己的照片、截图或可核验的公开素材，并保留来源。
4. 用 `media-publish-check` 做发布前检查。
5. 最后人工上传和复核；自动发布、评论、点赞不作为默认步骤。

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
