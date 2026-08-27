<!--
  ═══════════════════════════════════════════════════════════════════════════
   MrFrostDev / README.md  —  GitHub Profile README

   This repo is named exactly like the account, which is why GitHub renders this
   file at the top of https://github.com/MrFrostDev

   OPSEC: nothing here describes private work. No private repo names, no project
   descriptions, no working-hours card, and no tool badge specific enough to point
   at a particular private project. Skills and subject areas only.

   TO EDIT: search for "TODO" to find the parts only you can fill in.
   To change the card theme, swap the folder name in the stats URLs below.
  ═══════════════════════════════════════════════════════════════════════════
-->

<div align="center">

<!--
  The banner is a file in this repo (assets/header.svg), not a live call to
  capsule-render. That service runs on a free Vercel instance, and every URL change
  forces GitHub's camo proxy to refetch the image - which fails often enough to
  leave a broken header. A committed file cannot break that way, and the animation
  lives inside the SVG so it still runs.

  WARNING, BUG IN capsule-render: an "&" in text= or desc= is written into the SVG
  UNESCAPED. The result is invalid XML, and browsers parse an SVG inside <img> with
  a strict XML parser -> broken image, no error message anywhere.
  So pass "&" as "%26amp%3B" (the XML entity &amp;), not as "%26".
  Always validate after regenerating:
      python -c "import xml.dom.minidom;xml.dom.minidom.parse('assets/header.svg')"

  To regenerate (change type, colours or text, then save):
  curl -o assets/header.svg "https://capsule-render.vercel.app/api?type=waving\
  &color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=MrFrost\
  &fontSize=70&fontColor=ffffff&fontAlignY=35&descAlignY=58&descSize=18\
  &desc=Full-Stack%20Development%20%E2%80%A2%20AI%20Tooling%20%E2%80%A2%20Automation\
  &animation=fadeIn"
  Types: rect slice blur egg waving soft cylinder venom shark transparent speech
  Animations: fadeIn blinking scaleIn twinkling   (there is no "round" type!)
-->
<img
  src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/assets/header.svg"
  alt="MrFrost"
/>

<a href="https://github.com/MrFrostDev">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=4FC3F7&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B+I'm+MrFrost;Full-stack+developer+%26+tooling+builder;Web+%E2%80%A2+Mobile+%E2%80%A2+Backend+%E2%80%A2+AI;C+%E2%80%A2+Shell+%E2%80%A2+Java+%E2%80%A2+JavaScript+%E2%80%A2+Kotlin"
    alt="Typing SVG"
  />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=MrFrostDev&label=Profile%20views&color=4FC3F7&style=flat-square" alt="Profile views" />
<img src="https://img.shields.io/badge/GitHub%20since-2017-4FC3F7?style=flat-square&logo=github&logoColor=white" alt="On GitHub since 2017" />
<img src="https://img.shields.io/badge/focus-tooling%20%26%20AI-203a43?style=flat-square" alt="Focus" />

</div>

---

## 🧊 About Me

**Full-stack developer** — product engineering, internal tooling and AI integration.

🧩 &nbsp;**Product & platform**<br/>
Web and mobile front ends in TypeScript, React, Next.js and Flutter, backed by Node
services and relational data. APIs, authentication and deployment included.

⚙️ &nbsp;**Tooling & automation**<br/>
Generators, pipelines and internal services that turn recurring manual work into a single
command. Built to run locally, with the operator in control.

🧠 &nbsp;**AI integration**<br/>
Retrieval with embeddings and vector search, tool-calling and agent workflows, and MCP
servers that expose data and actions to a model in a controlled, auditable way.

🤝 &nbsp;**Open to**<br/>
Contract work, and joint commissions as a development duo.

<sub>Game-server development — Arma Reforger, FiveM, alt:V — is where I started, and still ships
occasionally. Most public repos here are archived releases from that period, so the language
stats below show where I have been more than where I am now.</sub>

---

## 🛠️ Tech Stack

<!--
  One #### heading per category, with that category's badges underneath.
  Alphabetical inside each category. Currently 55 badges:

      Languages 20 · Web & App 7 · AI 8
      Data & Protocols 8 · Game Dev 9 · Tools 3

  Every badge links to the official page for that technology.

  Inside a category there must be NO blank line and NO HTML comment between the
  badge lines. Either one splits the paragraph and stacks the badges vertically
  instead of side by side. A plain line break is fine in a README - GitHub does
  not turn those into <br> the way it does in comments.
-->


#### Languages

