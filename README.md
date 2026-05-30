<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,40:9333ea,100:ec4899&height=240&section=header&text=&fontSize=0&animation=twinkling" width="100%" alt=""/>

</div>

<table border="0">
<tr>
<td width="280" align="center" valign="middle">
<img src="./assets/mascot/unicorn-south.png" width="240" alt="" style="image-rendering:pixelated"/>
</td>
<td valign="middle">

# fasad · CTO @ [solafon](https://solafon.com)

<a href="https://github.com/FasadSalatov">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=600&color=EC4899&center=false&vCenter=false&multiline=false&width=620&lines=building+MCP+marketplaces+for+Claude;shipping+AI+agents+that+close+tickets+on+their+own;deploying+via+my+own+webhook+server+%E2%80%94+no+GitHub+Actions;baking+kawaii+glass+aesthetics+into+production" alt=""/>
</a>

`Next.js 16` · `Drizzle` · `Tailwind 4` · `Claude Agent SDK` · `Rust` · `TON · EVM` · `Node · Bun · Go`

<br/>

<a href="https://unyly.org"><img src="https://img.shields.io/badge/✦_unyly.org-7c3aed?style=for-the-badge&labelColor=0a0a0f" alt="unyly"/></a>
<a href="https://t.me/Fasad_Salatov"><img src="https://img.shields.io/badge/✦_telegram-ec4899?style=for-the-badge&labelColor=0a0a0f" alt="telegram"/></a>
<a href="mailto:salatiksama@gmail.com"><img src="https://img.shields.io/badge/✦_mail-9333ea?style=for-the-badge&labelColor=0a0a0f" alt="email"/></a>
<a href="https://github.com/FasadSalatov?tab=followers"><img src="https://img.shields.io/github/followers/FasadSalatov?style=for-the-badge&logo=github&labelColor=0a0a0f&color=7c3aed&label=followers" alt=""/></a>
<img src="https://komarev.com/ghpvc/?username=FasadSalatov&style=for-the-badge&color=ec4899&label=PROFILE+VIEWS&labelColor=0a0a0f" alt=""/>

</td>
</tr>
</table>

<div align="center">

> _11 years shipping commercial software. I take products from idea to production — full-stack, AI agents, on-chain, infra._
> _Current focus — the **MCP ecosystem** and **agents that close their own tickets**._

<br/>

<img src="./assets/mascot/unicorn-west.png" width="64" alt="" style="image-rendering:pixelated"/>&nbsp;&nbsp;
<img src="./assets/mascot/unicorn-south.png" width="64" alt="" style="image-rendering:pixelated"/>&nbsp;&nbsp;
<img src="./assets/mascot/unicorn-east.png" width="64" alt="" style="image-rendering:pixelated"/>

