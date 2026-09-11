# Awesome DSH Tavern 🍺

> DeepSeek Harness（dsh）酒馆与角色扮演插件精选 — 把酒馆搬进 agent。
> A curated list of tavern-style roleplay plugins for DeepSeek Harness (dsh).

「酒馆越用越重，agent 越来越能干」——这个清单收录把 SillyTavern 的角色卡、世界书、预设生态搬进 dsh 的插件：角色直接用上 harness 的工具、记忆与子 Agent 能力，而不是在一个重型专用前端里重演旧玩法。

- 生态总目录见综合清单（[awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) 等），本清单只做**酒馆 × 角色扮演**垂直方向。
- 配套网站：[DSH Meme Hub · 酒馆与角色扮演专区](https://dsh-meme-hub.cdqyfdbymn.me/plugins/tavern)（四语落地页，含安装命令与筛选排序）。

⭐ 为 GitHub star 快照（**2026-09-11**，非实时）；「更新」为最近一次 push 日期。同名仓库较多，请以 owner 全名为准。

## 目录

- [Agent RP 运行时](#agent-rp-运行时)
- [文字游戏与剧本](#文字游戏与剧本)
- [酒馆管理面板](#酒馆管理面板)
- [制卡与世界书](#制卡与世界书)
- [输入与渲染增强](#输入与渲染增强)
- [人格与扮演](#人格与扮演)
- [生态资源](#生态资源)

## Agent RP 运行时

角色作为顶层 Agent 行动，Persona / 世界 / 规则 / 记忆是可组合的一等资源。

- [hewzhew/dsh-agent-rp](https://github.com/hewzhew/dsh-agent-rp) — 原生角色扮演 Runtime：兼容酒馆角色卡（PNG/JSON/CHARX）、Chat Completion 预设、World Info、MVU、EJS 与 Tavern Helper；故事工程由多个 Worker 协作维护大纲与伏笔。⭐214 · 更新 2026-09-05
- [RiemannRe3/DSH-RolePlay](https://github.com/RiemannRe3/DSH-RolePlay) — Tavern 角色卡兼容与原生 Agent RolePlay。⭐7 · 更新 2026-08-30
- [LiweiDonVee/dsh-rp-studio](https://github.com/LiweiDonVee/dsh-rp-studio) — 无内容绑定的角色扮演前端与网关，自带预设与运行时即可开跑。⭐1 · 更新 2026-09-09
- [Ryu6Zero/dsh-character-studio](https://github.com/Ryu6Zero/dsh-character-studio) — 沉浸式 RP 与陪伴工作室：角色卡 + Hindsight 图谱记忆，按角色配置。⭐0 · 更新 2026-08-29

## 文字游戏与剧本

- [flizzywine/dsh-tavern](https://github.com/flizzywine/dsh-tavern) — SillyTavern 类文字游戏 Agent：正文与候选项分轨生成、独立人物态势总结、剧本模式锚定主线、回合回退；可从小说与剧本素材制卡。[在线文档](https://flizzywine.github.io/dsh-tavern/)。⭐243 · 更新 2026-09-10
- [bigharm/dsh-agentnoodle](https://github.com/bigharm/dsh-agentnoodle) — AI 驱动的群像聊天游戏框架（轻量化酒馆），兼容 ST V1/V2/V3 JSON 与 PNG 内嵌卡。⭐0 · 更新 2026-08-31
- [makenwjz/dsh-novel-tavern](https://github.com/makenwjz/dsh-novel-tavern) — 小说模式 + 酒馆模式：novel 创作工作区与 ST 兼容酒馆，微信式聊天 UI 与卡桥接。⭐4 · 更新 2026-08-20

## 酒馆管理面板

多角色卡、多世界书、多预设的原生管理面板。

- [Amakurai/dsh-liketavern](https://github.com/Amakurai/dsh-liketavern) — 把 dsh web 变成 SillyTavern 式前端：导入 ST 卡与预设，同会话推进剧情、重roll、切分支；内置 EJS 模板与部分酒馆助手接口。⭐84 · 更新 2026-09-10
- [LingyeSoul/dsh-tavern](https://github.com/LingyeSoul/dsh-tavern) — 原生角色扮演工作区：V1/V2/V3 卡、世界书递归扫描与预算、JSONL 记录、swipe 与消息分支、Persona 注入、群聊。⭐14 · 更新 2026-09-10
- [chen731215-dev/dsh-tavern-v2](https://github.com/chen731215-dev/dsh-tavern-v2) — 酒馆管理面板二代：角色卡扮演、世界书、预设切换、深色主题、记忆总结，含 NSFW 开关（PolyForm 非商业许可）。⭐13 · 更新 2026-08-31
- [XCNXNXNX/dsh-portable-tavern](https://github.com/XCNXNXNX/dsh-portable-tavern) — 「便携酒馆」：RPG 式 V2/V3 制卡器 + 酒馆聊天，世界书、JSON/PNG 导入导出、面板主题与本地音乐。⭐21 · 更新 2026-08-20
- [yejiming/dsh-museai-tavern](https://github.com/yejiming/dsh-museai-tavern) — 把 MuseAI 角色放进 DSH 使用。⭐19 · 更新 2026-08-15
- [tk553521/dsh-tavern](https://github.com/tk553521/dsh-tavern) — ST 风格角色扮演：人物卡 / 世界书 / 预设 / 多 agent。⭐2 · 更新 2026-08-23
- [Star-Guest/dsh-plugin-tavern](https://github.com/Star-Guest/dsh-plugin-tavern) — 酒馆精简版：card-analyst 解析角色卡 + roleplay 讲述者双 Agent 分工。⭐3 · 更新 2026-08-22
- ~~[chen731215-dev/dsh-tavern](https://github.com/chen731215-dev/dsh-tavern)~~ — 已归档，迁移至上面的 dsh-tavern-v2。⭐40 · 2026-08-27

## 制卡与世界书

- [xia-sc/dsh-cc-studio](https://github.com/xia-sc/dsh-cc-studio) — CCv3 角色卡工坊：一句话点子生成可导入 SillyTavern / Risu 的 chara_card_v3。⭐2 · 更新 2026-09-10
- [VO-Bogey/dsh-tavernweave](https://github.com/VO-Bogey/dsh-tavernweave) — TavernWeave 制卡系统的 DSH 原生前端。⭐8 · 更新 2026-09-03
- [bychv/dsh-stcardwriter](https://github.com/bychv/dsh-stcardwriter) — ST 角色卡、世界书与预设创作插件，集成 Preset Plus。⭐2 · 更新 2026-09-03
- [609476965/dsh-LorebookMD](https://github.com/609476965/dsh-LorebookMD) — 导入酒馆角色卡与世界书为本地 Markdown 设定文档，激活创作模式写小说。⭐19 · 更新 2026-08-14
- [TritiumWang/dsh-universal-worldbook](https://github.com/TritiumWang/dsh-universal-worldbook) — 通用世界书：为最新用户消息附加一次性注入，无上下文污染。⭐1 · 更新 2026-09-06

## 输入与渲染增强

- [wuzhigouno-collab/dsh-rp-composer](https://github.com/wuzhigouno-collab/dsh-rp-composer) — TriComposer：台词 / 动作 / 心理分框填空组装发送，从输入层消除成分误识别。⭐3 · 更新 2026-08-24
- [LiweiDonVee/dsh-tavern-renderer](https://github.com/LiweiDonVee/dsh-tavern-renderer) — 独立消息渲染器：白名单 HTML/CSS、宏与八个沉浸式文档模板。⭐1 · 更新 2026-09-09
- [Player-MINEPIG/dsh-tavern](https://github.com/Player-MINEPIG/dsh-tavern) — 让 dsh 兼容 SillyTavern artifacts。⭐12 · 更新 2026-09-10

## 人格与扮演

- [ZelinW1/dsh-cosplay](https://github.com/ZelinW1/dsh-cosplay) — 全局角色扮演开关 + 酒馆 v2 角色卡（JSON 导入导出）+ 一句话生成角色卡的内置 skill。⭐6 · 更新 2026-08-19
- [chinosk6/dsh-roleplay](https://github.com/chinosk6/dsh-roleplay) — 角色卡对话、对话中创作与编辑角色卡，可接生图后端出插图。⭐6 · 更新 2026-09-09
- [lutrodev/dsh-roleplay](https://github.com/lutrodev/dsh-roleplay) — RP 全家桶：角色卡、lorebook、personas、预设、状态与对话工具。⭐7 · 更新 2026-09-03
- [oliblue-evan/dsh-roleplay-preset](https://github.com/oliblue-evan/dsh-roleplay-preset) — DeepSeek 深度调校的沉浸式 RP Agent 预设：零工具纯对话、酒馆式演出格式、文件记忆库。⭐19 · 更新 2026-09-01
- [loonai321/dsh-humanized-deepseek-maid](https://github.com/loonai321/dsh-humanized-deepseek-maid) — 可配置的鲸鱼娘女仆人格：沉浸式扮演 + 分层记忆按需召回。⭐5 · 更新 2026-08-26
- [ajuwm/dsh-roleplay-plugin](https://github.com/ajuwm/dsh-roleplay-plugin) — 以角色扮演为主体、桌宠为附加功能。⭐1 · 更新 2026-09-10

## 生态资源

- [SillyTavern 官方](https://github.com/SillyTavern/SillyTavern) — 酒馆本馆；角色卡与世界书格式的定义者。
- [DeepSeek Harness 官方仓库](https://github.com/deepseek-ai/deepseek-harness) — dsh 本体与插件协议文档。
- [Awesome DSH Plugin 讨论（官方 #215）](https://github.com/deepseek-ai/deepseek-harness/discussions/215) — 官方仓库下的插件精选讨论帖。
- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) — 生态最大综合精选列表（暂无酒馆垂直分区，本清单补位）。
- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) — 综合目录，含 CATALOG。
- [DSH Meme Hub · 酒馆与角色扮演专区](https://dsh-meme-hub.cdqyfdbymn.me/plugins/tavern) — 本清单配套网站专区（四语、安装命令、star 排序）。

## 收录标准

1. 是 DeepSeek Harness（dsh）插件、预设或直接相关工具；
2. 与酒馆 / 角色扮演 / 角色卡 / 世界书 / RP 直接相关；
3. 仓库有实质 README（空壳仓库不收）；
4. 归档仓库保留一条删除线标注（指引继任者），不再计入活跃推荐。

欢迎 PR / issue 自荐。提交时请附：仓库链接、一句话中文描述、所属分区；star 数与更新日期由维护者统一刷新（快照制，不实时）。

## License

[MIT](./LICENSE) · 清单内容数据截至 2026-09-11，以各仓库实际情况为准。