[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://en.cppreference.com/w/c)
[![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![C++](https://img.shields.io/badge/C%2B%2B-004482?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![EnforceScript](https://img.shields.io/badge/EnforceScript-6E4B9E?style=for-the-badge)](https://community.bistudio.com/wiki/Arma_Reforger:Scripting)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![HPP](https://img.shields.io/badge/HPP-34495E?style=for-the-badge)](https://community.bistudio.com/wiki/Class_Config_Reference)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://dev.java/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://www.lua.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Shell](https://img.shields.io/badge/Shell-89E051?style=for-the-badge&logo=shell&logoColor=black)](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html)
[![SQF](https://img.shields.io/badge/SQF-3C4F76?style=for-the-badge)](https://community.bistudio.com/wiki/SQF_Syntax)
[![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://www.swift.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

#### Web & App

[![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)](https://vuejs.org/)

#### AI

[![AI Agents](https://img.shields.io/badge/AI%20Agents-6E4B9E?style=for-the-badge)](https://en.wikipedia.org/wiki/Intelligent_agent)
[![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/claude)
[![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge)](https://openai.com/codex/)
[![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)](https://gemini.google.com/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![MCP](https://img.shields.io/badge/MCP-1F1F1F?style=for-the-badge)](https://modelcontextprotocol.io/)
[![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)](https://ollama.com/)
[![RAG & Embeddings](https://img.shields.io/badge/RAG%20%26%20Embeddings-2E8B57?style=for-the-badge)](https://en.wikipedia.org/wiki/Retrieval-augmented_generation)

#### Data & Protocols

[![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge)](https://grpc.io/)
[![JSON-RPC](https://img.shields.io/badge/JSON--RPC-2E3440?style=for-the-badge)](https://www.jsonrpc.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![REST / OpenAPI](https://img.shields.io/badge/REST%20%2F%20OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white)](https://www.openapis.org/)
[![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge)](https://en.wikipedia.org/wiki/SQL)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge)](https://developer.mozilla.org/docs/Web/API/WebSockets_API)

#### Game Dev

[![alt:V](https://img.shields.io/badge/alt%3AV-00A8E8?style=for-the-badge)](https://altv.mp/)
[![Arma 3](https://img.shields.io/badge/Arma%203-5A6E2A?style=for-the-badge&logo=bohemiainteractive&logoColor=white)](https://arma3.com/)
[![Arma Reforger](https://img.shields.io/badge/Arma%20Reforger-4A5D23?style=for-the-badge&logo=bohemiainteractive&logoColor=white)](https://reforger.armaplatform.com/)
[![Enfusion](https://img.shields.io/badge/Enfusion%20Workbench-2E4053?style=for-the-badge)](https://enfusionengine.com/)
[![FiveM](https://img.shields.io/badge/FiveM-F40552?style=for-the-badge&logo=fivem&logoColor=white)](https://fivem.net/)
[![Garry's Mod](https://img.shields.io/badge/Garry's%20Mod-1F5A8C?style=for-the-badge&logo=sourceengine&logoColor=white)](https://gmod.facepunch.com/)
[![Minecraft](https://img.shields.io/badge/Minecraft-52A535?style=for-the-badge)](https://www.minecraft.net/)
[![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)](https://unity.com/)
[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)](https://www.unrealengine.com/)

#### Tools

[![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)](https://www.blender.org/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)


---

## 📊 GitHub Stats

<!--
  These cards are generated into THIS repo by .github/workflows/summary-cards.yml
  (folder profile-summary-card-output/), so they do not depend on anyone else's
  Vercel quota - github-readme-stats currently returns 503 and
  github-profile-trophy returns 402.

  To change the theme, swap the folder name below. Available themes include:
  tokyonight · dracula · radical · gruvbox · monokai · nord_dark · github_dark
  2077 · vue · solarized · zenburn · transparent · default

  The "productive-time" card is deliberately NOT embedded: it publishes which
  hours of the day work happens.
-->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/tokyonight/0-profile-details.svg" />
  <img src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/default/0-profile-details.svg" alt="Profile details" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/tokyonight/3-stats.svg" />
  <img width="32%" src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/default/3-stats.svg" alt="Stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/tokyonight/1-repos-per-language.svg" />
  <img width="32%" src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/default/1-repos-per-language.svg" alt="Repos per language" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/tokyonight/2-most-commit-language.svg" />
  <img width="32%" src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/profile-summary-card-output/default/2-most-commit-language.svg" alt="Most commit language" />
</picture>

</div>

---

## 🤝 Trusted Collaborator

<!--
  Any badges added here must sit on ONE line. An HTML comment placed between them
  splits the paragraph into two <p> elements, which stacks them vertically instead
  of side by side. That is also why this comment is up here rather than between
  the badges.

  <small> is stripped by GitHub's sanitizer, <sub> survives - hence <sub> for the
  small text.

  Name and tagline live together in ONE <h3>, separated only by <br/>. As two
  separate blocks (heading plus its own paragraph) the block margin pushes them
  apart, and style="margin:0" is no fix because GitHub strips style attributes
  outright. A shared element is the only way to get the tagline to sit directly
  under the name.
-->

<h3>
  <a href="https://github.com/maxionice">maxionice</a><br/>
  <sub>Full-stack developer, building tools for gaming, AI and everyday use.</sub>
</h3>

A long-standing collaborator and the one external developer with a permanent place on
this profile. For suitable commissions the two of us are available together as a
development duo.

<a href="https://github.com/maxionice"><img src="https://img.shields.io/badge/maxionice-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="maxionice on GitHub" /></a>

---

## 🌐 Connect

<div align="center">

<a href="https://github.com/MrFrostDev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<!-- TODO: more contact channels if wanted - uncomment the lines below.
     Keep them on adjacent lines with no comment in between, otherwise the
     paragraph splits and the badges stack vertically.
<a href="https://www.youtube.com/@YOUR_CHANNEL"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
<a href="mailto:YOU@EXAMPLE.COM"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
-->

</div>

<div align="center">

<!-- Also a committed file, see the comment above the header.
     curl -o assets/footer.svg "https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" -->
<img src="https://raw.githubusercontent.com/MrFrostDev/MrFrostDev/main/assets/footer.svg" alt="" />

</div>
