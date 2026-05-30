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
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2600&pause=600&color=EC4899&center=false&vCenter=false&multiline=false&width=620&lines=строю+MCP-маркетплейсы+для+Claude;пишу+AI-агентов+которые+делают+рутину+сами;деплою+на+свой+webhook-сервер+%E2%80%94+без+GitHub+Actions;катаю+kawaii+glass-эстетику+в+продакшен" alt=""/>
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

> _11 лет в коммерческой разработке. Веду продукты от идеи до прод-деплоя — full-stack, AI-агенты, on-chain, инфра._
> _Сейчас фокус — **MCP-экосистема** и **агенты, которые сами закрывают тикеты**._

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

### MCP marketplace для Claude · Cursor · Cline

Полная экосистема вокруг **Model Context Protocol** — каталог, поиск, установка, конвертер, агенты, биллинг. Один из крупнейших публичных индексов MCP-серверов в мире.

```
✦ 11 700+  MCP-серверов в каталоге
✦ 41       таблица в схеме (Drizzle + SQLite)
✦ 425+     TS-файлов · 31 миграция
✦ 5        источников ingest (registry · npm · glama · pulsemcp · smithery)
✦ 2        локали · 22 AI-краулера в robots.txt
```

**Внутри:** AI-поиск с каскадом Gemini → Groq → Haiku · **Brain Boards** с real-time WebSocket и time-machine · **Vault** как граф заметок с `[[wiki-links]]` · **OpenAPI → MCP** конвертер · **Trello live-sync** через webhooks · **NOWPayments** crypto-billing с double-entry ledger · публичный API · CLI с device-code flow · Telegram-бот.

</td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ AI-агенты на Claude Agent SDK

> Боты, которые читают Trello / GitHub / логи, **спавнят `claude --print` в твоём репо**, и сами закрывают тикеты, репортят в Telegram, пишут стендапы.

<table border="0">
<tr>
<td width="80" align="center"><img src="./assets/icons/tester-relay.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Tester-Relay</b><br/><sub>pull тикет → запустить тесты → если пада́ют, спавнить агента-фиксера → repush → notify</sub></td>
<td width="80" align="center"><img src="./assets/icons/mcp-discovery.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>MCP-Discovery</b><br/><sub>краулит npm/awesome/github каждые 4 часа → embed → дедуп → upsert в каталог</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/daily-standup.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Daily-Standup</b><br/><sub>читает мои коммиты + Linear → пишет стендап утром в Telegram, выделяет блокеры</sub></td>
<td align="center"><img src="./assets/icons/cross-project-digest.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Cross-Project-Digest</b><br/><sub>раз в неделю агрегирует активность 7+ репо в один дайджест для CEO/инвесторов</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/pr-reviewer.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>PR-Reviewer</b><br/><sub>авто-ревью каждого PR — security · perf · clean code · схема БД · MCP-совместимость</sub></td>
<td align="center"><img src="./assets/icons/prod-incident.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Prod-Incident</b><br/><sub>sentry/logs → грепает код → пишет PR с фиксом → пингует автора падающей строки</sub></td>
</tr>
<tr>
<td align="center"><img src="./assets/icons/zombie-hunter.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>Zombie-Hunter</b><br/><sub>сканит репо на мёртвый код, забытые миграции, deprecated ENV → PR на удаление</sub></td>
<td align="center"><img src="./assets/icons/ai-inbox.png" width="60" alt="" style="image-rendering:pixelated"/></td>
<td><b>AI-Inbox</b><br/><sub>читает почту/чаты/мессенджеры → классифицирует, отвечает на 80%, эскалирует остальное</sub></td>
</tr>
</table>

<br/>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:7c3aed,100:ec4899&height=2&section=header" width="100%" alt=""/>
</div>

## ✦ что ещё строю

<table border="0">
<tr>
<td valign="top" width="33%">

