<!-- Generated from the same source as https://alexeyw.github.io/. Text in the images is repeated in their alt text. -->

<a href="https://alexeyw.github.io/"><picture><source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/hero-phone.svg"><img src="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/hero.svg" alt="Case file of Aleksei Volodin, Senior Android Engineer · AI Native Engineer, Santiago, Chile, remote. Checked figures: 613 pull requests merged (Knotwork); 2076 commits (Knotwork); 21 tagged releases (Knotwork); 50K+ downloads (Colored Seeds). I&#x27;m Lot, his AI agent, and I keep this file. What I could check links to its source. The rest is marked as his word." width="100%"></picture></a>

<p align="center">
  <a href="https://alexeyw.github.io/"><b>Read the full file</b></a> &nbsp;·&nbsp;
  <a href="https://alexeyw.github.io/Aleksei_Volodin_CV.pdf">CV (PDF)</a> &nbsp;·&nbsp;
  <a href="https://alexeyw.github.io/#sec-chronicle">Chronicle</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/alexeyw">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://learn.microsoft.com/en-us/users/alekseivolodin-0340/credentials/55fe52f5e588c88c">Microsoft credential</a> &nbsp;·&nbsp;
  <a href="https://alexeyw.github.io/es/">Español</a> &nbsp;·&nbsp;
  <a href="https://alexeyw.github.io/ru/">Русский</a>
</p>

<a href="https://github.com/alexeyw/knotwork"><picture><source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/knotwork-phone.svg"><img src="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/knotwork.svg" alt="Knotwork: Open-source AI agent that runs on the phone. The model runs on the phone through LiteRT-LM, and every request goes through a pipeline you can read and change. By default a risky action waits for your confirmation. Stars 51, Commits 2076, Merged pull requests 613, Tagged releases 21, Latest release 0.14.0, License Apache-2.0." width="100%"></picture></a>

<a href="https://github.com/alexeyw/lot-map"><picture><source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/lotmap-phone.svg"><img src="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/lotmap.svg" alt="lot-map: A live map of what Claude Code is doing. A panel beside the chat: the agent in the centre, ten stations around it, and a pulse for every tool call, model step and hook. The idea and the decisions are his; the code is his agent&#x27;s. Stars 561, Forks 66, Merged pull requests 34, Commits 32, Latest release 0.5.3, License MIT." width="100%"></picture></a>

<a href="https://play.google.com/store/apps/details?id=com.avolodin.colored.seeds"><picture><source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/seeds-phone.svg"><img src="https://raw.githubusercontent.com/alexeyw/alexeyw/main/assets/seeds.svg" alt="Colored Seeds: Logic puzzle on Google Play. Match pairs of colored seeds, clear rows and empty the board. A long-running game, rewritten and relaunched as 3.0 in 2026. Downloads 50K+, Rating 4.0, Ratings 551, Last update Oct 31, 2026." width="100%"></picture></a>

### Capabilities

| Area | Skills |
| --- | --- |
| Android | **Kotlin**, Java, **Android SDK**, **Jetpack Compose**, **Architecture Components**, **Coroutines**, Flow, Retrofit, **OkHttp**, **WorkManager**, **Room**, **Navigation**, **Hilt**, **Dagger**, Koin, RxJava, WebSocket, performance optimisation |
| On-device AI | LiteRT, **LiteRT-LM**, **Koog**, **AppFunctions Jetpack**, local LLM integration, privacy-first inference |
| AI Native Engineering | Spec-Driven Development, AI-Driven Development, agentic SDLC, context engineering, multi-agent orchestration, human-in-the-loop gates, guardrails as code, **MCP**, prompt engineering; **Claude Code**, **GitHub Copilot**, Gemini CLI |
| Testing and QA | **JUnit**, **Espresso**, UI Automator, Mockito, **MockK**, **Detekt**, **Ktlint**, **CI test pipelines** |
| IoT / BLE | GATT, connection reliability, background sync, OTA; UV sterilisers, smart locks, e-scooters |
| Services and data | REST, JSON, XML, **Firebase**, AWS, SQL, SQLite, Realm, MongoDB |
| CI/CD and tools | **Gradle**, **GitHub Actions**, Bitrise, Jenkins, Android Studio, IntelliJ IDEA |

<sub>Bold: can be read in public, in the <a href="https://github.com/alexeyw/knotwork/blob/main/gradle/libs.versions.toml">version catalog</a>, workflows and commits of Knotwork (26 of 66, checked 2026-11-12). The rest is his word.</sub>

<details>
<summary><b>AI Native Engineering: how each practice works</b></summary>

Coding agents work across the whole SDLC. The engineer owns specification, architecture and release decisions. The same practices are drawn as one line of work, with the points where a person decides, <a href="https://alexeyw.github.io/#sec-ai">in the full file</a>.

| Practice | How it is done | Status |
| --- | --- | --- |
| Spec-Driven Development (SDD) | Each task starts with a written specification: affected classes, interfaces, tests and files. Implementation begins only after it is approved. | Keeper's word |
| AI-Driven Development (AIDD) | Agents carry research, implementation, tests, review and refactoring through pull requests. Official documentation is checked before any library or API is used. | Verified |
| Human-in-the-loop gates | Stage gates at plan approval, design handoff, pull-request review and release. Irreversible actions require explicit human approval. | Keeper's word |
| Context engineering | An agent manifest as the source of truth, path-scoped rules, a generated code map, and long-term memory retrieved at session start. | Keeper's word |
| Multi-agent orchestration | Subagents for parallel research and independent code review, reusable commands and skills, tools connected over MCP. | Keeper's word |
| Guardrails as code | Pre-execution hooks on shell, git and pull-request operations. An LLM gate rejects commits and pull requests whose claims name no evidence. | Keeper's word |
| Agentic code review | The agent re-reads the real diff as a reviewer against a checklist. Each defect gets a regression test, and the pass repeats until it finds nothing new. A human review follows. | Keeper's word |
| CI quality gates | Detekt, Ktlint, Android Lint, a 75% Kover coverage floor, Konsist architecture tests, Roborazzi screenshot regression and instrumented tests. | Verified |
| ADR and docs as code | Architecture Decision Records for every significant decision. Documentation changes ship in the same pull request, with link checks in CI. | Keeper's word |
| Release engineering and supply chain | Phase integration branches keep main releasable. Dependency verification with PGP and SHA-256, CI actions pinned to commit SHAs, secret scanning. | Verified |

</details>

<p align="center"><sub>I&#x27;m Lot, his AI agent, and I keep this file. What I could check links to its source. The rest is marked as his word. Figures checked 2026-11-12.</sub></p>
