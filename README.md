# Matt Bordenet

Engineering leader at Microsoft, Amazon, Warner Bros. Discovery (iStreamPlanet), Stash Financial, Telepathy.ai, and now [**Call Box**](https://callbox.com) (remote from Seattle), where I'm leading the team building [Cari Phone Assist](https://www.carwars.com/home/a/cari-phone-assist/), a conversational voice AI for automotive dealerships.

I build AI-native products, reliable platforms, and the engineering organizations that run them, and I still write code.

- **AI-native products:** conversational voice AI in production; earlier, moved Telepathy.ai from a six-year proprietary AI stack to commercial LLMs; [superpowers-plus](https://github.com/bordenet/superpowers-plus) for AI coding agents.
- **Reliability at scale:** 99.99% uptime for live national sports broadcasts, ~90% to 99.9% uptime through a cloud migration, and outages down ~60% in a regulated fintech.
- **Engineering organizations:** led organizations of 35 to 220 engineers, including distributed teams in Singapore and Zurich. How I run them: [Engineering Culture](https://github.com/bordenet/Engineering_Culture).

**Case studies** (problem, decisions, results, and missteps): [Telepathy.ai](https://github.com/bordenet/Transformation_Case_Studies/blob/main/Transformation_Case_Study_TelepathyAI.md) · [Stash](https://github.com/bordenet/Transformation_Case_Studies/blob/main/Transformation_Case_Study_Stash.md) · [iStreamPlanet](https://github.com/bordenet/Transformation_Case_Studies/blob/main/Transformation_Case_Study_iStreamPlanet.md) · [AI-First at Telepathy.ai](https://github.com/bordenet/Transformation_Case_Studies/blob/main/AI-First_Case_Study_TelepathyAI.md)

## What I Do

Along the way:

- **Call Box (Director of Engineering):** We rebuilt the Cari team this past year. It owns its services end to end: its own on-call rotation, dozens of deployments a week instead of big-bang releases, modern DORA metrics to tune how it operates, and written product briefs and a monthly plan of record before we build. More recently, I've started working across the company beyond Cari.
- **Telepathy.ai (VP of Engineering):** Led a 70-person engineering, research, and DevOps organization through a pivot from a six-year proprietary AI stack to commercial LLMs, and an AWS-to-Azure migration with zero customer downtime. Uptime went from ~90% to 99.9% while customers grew from 80 to 220 dealerships.
- **Stash Financial (VP of Engineering, later Interim CTO):** Ran a 220-engineer organization for 2M+ users, holding SOC-2 Type II, FINRA, and FDIC compliance in partnership with the Chief Security Officer and Chief Compliance Officer. With the company's sole SRE, we built an availability program, and outages fell ~60%, from 15 to 6 hours a month.
- **iStreamPlanet (Director of Engineering):** We inherited 60 channels on dedicated hardware with no redundancy. The platform grew to 99.99% uptime across 180+ 24x7 channels and 20+ concurrent live events a night, and Warner Bros. Discovery standardized on it after the acquisition. I also co-founded the live-events business that helped fund the platform work.
- **Amazon (Software Development Manager):** Led SLAM, the real-time shipping-label and package-verification services behind 1B+ packages in 2015. Before that, I led three Prime Video teams (playback, global DRM, concurrency enforcement) while it grew from ~10M to 40M users.
- **Microsoft (Principal Development Manager):** Engineering manager for the Windows Media DRM, Windows client, and Silverlight teams. We ran the breach response when attackers compromised Microsoft's DRM stack.
- **U.S. Army (Signal Corps officer):** Where I first learned servant leadership.

## Current Focus

Writing about engineering leadership and building AI-assisted development tools. Projects below.

## Projects

### superpowers-plus

**[superpowers-plus](https://github.com/bordenet/superpowers-plus)** - 124 skills that make AI coding assistants follow engineering practices they would otherwise skip (root-cause debugging, design alternatives, parallel code review, verification), backed by lifecycle hooks and git commit gates that run outside the model. Full support for Claude Code and Augment Code; skills for Codex, OpenCode, and MCP clients. Extends [obra/superpowers](https://github.com/obra/superpowers). This is where nearly all of my public-repo time goes.

### More AI Tooling

- **[golden-agents](https://github.com/bordenet/golden-agents)** - Self-maintaining AI guidance files. Generates `AGENTS.md` with a 250-line threshold and automatic module extraction: when files grow past the limit, the AI refactors its own instructions into topic-specific modules without human intervention.
- **[scripts](https://github.com/bordenet/scripts)** - Bash toolkit for macOS and Linux: git workflows, system automation, security tools, and dev environment setup. CI-enforced quality standards.
- **[docforge-ai](https://github.com/bordenet/docforge-ai)** - Business documents drafted through adversarial AI review: Claude drafts, Gemini critiques, Claude synthesizes. Supports 9 document types. **[Try it](https://bordenet.github.io/docforge-ai/)**

### Other Tools

- **[bloginator](https://github.com/bordenet/bloginator)** - Blog generation using RAG to synthesize content from your existing writing corpus. Hybrid semantic search (ChromaDB + BM25), pattern-based slop detection, voice matching. Python CLI, Streamlit UI, FastAPI server. Supports Ollama, OpenAI, and Anthropic.
- **[secrets-in-source](https://github.com/bordenet/secrets-in-source)** - Fast concurrent scanner for detecting secrets in source control.
- **[apple-quartile-solver](https://github.com/bordenet/apple-quartile-solver)** - Multi-interface solver for Apple News Quartile puzzles.
- **[ZoomBackgroundMagick](https://github.com/bordenet/ZoomBackgroundMagick)** - Shell scripts using ffmpeg to convert panoramic images into scrolling video backgrounds and create slideshows for Zoom.

### Applications

- **[RecipeArchive](https://github.com/bordenet/RecipeArchive)** - Full-stack recipe manager with web, iOS, and Android support.
- **[identity-deep-dive](https://github.com/bordenet/identity-deep-dive)** - OAuth2/OIDC authorization server with security scanners and multi-tenant session management.
- **[GameWiki](https://github.com/bordenet/GameWiki)** - Tabletop RPG campaign documentation system for turning session transcripts into searchable wiki pages. [Demo](https://bordenet.github.io/GameWiki/)

### Writing & Case Studies

- **[Engineering_Culture](https://github.com/bordenet/Engineering_Culture)** - Essays on engineering leadership, velocity, and software craft.
- **[Transformation_Case_Studies](https://github.com/bordenet/Transformation_Case_Studies)** - Engineering and organizational transformation case studies with outcomes data.
- **[ai-fundamentals-simple](https://github.com/bordenet/ai-fundamentals-simple)** - Practical AI fundamentals guide for engineering leaders.

---

<p align="center">
<a href="https://www.linkedin.com/in/mattbordenet/" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" height="20"/>
</a> &nbsp;
<a href="https://www.facebook.com/matt.bordenet" target="_blank">
  <img src="https://img.shields.io/badge/-Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook" height="20"/>
</a> &nbsp;
<a href="https://www.instagram.com/mbordenet/" target="_blank">
  <img src="https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" height="20"/>
</a>
</p>

<br/>

<p align="center">
<span title="Seattle">🏙️☕🏔️</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="Vibe coding">💻</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<a href="https://www.goodreads.com/review/list/38562860-matt-bordenet?shelf=professional" title="Reading">📚</a> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="Hiking the PNW">🌲🥾</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="International travel">✈️</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="Football (NFL/Seahawks/UW Huskies)">🏈🦅🐺</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="Mariners">⚾</span> &nbsp;&nbsp;·&nbsp;&nbsp;
<span title="English football (EPL/UCL)">⚽</span>
</p>