`web · agents · on-chain`

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ featured · [unyly.org](https://unyly.org)

<table border="0">
<tr>
<td width="240" align="center" valign="top">

<a href="https://unyly.org">
<img src="./assets/mascot/unicorn-east.png" width="200" alt="unyly mascot" style="image-rendering:pixelated"/>
</a>

<br/>

<img src="https://img.shields.io/badge/LIVE-ec4899?style=for-the-badge&labelColor=0a0a0f" alt=""/>

</td>
<td valign="top">

### MCP marketplace for Claude · Cursor · Cline

A full ecosystem around the **Model Context Protocol** — catalog, search, install, converter, agents, billing. One of the largest public indexes of MCP servers on the web.

```
✦ 11,700+  MCP servers in catalog
✦ 41       tables in schema (Drizzle + SQLite)
✦ 425+     TS files · 31 migrations
✦ 5        ingest sources (registry · npm · glama · pulsemcp · smithery)
✦ 2        locales · 22 AI crawlers in robots.txt
```

**Inside:** AI search with a Gemini → Groq → Haiku cascade · **Brain Boards** with real-time WebSocket and time-machine · **Vault** as a notes graph with `[[wiki-links]]` · **OpenAPI → MCP** converter · **Trello live-sync** via webhooks · **NOWPayments** crypto billing with a double-entry ledger · public API · CLI with device-code flow · Telegram bot.

</td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ AI agents on the Claude Agent SDK

> Bots that read Trello / GitHub / logs, **spawn `claude --print` inside your repo**, close tickets, report to Telegram and write your standup.

<table border="0">
<tr>
<td width="80" align="center"><img src="./assets/icons/tester-relay.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Tester-Relay</b><br/><sub>pull ticket → run tests → on red, spawn a fixer agent → repush → notify</sub></td>
<td width="80" align="center"><img src="./assets/icons/mcp-discovery.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>MCP-Discovery</b><br/><sub>crawls npm / awesome / github every 4h → embed → dedupe → upsert into the catalog</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/daily-standup.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Daily-Standup</b><br/><sub>reads my commits + Linear → drops a morning standup to Telegram, calls out blockers</sub></td>
<td align="center"><img src="./assets/icons/cross-project-digest.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Cross-Project-Digest</b><br/><sub>weekly: aggregates activity across 7+ repos into one digest for CEO / investors</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/pr-reviewer.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>PR-Reviewer</b><br/><sub>auto-reviews every PR — security · perf · clean code · DB schema · MCP compatibility</sub></td>
<td align="center"><img src="./assets/icons/prod-incident.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Prod-Incident</b><br/><sub>sentry/logs → greps the code → opens a fix PR → pings whoever wrote the failing line</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/zombie-hunter.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Zombie-Hunter</b><br/><sub>scans repos for dead code, forgotten migrations, deprecated ENV → PR to delete</sub></td>
<td align="center"><img src="./assets/icons/ai-inbox.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>AI-Inbox</b><br/><sub>reads mail / chats / messengers → classifies, answers 80%, escalates the rest</sub></td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ other lanes

<table border="0">
<tr>
<td valign="top" width="33%">

### 🪙 on-chain / MEV
- **DEX arbitrage** on EVM via `viem` + Flashbots relays (sandwich-resistant)
- **TON** — DEX routers, mini-acquiring, jetton swaps
- **Liquidators** for Aave / Compound / Venus
- **Signals** — whale-wallet monitoring, on-chain analytics

</td>
<td valign="top" width="33%">

### 🛰 Telegram products
- **Mini Apps** on Next.js + WebApp SDK
- **Stars payments** + crypto inbound
- **Game monetization** (Cookie Wars, NERV, partner bots)
- **Bots** scaled to 100k+ MAU, sharded PostgreSQL

</td>
<td valign="top" width="33%">

### 🚀 deploy infra
- One **webhook server** on a single VPS serving **7+ production projects**
- `git push prod` → atomic `.next.new` swap → pm2 restart
- AI failure triage via Haiku → Telegram
- No GitHub Actions, no Vercel lock-in

</td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,nextjs,react,tailwind,nodejs,bun,go,rust,python,solidity,postgres,sqlite,redis,docker,kubernetes,nginx,linux,bash,git,github&perline=10" alt=""/>

</div>

<table border="0">
<tr>
<td valign="top" width="50%">

**core / web**
- TypeScript · Python · Rust · Go · Solidity
- Next.js 16 · React 19 · Tailwind 4 · radix
- Node · Bun · NestJS · FastAPI · Hono
- PostgreSQL · SQLite (Drizzle) · Redis · WebSocket

</td>
<td valign="top" width="50%">

**ai · web3 · infra**
- Claude Agent SDK · LLM cascade · RAG · MCP
- viem · TON · Flashbots · NOWPayments
- Docker · k8s · nginx · PM2 · systemd
- own webhook deploy server (no GH Actions)

</td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ stats

<div align="center">

<a href="https://github.com/FasadSalatov">
<img height="180" src="https://github-readme-stats.vercel.app/api?username=FasadSalatov&show_icons=true&count_private=true&include_all_commits=true&theme=synthwave&hide_border=true&bg_color=0a0a0f&title_color=ec4899&icon_color=7c3aed&text_color=c0c0c0&ring_color=ec4899" alt=""/>
<img height="180" src="https://github-readme-streak-stats.herokuapp.com?user=FasadSalatov&theme=synthwave&hide_border=true&background=0a0a0f&stroke=ec4899&ring=ec4899&fire=7c3aed&currStreakLabel=ec4899" alt=""/>
</a>

<br/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FasadSalatov&layout=compact&theme=synthwave&hide_border=true&bg_color=0a0a0f&title_color=ec4899&text_color=c0c0c0&langs_count=10" alt=""/>
<img height="180" src="https://github-profile-trophy.vercel.app/?username=FasadSalatov&theme=radical&no-frame=true&no-bg=true&column=4&row=2&margin-w=8&margin-h=8" alt=""/>

<br/>
<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=FasadSalatov&bg_color=0a0a0f&color=ec4899&line=7c3aed&point=ec4899&area_color=9333ea&area=true&hide_border=true&custom_title=contribution+graph" width="100%" alt=""/>

</div>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ what I believe

<table border="0">
<tr>
<td valign="top" width="50%">

**🛠 fewer abstractions, longer-lived code**
- No layer for the sake of a layer, no interface for a single impl, no wrapping the std lib without a reason.

**⚡ deploys should be boring**
- `git push prod` and you're done. No human in the loop, no hand-rolled yaml, no Vercel lock-in.

**🤖 the routine belongs to the agent**
- Standups, code review, incidents, MCP server dedupe — Claude already does this. I just wire the pipes.

</td>
<td valign="top" width="50%">

**🎨 aesthetic, but never at the cost of DX**
- Kawaii pixel art, glass UI, gradient brand — but not for the price of a 200ms LCP. One SVG beats ten `<div>`s.

**🔒 secrets never live in the repo**
- `.env` + `.env.local` + vault. Bot tokens, keys, prod configs — server environment only.

**🌍 your own VPS is cheaper and faster**
- 7 production projects on one $20/mo VPS outrun the same stack on $400/mo serverless.

</td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ work together

| | |
|---|---|
| **🛠 custom development** | Next.js · Go · Rust. MVP in 2-3 weeks, production in 6-8. Fixed-price or T&M. |
| **🤖 AI agents for your workflow** | Claude-based automation of the routine. Trello → GitHub / DevOps / support / sales. |
| **🧠 CTO consulting** | Architecture, stack picks, hiring your first team, due diligence. First 30 min call on me. |
| **🪙 on-chain / MEV** | DEX arbitrage, liquidators, MEV bots on EVM and TON. NDA before the deal. |

<div align="center">

<br/>

<a href="https://t.me/Fasad_Salatov"><img src="https://img.shields.io/badge/💬_ping_me_on_telegram-@Fasad__Salatov-ec4899?style=for-the-badge&labelColor=0a0a0f" alt="telegram"/></a>
<a href="mailto:salatiksama@gmail.com"><img src="https://img.shields.io/badge/✉_email-salatiksama@gmail.com-7c3aed?style=for-the-badge&labelColor=0a0a0f" alt="email"/></a>
<a href="https://unyly.org"><img src="https://img.shields.io/badge/🦄_unyly.org-9333ea?style=for-the-badge&labelColor=0a0a0f" alt="unyly"/></a>

<br/>
<br/>

> _«ship · iterate · automate»_

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ec4899,50:9333ea,100:7c3aed&height=120&section=footer&fontSize=0" width="100%" alt=""/>

</div>
