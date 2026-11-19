# Austin Spraggins

**Co-Founder & CTO at LineCrush · Product engineering, applied AI, and developer tools**

I'm an expert at directing AI agents. I know how to brief them properly, how to review their work, and when to stop one that's headed the wrong way. I built LineCrush's self-sustaining, self-improving AI engineering fleet and C2, our replacement for Linear.

I started the LineCrush codebase in 2024, and Jay and I grew it into a paid sports research product. I built real-time delivery for research and alerts, led the live auth migration across web and mobile, automated backend releases, and shipped our ChatGPT integration.

I started both native apps from scratch and wrote their first month of code in SwiftUI and Kotlin with Jetpack Compose. I kept coding after launch, including updates to the research cards across all three clients and on-device answer narration on iOS. The fleet I built has written most of the later feature code. I own releases and store review for both apps.

The fleet rarely needs a person to step in. As of November 17, 2026, it had completed **14,111 jobs**, including **10,745 with a recorded commit link**. I led the move from Linear to C2 and brought over roughly **19,000 historical issues** while active work kept moving. [LineCrush engineering case study](https://www.spragginsdesigns.xyz/work/linecrush)

I created SureWord and shipped the web, Android, iPhone, iPad, and Mac apps myself. I built the Scripture retrieval that supplies exact verse text to the AI, the memory controls that let readers decide what carries into their next study, and one membership across Stripe, Apple, and Google Play. SureWord has a free plan and optional Pro. New accounts were up in the first 18 days of November 2026 compared with the same period in October. [SureWord engineering case study](https://www.spragginsdesigns.xyz/work/sureword)

I designed and developed Gunmetal Orbit in Godot and took it from first playable to a paid Steam launch in 67 days. I built the Steam release pipeline and a test that plays the exported game from launch through mining, combat, and banking ore. I shipped Windows and native Linux builds, added a signed and notarized macOS release, and fixed a controller bug I found on my own Steam Deck. Steamworks recorded paid sales and 152 lifetime wishlist additions as of November 19, 2026, up from 75 on September 17. [Gunmetal Orbit case study](https://www.spragginsdesigns.xyz/work/game-development#gunmetal-orbit)

I'm based in Fresno, California. [My resume](https://www.spragginsdesigns.xyz/resume)

## Shipped

| Product | What it is | Where |
| --- | --- | --- |
| **Agent fleet and C2** | AI engineering fleet that takes work from investigation through release, with C2 tracking the issue, the work, and the evidence. | [Fleet and C2 case study](https://www.spragginsdesigns.xyz/work/linecrush#c2) |
| **LineCrush** | Sports research platform with a Next.js and TypeScript web app, Python data services, PostgreSQL, Redis, and a ChatGPT integration built on MCP. I wrote the foundations of the SwiftUI iOS and Kotlin/Jetpack Compose Android apps and took both through store review and release. | [Web](https://www.linecrush.com) · [App Store](https://apps.apple.com/us/app/linecrush-sports-research/id6774968606) · [Google Play](https://play.google.com/store/apps/details?id=com.linecrush.android) · [ChatGPT](https://chatgpt.com/plugins/plugin_asdk_app_6ad6200f5d308191826093af74536aa2) |
| **SureWord** | Personal Bible study with exact Scripture quotations, an offline KJV reader, synced notes, and user-controlled memory. I built the Next.js web app and backend, Expo/React Native Android app, and SwiftUI apps for iPhone, iPad, and Mac. Free plan with optional Pro. | [Case study](https://www.spragginsdesigns.xyz/work/sureword) · [Web](https://sureword.app) · [Google Play](https://play.google.com/store/apps/details?id=com.spragginsdesigns.sureword) · [App Store](https://apps.apple.com/app/id6820260211) |
| **Gunmetal Orbit** | I designed, developed, and released a commercial space-mining roguelite in Godot for Windows, Linux/Steam Deck, and Apple silicon Macs. I shipped Steam Cloud and 34 achievements, with over 100 post-launch Steam-channel version entries in the changelog. | [Steam](https://store.steampowered.com/app/4975430) · [Changelog](https://games.linecrush.com/gunmetal-orbit/changelog) |

## More of the engineering

- **LineCrush performance.** I profiled Picks in DevTools and cut GPU compositing layers from 360 to 80. One player headshot went from about 238 KB to 3 KB. The March 16, 2026 desktop production snapshot recorded a Vercel Real Experience Score of 100. [Performance case study](https://www.spragginsdesigns.xyz/work/linecrush#platform)
- **LineCrush reliability.** I moved long-running Discord bot work into background workers and fixed a rollout regression in reply delivery. The follow-up passed all 39 database assertions across seven scenarios. I also built off-host backups. A restore recovered a Git checkout with six commits that had never been pushed. [Discord work](https://www.spragginsdesigns.xyz/work/linecrush#integrations) · [Recovery](https://www.spragginsdesigns.xyz/work/linecrush#production)
- **SureWord notes and text scaling.** I made late AI edits respect newer drafts and kept formatting intact across editors. The Android release check recovered an AI edit after an immediate close and reopen. I also built text scaling across clients. The release checks covered narrow web layouts and doubled Android system text. [Notes and accessibility](https://www.spragginsdesigns.xyz/work/sureword#notes-accessibility)

## Recent builds

| Project | What it does | Stack |
| --- | --- | --- |
| [Ghostcount](https://github.com/spragginsdesigns/ghostcount) | Read-only backing check for the NEAR Intents contract. Its replay of a September 2026 incident flags the first unbacked balance 39.8 hours before the problem was identified. Every published claim has a runnable check. [Live dashboard](https://spragginsdesigns.github.io/ghostcount/) | JavaScript, Rust contract, NEAR RPC |
| [Jury Swarm](https://github.com/spragginsdesigns/jury-swarm) | AI judges on their own NEAR accounts rank hackathon entries and stake on their rankings in an on-chain market. Published backtest on six past hackathons, including where it failed. [Live app](https://spragginsdesigns.github.io/jury-swarm/) | JavaScript, Rust contract, LLM APIs |
| [Sideline](https://github.com/spragginsdesigns/sideline) | Fleet-built hackathon prototype for youth sports finances, with invoice and payout flows in the PayPal sandbox | Next.js, PayPal and webhooks |
| [FileSteward AI](https://github.com/spragginsdesigns/filesteward-ai-releases/releases/tag/v0.15.0) | I built an Android file assistant that resumes interrupted work and asks for review when it can't tell whether a move finished. The source for this prerelease has tests for both. | Kotlin, Android |
| [Two Cities Off Road](https://twocitiesoffroad.com/) | I built the live site and an editor the owner can use to update the catalog, gallery, and homepage. The editor shows when the saved version is live. [Live version](https://twocitiesoffroad.com/build.json) | Next.js, Cloudflare Workers and D1 |
| [FormUp](https://github.com/spragginsdesigns/soccer-team-management) | I built a youth-team app with player assessments, schedules, messaging, coach-approved roles, and read-only parent and player portals. [Live web app](https://soccer-team-management-umber.vercel.app/) | Next.js, Convex |
| [Cut Loose](https://spragginsdesigns.itch.io/cut-loose) | I directed the solo Epic AI MegaJam entry and took it from scaffold to Windows release in four days. My first full playthrough found four problems after 85 tests passed. | Unreal Engine 5.8, C++ |
| [Clearline](https://github.com/spragginsdesigns/clearline) | Open-source site for publishing drug-checking results, built for harm reduction | Next.js, Bun |
| [react-steam-deck](https://www.npmjs.com/package/react-steam-deck) | Zero-dependency Steam Deck frame component for React, on npm | TypeScript, SVG |
| [tty7](https://github.com/l0ng-ai/tty7) | Three merged contributions. I added [Kimi Code integration](https://github.com/l0ng-ai/tty7/pull/694), a shortcut to [jump to the agent waiting longest](https://github.com/l0ng-ai/tty7/pull/1164), and a [terminal session-exit fix](https://github.com/l0ng-ai/tty7/pull/877). | Rust |

## How I work

I build with Claude Code and Codex every day. I wrote the skills and workflows our fleet follows to investigate an issue, plan the change, implement it, verify it in the running product, review the diff, and ship. I design tool permissions around the work each agent needs to do. Our public ChatGPT MCP server exposes five read-only research tools, and sensitive decisions stay with a person.

- **Applied AI:** agent orchestration, tool use and MCP servers, multi-model features with validation and fallbacks, retrieval and vector search, vision/OCR, review and proof gates.
- **Product engineering:** TypeScript, React, Next.js, Node.js, Python, PostgreSQL, Redis, REST and real-time systems.
- **Native and games:** SwiftUI, Kotlin/Jetpack Compose, React Native/Expo, Godot, Unreal Engine 5.
- **Delivery:** AWS, Vercel, Docker, Linux, GitHub Actions, and release automation for the App Store, Google Play, and Steam.

[![LineCrush coding activity](https://wakatime.com/badge/github/spragginsdesigns/Context-Pro-AI.svg)](https://wakatime.com/badge/github/spragginsdesigns/Context-Pro-AI)

## Connect

[Portfolio](https://www.spragginsdesigns.xyz) · [Resume](https://www.spragginsdesigns.xyz/resume) · [LinkedIn](https://www.linkedin.com/in/spragginsdesigns/) · [X](https://x.com/spragginsdesign) · [itch.io](https://spragginsdesigns.itch.io/) · spragginsdesigns@gmail.com
