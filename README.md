<p align="center">
  <img src="assets/portrait.svg" width="440" alt="ASCII-art portrait of Eashan Babber">
</p>

<h1 align="center">Eashan Babber</h1>

<p align="center">
  <b>Robotics Engineering student</b> · UC Santa Cruz<br>
  <b>Software Engineer</b> · <a href="https://goldtickets.com">GoldTickets</a> (playDTC)<br>
  <sub>Contributor to <a href="https://github.com/meta/pyrefly">pyrefly</a> · <a href="https://github.com/kevinpbuckley/VibeUE">VibeUE</a> · <a href="https://github.com/garrytan/gbrain">gbrain</a></sub>
</p>

<p align="center"><i>I am drawn to building systems that solve real-world problems, bring people together into a community, or simply put a smile on someone's face.</i></p>

---

## Without AI

I don't use AI for schoolwork. Doing that work by myself is really important to me, because I believe the more I understand on my own, the better ideas I will have.

**Currently learning** · Fall 2026

- Python · CSE 20
- Calculus II · MATH 19B

**Learning path** · planned

| Winter 2027 | Spring 2027 |
| --- | --- |
| Computer systems and assembly · CSE 12 | Systems programming in C · CSE 13S |
| Mechanics · PHYS 5A | Linear algebra · AM 10 |
| | Discrete math · CSE 16 |

## With AI

Outside of schoolwork, I use AI to learn, as a teacher that explains things rather than giving me the answers, and to bring my ideas to life.

| Principle | Where it shows |
| --- | --- |
| **Measure, don't assume** | The first suspected cause of [pyrefly #4647](https://github.com/meta/pyrefly/pull/4647) was ruled out by testing before the real fix. VibeUE skill routing was measured at 100% accuracy, smaller models included ([#502](https://github.com/kevinpbuckley/VibeUE/pull/502), [#516](https://github.com/kevinpbuckley/VibeUE/pull/516)). |
| **Give agents real tools** | A locally patched pyrefly language server, so agents navigate code by type information instead of text search. That work sent two fixes upstream ([#4643](https://github.com/meta/pyrefly/pull/4643), [#4647](https://github.com/meta/pyrefly/pull/4647)). |
| **One memory across agents** | [gbrain](https://github.com/garrytan/gbrain) is the shared knowledge base behind every agent I run, and I fix it upstream when it breaks. |
| **Report what actually happened** | Every status below says what landed and how. Closed is not the same as rejected, and adopted is not the same as merged. |

**Coding agents I actively use:** Claude Code · Codex · Hermes

## Open source

| Project | What I did |
| --- | --- |
| **[pyrefly](https://github.com/meta/pyrefly)**<br><sub>Meta's Python type checker · 7.2k★</sub> | Fixed type-hierarchy queries missing subtypes declared in other modules ([#4647](https://github.com/meta/pyrefly/pull/4647)), and limited the expensive full-analysis step to the requests that actually read the AST ([#4643](https://github.com/meta/pyrefly/pull/4643)). Both landed on `main` ([`f8b724b`](https://github.com/meta/pyrefly/commit/f8b724b90), [`5bec107`](https://github.com/meta/pyrefly/commit/5bec107f7)). |
| **[VibeUE](https://github.com/kevinpbuckley/VibeUE)**<br><sub>AI agent tooling for Unreal Engine · 810★</sub> | 5 PRs merged. Restored typed Blueprint member-variable creation ([#504](https://github.com/kevinpbuckley/VibeUE/pull/504)) and built the skill-routing dispatcher ([#502](https://github.com/kevinpbuckley/VibeUE/pull/502), [#516](https://github.com/kevinpbuckley/VibeUE/pull/516)). |
| **[gbrain](https://github.com/garrytan/gbrain)**<br><sub>Agent knowledge system · 31.5k★</sub> | Bug fixes adopted into two maintainer fix waves with co-author credit ([v0.46.35](https://github.com/garrytan/gbrain/commit/3464179ce), [v0.48.1](https://github.com/garrytan/gbrain/commit/e9a14c952)). |

## My projects

| Project | What it is |
| --- | --- |
| **[Agent_Efficiency](https://github.com/DarkNightForge/Agent_Efficiency)** | Gives a coding agent usage data that always existed but that it never saw while it worked: exact token counts from its own transcripts, and the vendor's usage meter from the status line. It knows your burn rate, warns before a big task that won't fit, and says when there's room to go wide. Codex port by [@Eclipse1231317](https://github.com/Eclipse1231317). |
| **[eashans-claude-mods](https://github.com/DarkNightForge/eashans-claude-mods)** | Claude Code mods I build as I need them. First: tui-diagrams, which draws Mermaid, PlantUML and HTML widgets as pictures inline in the terminal. |

## Professional work

**[GoldTickets](https://goldtickets.com)** · playDTC · Software Engineer · since September 2026

- Took the React Native app to Android as a native build, not a wrapper around the site, and tested it on a real device.
- Built sign-up attribution: every account records the link that brought it, feeding a growth-channels view and creator codes.
- Hardened delivery: a deploy watch that files an issue when a green commit never ships, faster CI, and security fixes in dependencies.

<sub>Private repository · 52 merged pull requests</sub>

---

<p align="center"><code>~/links</code> &nbsp; <a href="https://eashanbabber.com">Portfolio</a> · <a href="https://github.com/DarkNightForge">GitHub</a> · <a href="https://www.linkedin.com/in/eashanbabber/">LinkedIn</a> · <a href="mailto:eashan@babber.com">eashan@babber.com</a></p>

<p align="center"><sub>Star and pull-request counts as of November 2026.</sub></p>
