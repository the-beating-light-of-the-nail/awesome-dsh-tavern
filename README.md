# Awesome DSH Tavern 🍺

> **English** | [简体中文](./README.zh-CN.md)
>
> Curated tavern & roleplay plugins for DeepSeek Harness (dsh) — the tavern, rebuilt on an agent.

"The tavern keeps getting heavier while agents keep getting smarter." This list collects the plugins that move SillyTavern's character cards, worldbooks and presets into dsh — so characters can use the harness's tools, memory and sub-agents instead of replaying the old playbook inside another heavyweight dedicated frontend.

- For the ecosystem at large, see the general lists ([awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) et al.); this list covers the **tavern × roleplay** vertical only.
- Companion site: [DSH Meme Hub · Tavern & Roleplay section](https://dsh-meme-hub.cdqyfdbymn.me/plugins/tavern) (four languages, install commands, star-sorted).

⭐ = GitHub star snapshot (**2026-09-11**, not live); "updated" = last push date. Several repos share the same name — always refer to the full `owner/repo`.

## Contents

- [Agent RP Runtimes](#agent-rp-runtimes)
- [Text Games & Scripted Stories](#text-games--scripted-stories)
- [Tavern Management Panels](#tavern-management-panels)
- [Card Authoring & Worldbooks](#card-authoring--worldbooks)
- [Input & Rendering](#input--rendering)
- [Personas & Roleplay](#personas--roleplay)
- [Ecosystem Resources](#ecosystem-resources)

## Agent RP Runtimes

Characters act as top-level agents; personas, worlds, rules and memory are composable first-class resources.

- [hewzhew/dsh-agent-rp](https://github.com/hewzhew/dsh-agent-rp) — Native roleplay runtime: imports tavern character cards (PNG/JSON/CHARX), Chat Completion presets, World Info, MVU, EJS and Tavern Helper; a story-engineering layer has research, character, actor, section and editor workers maintain outlines and foreshadowing. ⭐214 · updated 2026-09-05
- [RiemannRe3/DSH-RolePlay](https://github.com/RiemannRe3/DSH-RolePlay) — Tavern character-card compatibility and native agent roleplay. ⭐7 · updated 2026-08-30
- [LiweiDonVee/dsh-rp-studio](https://github.com/LiweiDonVee/dsh-rp-studio) — Content-free roleplay frontend and gateway: bring your own presets and runtime. ⭐1 · updated 2026-09-09
- [Ryu6Zero/dsh-character-studio](https://github.com/Ryu6Zero/dsh-character-studio) — Immersive RP & companion studio: character cards plus Hindsight graph memory, configured per character. ⭐0 · updated 2026-08-29

## Text Games & Scripted Stories

- [flizzywine/dsh-tavern](https://github.com/flizzywine/dsh-tavern) — SillyTavern-style text-game agent: prose and candidate options on separate tracks, an independent character-state summary keeps positions and status consistent, a script mode anchors long stories to their intended arc, with turn rollback; builds new cards from novels and scripts. [Docs](https://flizzywine.github.io/dsh-tavern/). ⭐243 · updated 2026-09-10
- [bigharm/dsh-agentnoodle](https://github.com/bigharm/dsh-agentnoodle) — AI-driven ensemble chat-game framework (a lightweight tavern), compatible with ST V1/V2/V3 JSON and PNG-embedded cards. ⭐0 · updated 2026-08-31
- [makenwjz/dsh-novel-tavern](https://github.com/makenwjz/dsh-novel-tavern) — Novel mode plus tavern mode: a novel-writing workspace and an ST-compatible tavern with WeChat-style chat UI and card bridging. ⭐4 · updated 2026-08-20

## Tavern Management Panels

Native panels for multiple character cards, worldbooks and presets.

- [Amakurai/dsh-liketavern](https://github.com/Amakurai/dsh-liketavern) — Turns dsh web into a SillyTavern-style frontend: import ST cards and presets, advance the plot, re-roll and switch branches within one session; ships EJS prompt templates and partial Tavern Helper interfaces. ⭐84 · updated 2026-09-10
- [LingyeSoul/dsh-tavern](https://github.com/LingyeSoul/dsh-tavern) — Native roleplay workspace: V1/V2/V3 cards, worldbook recursive scanning and budget control, JSONL logs, swipes and message branching, persona injection, group chat. ⭐14 · updated 2026-09-10
- [chen731215-dev/dsh-tavern-v2](https://github.com/chen731215-dev/dsh-tavern-v2) — Tavern management panel v2: character-card roleplay, worldbook management, preset switching, dark theme, memory summaries, NSFW toggle (PolyForm non-commercial license). ⭐13 · updated 2026-08-31
- [XCNXNXNX/dsh-portable-tavern](https://github.com/XCNXNXNX/dsh-portable-tavern) — A "portable tavern": RPG-style V2/V3 card generator plus tavern roleplay chat, with worldbooks, JSON/PNG import-export, panel themes and local music. ⭐21 · updated 2026-08-20
- [yejiming/dsh-museai-tavern](https://github.com/yejiming/dsh-museai-tavern) — Bring your MuseAI characters into DSH. ⭐19 · updated 2026-08-15
- [tk553521/dsh-tavern](https://github.com/tk553521/dsh-tavern) — ST-style roleplay: character cards / worldbooks / presets / multi-agent. ⭐2 · updated 2026-08-23
- [Star-Guest/dsh-plugin-tavern](https://github.com/Star-Guest/dsh-plugin-tavern) — Compact tavern: a card-analyst agent parses character cards while a roleplay agent narrates. ⭐3 · updated 2026-08-22
- ~~[chen731215-dev/dsh-tavern](https://github.com/chen731215-dev/dsh-tavern)~~ — Archived; migrated to dsh-tavern-v2 above. ⭐40 · 2026-08-27

## Card Authoring & Worldbooks

- [xia-sc/dsh-cc-studio](https://github.com/xia-sc/dsh-cc-studio) — CCv3 character-card studio: turns a one-line idea into a chara_card_v3 importable to SillyTavern / Risu. ⭐2 · updated 2026-09-10
- [VO-Bogey/dsh-tavernweave](https://github.com/VO-Bogey/dsh-tavernweave) — Native DSH frontend for the TavernWeave card-authoring system. ⭐8 · updated 2026-09-03
- [bychv/dsh-stcardwriter](https://github.com/bychv/dsh-stcardwriter) — Authoring plugin for ST character cards, worldbooks and presets, with Preset Plus integrated. ⭐2 · updated 2026-09-03
- [609476965/dsh-LorebookMD](https://github.com/609476965/dsh-LorebookMD) — Import tavern character cards and worldbooks as local Markdown lore documents, then write novels with a creation mode. ⭐19 · updated 2026-08-14
- [TritiumWang/dsh-universal-worldbook](https://github.com/TritiumWang/dsh-universal-worldbook) — General-purpose worldbook: attaches one-shot injections to the latest user message with no context pollution. ⭐1 · updated 2026-09-06

## Input & Rendering

- [wuzhigouno-collab/dsh-rp-composer](https://github.com/wuzhigouno-collab/dsh-rp-composer) — TriComposer: fill in dialogue / action / inner-thought boxes and send assembled templates, eliminating the model's misreading of player speech at the input layer. ⭐3 · updated 2026-08-24
- [LiweiDonVee/dsh-tavern-renderer](https://github.com/LiweiDonVee/dsh-tavern-renderer) — Independent message renderer with sanitized HTML/CSS, macros and eight immersive document templates. ⭐1 · updated 2026-09-09
- [Player-MINEPIG/dsh-tavern](https://github.com/Player-MINEPIG/dsh-tavern) — Makes dsh compatible with SillyTavern artifacts. ⭐12 · updated 2026-09-10

## Personas & Roleplay

- [ZelinW1/dsh-cosplay](https://github.com/ZelinW1/dsh-cosplay) — Global cosplay switch, tavern v2 character cards (JSON import-export), and a built-in skill that authors cards from one sentence. ⭐6 · updated 2026-08-19
- [chinosk6/dsh-roleplay](https://github.com/chinosk6/dsh-roleplay) — Character-card conversations, in-chat card authoring and editing, optional image-generation backend for illustrations. ⭐6 · updated 2026-09-09
- [lutrodev/dsh-roleplay](https://github.com/lutrodev/dsh-roleplay) — Roleplay suite: character cards, lorebooks, personas, presets, state and conversation tools. ⭐7 · updated 2026-09-03
- [oliblue-evan/dsh-roleplay-preset](https://github.com/oliblue-evan/dsh-roleplay-preset) — Immersive RP agent preset tuned for DeepSeek: zero-tool pure conversation, tavern-style performance formatting, file-based memory store. ⭐19 · updated 2026-09-01
- [loonai321/dsh-humanized-deepseek-maid](https://github.com/loonai321/dsh-humanized-deepseek-maid) — Configurable whale-girl maid persona: immersive roleplay plus layered memory with on-demand recall. ⭐5 · updated 2026-08-26
- [ajuwm/dsh-roleplay-plugin](https://github.com/ajuwm/dsh-roleplay-plugin) — Roleplay as the core, desktop pet as a bonus. ⭐1 · updated 2026-09-10

## Ecosystem Resources

- [SillyTavern](https://github.com/SillyTavern/SillyTavern) — The tavern itself; definer of the character-card and worldbook formats.
- [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) — dsh itself, with the plugin protocol docs.
- [Awesome DSH Plugin discussion (official #215)](https://github.com/deepseek-ai/deepseek-harness/discussions/215) — The official repo's plugin showcase thread.
- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) — The ecosystem's largest general list (no tavern vertical yet — that's this list's job).
- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) — General directory with a catalog.
- [DSH Meme Hub · Tavern & Roleplay](https://dsh-meme-hub.cdqyfdbymn.me/plugins/tavern) — Companion site section (four languages, install commands, star-sorted).

## Inclusion criteria

1. It is a DeepSeek Harness (dsh) plugin, preset or directly related tooling;
2. Directly relevant to tavern / roleplay / character cards / worldbooks / RP;
3. The repo has a substantive README (empty shells are not listed);
4. Archived repos stay as a struck-through pointer to their successor, excluded from active recommendations.

PRs and self-nominations welcome. Include: repo link, a one-line description (English, plus Chinese if you like), and the section it belongs to; star counts and update dates are refreshed by the maintainer as snapshots, not live values.

## License

[MIT](./LICENSE) · List data as of 2026-09-11; refer to each repo for its current state.
