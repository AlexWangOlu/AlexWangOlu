<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=760&lines=I+build+the+unseen+half+of+FiveM;Qbox+%C2%B7+ox_inventory+%C2%B7+ox_lib;Lua+%2B+TypeScript+for+live+servers" alt="typing" />

# Alex

**FiveM systems engineer.** I build the part of a roleplay server that nobody photographs but everybody feels: inventory pipelines, phone ecosystems, whitelist plumbing, prop interactions, and the bridges that stop third-party resources from fighting each other.

<sub>中文 RP 服务器的底层系统开发 —— Qbox / ox_inventory / ox_lib，Lua 与 TypeScript 双线。</sub>

<br/>

<img src="https://img.shields.io/badge/FiveM-server%20systems-blueviolet?style=for-the-badge" />
<img src="https://img.shields.io/badge/Qbox-core-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/ox__inventory-items-2C2D72?style=for-the-badge" />
<img src="https://img.shields.io/badge/NUI-CEF%20%2B%20React-61DAFB?style=for-the-badge" />
<img src="https://img.shields.io/badge/zh--CN-localization-critical?style=for-the-badge" />

<br/>
<br/>

<img src="https://skillicons.dev/icons?i=lua,ts,js,nodejs,react,tailwind,mysql,redis,git,linux,docker,vscode&theme=dark" alt="stack" />

</div>

---

## What I actually build

| | Layer | What that means in practice |
|:--:|---|---|
| 🧩 | **Server systems** | Qbox resources in Lua: jobs, economy, whitelist queues, admin tooling, server-authoritative checks |
| 📱 | **Phone ecosystems** | Integrating burner phones, MDTs, radios and dispatch into one coherent player experience |
| 🎛️ | **NUI / CEF front-ends** | React + TypeScript panels that render inside CEF without dropping frames — custom props, live state, no jank |
| 🔌 | **Bridges** | Framework-agnostic adapters: Qbox / QBCore / ESX × ox_inventory / qb-inventory × ox_target / qb-target |
| 🗃️ | **Ops & tooling** | Node sync portals, MySQL migrations, Windows-to-Linux build pipelines for a 48-slot live server |

---

## Production systems

Running right now on a live Chinese-language Qbox server. **The code is private** — these are production resources on an active server, not portfolio pieces. I am happy to walk through any of them: architecture, screenshots, or a screen share.

| System | What it does | Stack |
|---|---|---|
| **speedtrailer** | Towable radar speed trailer with a folding LED sign and police-side controls | Lua |
| **Yes_radioPro** | Police / EMS radio on a custom APX 6000 prop, channel and zone logic included | Lua · JS |
| **yes_radialmenu** | Radial menu rebuilt around Qbox instead of a generic fork | Lua · HTML |
| **yes-local-sync-portal** | Local whitelist sync, KOOK claim flow and community portal integration | TypeScript · Lua |
| **ulc-mz-sync** | Proximity sync layer for a lighting controller across multiple machines | Lua · TS |
| **yes-club** | Bartending, venue management and social roleplay venue loop | Lua · HTML |
| **yes_lean** | Configurable consumable RP with visual effects and an addiction extension hook | Lua |
| **yes-namebadges** | Name plates on a purpose-built low-poly native prop | Lua |
| **bodycam (AXON 4)** | Bodycam NUI overlay with an offline test harness | JavaScript |
| **arsk-skin-lab** | Cinematic bilingual storefront | TypeScript · Next.js |

---

## Open work

| Repo | Role |
|---|---|
| **[sd-trapphone](https://github.com/AlexWangOlu/sd-trapphone/tree/zh-CN)** | Full Simplified Chinese localization — 308-key locale pack, rewritten dialogue, CJK font handling. Opened upstream as **[PR #1](https://github.com/Samuels-Development/sd-trapphone/pull/1)** |
| **[sd-phone](https://github.com/AlexWangOlu/sd-phone)** | Chinese localization and maintenance of the phone resource (TypeScript + Lua, ~5 MB Lua alone) |
| **[api-enhanced](https://github.com/AlexWangOlu/api-enhanced)** | Maintained revival of NeteaseCloudMusicApi — half refactored, still serving |
| **[liangxueyasi](https://github.com/AlexWangOlu/liangxueyasi)** | IELTS practice platform, Next.js + TypeScript |

---

## Currently

- Pushing the `sd-trapphone` localization upstream and keeping the branch rebased
- Wiring `ox_inventory` item definitions into a phone ecosystem so ten handset colours behave as ten distinct items with their own metadata
- Turning a Windows-side asset pipeline into something that survives a Linux production box

---

<div align="center">

<img src="https://komarev.com/ghpvc/?username=AlexWangOlu&style=flat-square&color=58A6FF&label=PROFILE+VIEWS" alt="views" />
<img src="https://img.shields.io/badge/server-48%20slots-2ea44f?style=flat-square" />
<img src="https://img.shields.io/badge/timezone-UTC%2B8-informational?style=flat-square" />

<sub>Most of my work lives in private repositories — if something here looks relevant to you, open an issue and say hi.</sub>

</div>
