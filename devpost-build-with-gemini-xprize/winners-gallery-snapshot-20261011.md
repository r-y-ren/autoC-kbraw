# 快照：Build with Gemini XPRIZE 获奖项目画廊（browser-use 预抓，winners 深构分片素材）

- 来源 URL: https://xprize.devpost.com/project-gallery（"View the winners" 入口；旧 /winners 路径已 404）
- 抓取日期: 2026-10-11（浏览器渲染+无限滚动后 DOM 提取）
- 赛事背景：$2,000,000 / 25 个获奖名额（$500k×1 + $200k×1 + $100k×3 + $50k×15 Runner Up + $50k×5 Category，rules 口径）；参赛 26419 人；90 天赛程 May 19 – Aug 17, 2026；获奖者 2026-09-25 前后公布（条目 watch 记录）。
- **注意**：gallery 的 "Winner" 徽章**不区分奖金档位**（本轮实抓 24 卡带徽章，规则 25 席差 1——可能 1 席未渲染或某 Category 席位无徽章；深构分片可访问 xprize.devpost.com/updates 页核实档位与缺口，devpost 页面为 SPA，WebFetch 可能空壳，必要时回报请求预抓）。
- 类别筛选器（gallery 侧栏）：Education & Human Potential / Entrepreneurship & Job Creation / Small Business Services / Money & Financial Access / Professional Services Access。

## Winner 徽章项目（24，2026-10-11 实抓）

| 项目 | 项目页 | 一句话描述（gallery 卡原文摘录） |
|---|---|---|
| Polyfork | https://devpost.com/software/polyfork | 3D assets you can recolor, resize, remix. Each model is a little program, AI-native, and fully customizable. |
| TICIAN Cierre | https://devpost.com/software/tician-cierre | Recovers VAT credits for Mexican businesses: processes CFDI, assembles the SAT file, and submits every close to a Vertex AI auditor that approves or rejects it with its reasons. |
| MyFixam | https://devpost.com/software/fixam | TaskRabbit for Nigeria's informal artisan economy, where 93% of workers have no way to get paid safely |
| LaunchBridge | https://devpost.com/software/launchbridge | AI tool that takes you from a business idea to actually having an LLC, EIN, website, and payments set up, all within a single platform in under 72 hours, in the state of Virginia. |
| DodoPrep - The Autonomous Learning OS | https://devpost.com/software/dodoprep-the-autonomous-learning-os | AI-native tutor that transforms any study material into personalized learning, adapts to knowledge gaps and progress. |
| ActinGym | https://devpost.com/software/actingym | Duolingo for performing arts: multimodal AI analyzes performances, video-first coaching across public speaking, dancing, singing, content creation and acting. |
| Ten Minutes Wiser | https://devpost.com/software/ten-minutes-wiser | Finds fascinating topics and turns them into trustworthy 10-minute daily lessons to read or hear, with quiz and personalized quests. |
| OpportunityOS | https://devpost.com/software/opportunityos-ikfs5b | AI-powered opportunity OS that helps students discover, evaluate, and apply for scholarships, jobs, internships, and grants. |
| Pantry Insight | https://devpost.com/software/pantry-insight | Know your impact. Feed your community better. |
| Seedubator | https://devpost.com/software/seedubator | Your AI Co-Founder |
| GrowthSphere AI | https://devpost.com/software/growth-sphere-ai | AI That Thinks, Strategizes, and Grows With You! |
| Olva | https://devpost.com/software/olva | The AI-native career OS. Everything runs on one living record. |
| PLENO APP | https://devpost.com/software/pleno-app | Latin American entrepreneurs juggle 5 apps: PLENO unifies finances, habits and projects, with agents that actually run the work. |
| Enamel | https://devpost.com/software/enamel | The AI operating system for a small dental clinic — records, scheduling, billing, lab and stock. Runs on the clinic's own computer, fully offline. One-time licence. |
| Spoken Letter | https://devpost.com/software/spoken-letter | Any family member records a story in their own voice and sends it to a child's Yoto. Screen-free. |
| EsencIA | https://devpost.com/software/esencia | Turns WhatsApp into an AI companion for older adults: stay connected, keep learning, preserve family stories in a Living Biography. |
| Teluma | https://devpost.com/software/teluma | AI-native platform deploying autonomous multi-agent pipelines to discover non-dilutive grants, evaluate fit, draft compliant proposals. |
| Barber Copilot | https://devpost.com/software/barber-copilot | Small human team + specialized AI agents serving hundreds of barbershops: AI workforce for customer retention. |
| Ability Bazaar: Talent with Disabilities | https://devpost.com/software/abilitybazaar-talent-with-disabilities-apps-without-barriers | Talent with Disabilities: apps without barriers. |
| Sembramos: AI-Native Wholesale Agriculture | https://devpost.com/software/sembramos-ai-powered-p2p-agriculture | AI-powered P2P wholesale agriculture. |
| Kosmo | https://devpost.com/software/intent-compiler | Turn your idea into a flawless AI prompt. |
| NoBanks Nearby: Art by a Human, Business by AI | https://devpost.com/software/nobanks-nearby-art-by-a-human-business-by-ai | Art by a Human, Business by AI. |
| TRAMA AI, Corp. | https://devpost.com/software/trama-ai-corp | AI agent on WhatsApp running inventory and operations for mid-size textile companies. Live in production with a paying customer — real-time inventory, orders, FIFO dispatch. |
| MiMi Money | https://devpost.com/software/mimi-money | AI Agent powered Super app, Blockchain Wallet and Web3/Web4 Gateway for Humans and AI agents. |

## 主会话线索观察（供分片参考，非事实源）

- 获奖画像高度"小生意/垂直行业 Agent"：墨西哥 VAT 合规（TICIAN）、尼日利亚工匠平台（MyFixam）、理发店留存（Barber Copilot）、纺织厂 WhatsApp 库存（TRAMA）、牙科诊所离线 OS（Enamel）、拉美小老板统一 OS（PLENO）——"AI agent 替小企业跑业务流程"是最大公约数。
- 教育类：DodoPrep/ActinGym/Ten Minutes Wiser/OpportunityOS；金融类：MiMi Money/Teluma/LaunchBridge。
- 叙事弱技术炫耀、强落地证据（"Live in production with a paying customer"），与赛事 "Real product. Real revenue. A real business." 评审口径一致。