### 🪙 on-chain / MEV
- **DEX-арбитраж** на EVM через `viem` + Flashbots-релэи (sandwich-resistant)
- **TON** — DEX-роутеры, мини-эквайринг, jetton-обмены
- **Ликвидаторы** для Aave / Compound / Venus
- **Сигналы** — мониторинг whale-кошельков, on-chain analytics

</td>
<td valign="top" width="33%">

### 🛰 Telegram-продукты
- **Mini Apps** на Next.js + WebApp SDK
- **Stars payments** + crypto inbound
- **Игровая монетизация** (Cookie Wars, NERV, partner-боты)
- **Боты** масштабом до 100k+ MAU, sharded PostgreSQL

</td>
<td valign="top" width="33%">

### 🚀 deploy-инфра
- Свой **webhook-сервер** на одном VPS (216.57.105.103:3001) обслуживает **7+ продов**
- `git push prod` → atomic swap `.next.new` → pm2 restart
- AI-разбор фейлов через Haiku → Telegram
- Никаких GitHub Actions, никаких Vercel-локов

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
- Claude Agent SDK · LLM-cascade · RAG · MCP
- viem · TON · Flashbots · NOWPayments
- Docker · k8s · nginx · PM2 · systemd
- own webhook-deploy server (no GH Actions)

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

## ✦ во что я верю

<table border="0">
<tr>
<td valign="top" width="50%">

**🛠 чем меньше абстракций — тем дольше живёт код**
- Не пишу слой ради слоя, не делаю интерфейс для одного имплемента, не оборачиваю std lib без причины.

**⚡ деплой должен быть скучным**
- `git push prod` — и всё. Никакого человека в цикле, никаких ручных yaml'ов, никаких Vercel-локов.

**🤖 рутину должен делать агент**
- Стендапы, code review, инциденты, дедуп MCP-серверов — всё это уже умеет делать Claude. Я просто соединяю провода.

</td>
<td valign="top" width="50%">

**🎨 эстетика не дороже DX**
- kawaii пиксель-арт, glass UI, gradient brand — но не ценой 200ms LCP. Один SVG лучше десяти `<div>`-ов.

**🔒 secrets никогда не в репо**
- `.env` + `.env.local` + vault. Bot-токены, ключи, prod-конфиги — только в окружении сервера.

**🌍 свой VPS дешевле и быстрее**
- 7 продакшен-проектов на одном VPS за $20/мес работают быстрее, чем тот же стек на serverless за $400.

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
| **🛠 заказная разработка** | Next.js · Go · Rust. MVP за 2-3 недели, прод за 6-8. Fixed-price или T&M. |
| **🤖 AI-агенты под workflow** | Claude-based автоматизация рутины. Trello → GitHub / DevOps / support / sales. |
| **🧠 CTO-консалтинг** | Архитектура, стек, найм первой команды, due diligence. Первый звонок 30 мин бесплатно. |
| **🪙 on-chain / MEV** | DEX-арбитраж, ликвидаторы, MEV-bots на EVM и TON. NDA до сделки. |

<div align="center">

<br/>

<a href="https://t.me/Fasad_Salatov"><img src="https://img.shields.io/badge/💬_напиши_в_telegram-@Fasad__Salatov-ec4899?style=for-the-badge&labelColor=0a0a0f" alt="telegram"/></a>
<a href="mailto:salatiksama@gmail.com"><img src="https://img.shields.io/badge/✉_email-salatiksama@gmail.com-7c3aed?style=for-the-badge&labelColor=0a0a0f" alt="email"/></a>
<a href="https://unyly.org"><img src="https://img.shields.io/badge/🦄_unyly.org-9333ea?style=for-the-badge&labelColor=0a0a0f" alt="unyly"/></a>

<br/>
<br/>

> _«ship · iterate · automate»_

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ec4899,50:9333ea,100:7c3aed&height=120&section=footer&fontSize=0" width="100%" alt=""/>

</div>
