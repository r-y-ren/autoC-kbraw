# 快照：Kaggle 竞赛列表（browser-use 预抓，P1 规则）

- 来源 URL: https://www.kaggle.com/competitions?listOption=active（另访 ?listOption=upcoming 回显页）
- 抓取日期: 2026-10-11（浏览器渲染后 DOM 提取；SPA 站点，WebFetch 空壳不可用）
- 用途: 分片候选线索。**条目事实仍须经该赛事详情页核实后才可写入条目**（详情页事实引用本文件不算数）。
- 说明: items 为页面可见竞赛卡片 (slug, 卡片聚合文本)；Getting Started 常驻区有已知噪声。

## 进行中（页面可见竞赛卡片，2026-10-11）

| slug | 卡片文本（聚合） |
|---|---|
| nfl-big-data-bowl-2027 | NFL Big Data Bowl 2027Uncover non-obvious linkages between Combine sensor tracking and regular-season NFL game performance Featured · Hackathon · 175 Teams · 3 months to go$100,000 |
| playground-series-s6e10 | Predicting Airline SatisfactionPlayground Series - Season 6 Episode 10 Playground · 1500 Teams · 20 days to goSwag |
| the-pokemon-company-ptcg-ai-battle-challenge-playground | The Pokémon Company - PTCG AI Battle Challenge PlaygroundBuild an AI Training Agent to play the Pokémon Trading Card Game Playground · Simulation Competition · 317 Teams · 3 months to goSwag |
| gemma-4-developer-agent-paper | Google - The Gemma 4 Developer Agent Paper TrackSubmit a Research Paper advancing the state-of-the-art for agentic software engineering Featured · Hackathon · 189 Teams · A month to go$35,000 |
| gemma-4-developer-agent | Google - The Gemma 4 Developer Agent CompetitionAccelerate research in autonomous coding agents Featured · 2422 Teams · 2 months to go$65,000 |
| enveda-CASMI26-molecule-id-mass-spectra | Enveda CASMI 2026 - Molecule ID From Mass SpectraPredict 2D chemical structures of small molecules detected in complex biological extracts Featured · Code Competition · 3049 Teams · 2 months to go$50,000 |
| rsna-knee-abnormality-detection | RSNA Knee Abnormality DetectionCreate a model that can detect knee abnormalities based on multimodal imaging data Research · Code Competition · 5743 Teams · 11 days to go$77,000 |
| kaggriculture | KaggricultureCreate an agent to play in this farming simulation and compete with others to maximize your income Featured · Simulation Competition · 10148 Teams · 3 days to go$50,000 |
| arc-prize-2026-arc-agi-3 | ARC Prize 2026 - ARC-AGI-3Create an AI capable of fluid intelligence Featured · Code Competition · 4135 Teams · 22 days to go$850,000 |
| arc-prize-2026-arc-agi-2 | ARC Prize 2026 - ARC-AGI-2Create an AI capable of novel reasoning Featured · Code Competition · 2730 Teams · 22 days to go$700,000 |
| arc-prize-2026-paper-track | ARC Prize 2026 - Paper TrackDocument your conceptual approach for the ARC Prize 2026 Featured · Hackathon · 246 Teams · A month to go$450,000 |
| （Getting Started 常驻区：llm-classification-finetuning/spaceship-titanic/store-sales/contradictory-watson/tpu-getting-started/connectx/nlp-getting-started/home-data/house-prices 九条 Ongoing 噪声，略） | |

## 本快照新增观察（对比 2026-10-05）

- **新 Featured 赛：nfl-big-data-bowl-2027**（$100k，175 队，3 个月窗口）——10-05 快照无此卡，为本周新上线（或新进入 active 池）。
- 队数增长：ARC-AGI-3 3676→4135（+459）；Gemma4 DevAgent 1684→2422（+738）；RSNA 5126→5743；PTCG Playground 172→317；Enveda 2439→3049。
- **kaggriculture "3 days to go"**（终交 2026-10-14 前后）；RSNA "11 days to go"（entry 10-15 临期）——两条时间敏感。
- Gemma4 主赛卡片 10-05 时带 "Hackathon" 标签、本轮显示 "Featured"（标签口径微变，以详情页为准）。
