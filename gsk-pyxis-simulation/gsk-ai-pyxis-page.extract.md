# gsk.ai/pyxis-portfolio-challenge 正文抽取视图（sidecar）

- 原件：同目录 `gsk-ai-pyxis-page.html`（2026-10-05 curl 直抓，HTTP 200，27,412B）
- 抽取方法：trafilatura 返回 None（页面为 JS 渲染 SPA，`/fe/assets/js/index-legacy.js` 等 bundle）；页面正文以 JSON 内嵌富文本（`rich-text-content`）形式存在于 HTML 源码中，经 HTML 实体反转义后正则恢复。本文件为恢复出的关键文本块，引用一律指向 .html 原件。
- 页面 `<title>`：Pyxis Portfolio Challenge；`og:url` = http://gsk.ai/pyxis-portfolio-challenge/
- 子页 `/pyxis-portfolio-challenge/play/` HTTP 200（2026-10-05 复核）

## 挑战描述（内嵌富文本原文恢复）

> Build an AI agent that manages a simulated pharmaceutical R&D portfolio of drug programs. Decide which drugs to fund, continue or abandon as you compete against rival agents for the same assets and markets.

> Researchers have so far treated portfolio optimisation and competitive drug development as separate problems: portfolio models ignore competitors, while game-theory models only estimate behaviour from past data. Multi-agent simulation benchmarks have matured substantially in the meantime, but no one has combined all three.

> In our competition, you will build an AI agent to manage a simulated pharmaceutical R&D portfolio. It will compete head-to-head against other agents. Go bankrupt, and you lose immediately. Survive, and you'll be judged on net cash flow in a field where more than 80% of what you fund will fail.

> You'll be working on a problem at the core of a $300 billion-a-year industry. The techniques developed here could extend well beyond pharma, offering a new way to study high-stakes long-horizon decision-making.

## Kaggle 入口（原文恢复）

> Head to the competition page on Kaggle to find out how to play, download the starter environment and submit your agent: https://www.kaggle.com/competitions/gsk-simulation

## Timeline（原文恢复）

- **29 September 2026:** Competition opens
- **4 January 2027:** Entry deadline (rules must be accepted to compete) and team merger deadline
- **11 January 2027:** Final submission deadline

> Games will continue running for roughly two weeks after the deadline to reduce rating uncertainty, followed by a final Bradley-Terry tournament to produce the final leaderboard.

## Prizes（原文恢复）

- **1st place:** $15,000
- **2nd place:** $12,000
- **3rd place:** $9,000
- **4th place:** $8,000
- **5th place:** $6,000
- **Non-monetary:** An invitation to co-author the post-competition proceedings paper.

（monetary 合计 $50,000 为条目撰写时算术汇总，非页面原文口径）

## Official Rules（原文恢复）

> Full competition rules, eligibility requirements and terms are available via the Kaggle competition page [链接指向 https://www.kaggle.com/competitions/gsk-simulation]

## How to get involved（片段）

> Play against our baseline agents or watch replays of agents competing: gsk.ai/pyxis-portfolio-challenge/play/

## 隐私条款（片段，与 ai_policy 相关）

> By entering this challenge, GSK will have access to the username and email provided when you signed up to participate. GSK may use your information in the following ways: … As per the Official Rules of the challenge … To contact you to award you with a prize. Please visit our Privacy Notice（privacy.gsk.com/en-gb/privacy-notice/）

## 主办方自述（片段）

> GSK is a science-led global healthcare company … / GSK.ai uses AI to discover transformational medicines. …

页面页脚版权串为 "2001-2024 GSK plc"（陈旧年份，不作为事实引用）。
