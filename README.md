# Austin Spraggins

**Co-Founder & CTO at LineCrush · Product engineering, applied AI, and developer tools**

I'm an expert at directing AI agents. I know how to brief them properly, how to review their work, and when to stop one that's headed the wrong way. I built LineCrush's self-sustaining, self-improving AI engineering fleet and C2, our replacement for Linear.

I started the LineCrush codebase in 2024, and Jay and I grew it into a paid sports research product. I built real-time delivery for research and alerts, led the live auth migration across web and mobile, automated backend releases, and shipped our ChatGPT integration.

I started both native apps from scratch and wrote their first month of code in SwiftUI and Kotlin with Jetpack Compose. I kept coding after launch, including updates to the research cards across all three clients and on-device answer narration on iOS. The fleet I built has written most of the later feature code. I own releases and store review for both apps.

The fleet rarely needs a person to step in. As of November 17, 2026, it had completed **14,111 jobs**, including **10,745 with a recorded commit link**. I led the move from Linear to C2 and brought over roughly **19,000 historical issues** while active work kept moving. [LineCrush engineering case study](https://www.spragginsdesigns.xyz/work/linecrush)

I created SureWord and shipped the web, Android, iPhone, iPad, and Mac apps myself. I built the Scripture retrieval that supplies exact verse text to the AI, the memory controls that let readers decide what carries into their next study, and one membership across Stripe, Apple, and Google Play. SureWord has a free plan and optional Pro. New accounts were up in the first 18 days of November 2026 compared with the same period in October. [SureWord engineering case study](https://www.spragginsdesigns.xyz/work/sureword)

I took Gunmetal Orbit from its first playable loop to Steam in 67 days. I'm based in Fresno, California. [My resume](https://www.spragginsdesigns.xyz/resume)

## Shipped

| Product | What it is | Where |
| --- | --- | --- |
| **Agent fleet and C2** | AI engineering fleet that takes work from investigation through release, with C2 tracking the issue, the work, and the evidence. | [Fleet and C2 case study](https://www.spragginsdesigns.xyz/work/linecrush#c2) |
| **LineCrush** | Sports research platform with a Next.js and TypeScript web app, Python data services, PostgreSQL, Redis, and a ChatGPT integration built on MCP. I wrote the foundations of the SwiftUI iOS and Kotlin/Jetpack Compose Android apps and took both through store review and release. | [Web](https://www.linecrush.com) · [App Store](https://apps.apple.com/us/app/linecrush-sports-research/id6774968606) · [Google Play](https://play.google.com/store/apps/details?id=com.linecrush.android) · [ChatGPT](https://chatgpt.com/plugins/plugin_asdk_app_6ad6200f5d308191826093af74536aa2) |
| **SureWord** | Personal Bible study with exact Scripture quotations, an offline KJV reader, synced notes, and user-controlled memory. I built the Next.js web app and backend, Expo/React Native Android app, and SwiftUI apps for iPhone, iPad, and Mac. Free plan with optional Pro. | [Case study](https://www.spragginsdesigns.xyz/work/sureword) · [Web](https://sureword.app) · [Google Play](https://play.google.com/store/apps/details?id=com.spragginsdesigns.sureword) · [App Store](https://apps.apple.com/app/id6820260211) |
| **Gunmetal Orbit** | Revenue-generating Godot space combat and mining game for Windows, macOS, and Linux/Steam Deck, with regular updates since its September 2026 release | [Steam](https://store.steampowered.com/app/4975430) |

## Recent builds

| Project | What it does | Stack |
| --- | --- | --- |
| [Ghostcount](https://github.com/spragginsdesigns/ghostcount) | Read-only backing check for the NEAR Intents contract. Its replay of a September 2026 incident flags the first unbacked balance 39.8 hours before the problem was identified. Every published claim has a runnable check. [Live dashboard](https://spragginsdesigns.github.io/ghostcount/) | JavaScript, Rust contract, NEAR RPC |
| [Jury Swarm](https://github.com/spragginsdesigns/jury-swarm) | AI judges on their own NEAR accounts rank hackathon entries and stake on their rankings in an on-chain market. Published backtest on six past hackathons, including where it failed. [Live app](https://spragginsdesigns.github.io/jury-swarm/) | JavaScript, Rust contract, LLM APIs |
| [Sideline](https://github.com/spragginsdesigns/sideline) | Fleet-built hackathon prototype for youth sports finances, with invoice and payout flows in the PayPal sandbox | Next.js, PayPal and webhooks |
| [Cut Loose](https://spragginsdesigns.itch.io/cut-loose) | Third-person chase game built solo in four days for the Epic AI MegaJam | Unreal Engine 5.8, C++ |
| [Clearline](https://github.com/spragginsdesigns/clearline) | Open-source site for publishing drug-checking results, built for harm reduction | Next.js, Bun |
| [react-steam-deck](https://www.npmjs.com/package/react-steam-deck) | Zero-dependency Steam Deck frame component for React, on npm | TypeScript, SVG |
| [tty7](https://github.com/l0ng-ai/tty7/pull/877) | Contributed a terminal fix that stops sending input after a session exits. | Merged upstream |

## How I work

I build with Claude Code and Codex every day. I wrote the skills and workflows our fleet follows to investigate an issue, plan the change, implement it, verify it in the running product, review the diff, and ship. I design tool permissions around the work each agent needs to do. Our public ChatGPT MCP server exposes five read-only research tools, and sensitive decisions stay with a person.

- **Applied AI:** agent orchestration, tool use and MCP servers, multi-model features with validation and fallbacks, retrieval and vector search, vision/OCR, review and proof gates.
- **Product engineering:** TypeScript, React, Next.js, Node.js, Python, PostgreSQL, Redis, REST and real-time systems.
- **Native and games:** SwiftUI, Kotlin/Jetpack Compose, React Native/Expo, Godot, Unreal Engine 5.
- **Delivery:** AWS, Vercel, Docker, Linux, GitHub Actions, and release automation for the App Store, Google Play, and Steam.

[![LineCrush coding activity](https://wakatime.com/badge/github/spragginsdesigns/Context-Pro-AI.svg)](https://wakatime.com/badge/github/spragginsdesigns/Context-Pro-AI)

## Connect

[Portfolio](https://www.spragginsdesigns.xyz) · [Resume](https://www.spragginsdesigns.xyz/resume) · [LinkedIn](https://www.linkedin.com/in/spragginsdesigns/) · [X](https://x.com/spragginsdesign) · [itch.io](https://spragginsdesigns.itch.io/) · spragginsdesigns@gmail.com
