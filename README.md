# Thalis Antunes

Computer engineer in Brazil. I build the plumbing between AI agents and
real-world systems: MCP servers for network gear, EDA tools and government
APIs, and the hardware, networks and machines around them.

**Contact:** [contato@thalisantunes.com.br](mailto:contato@thalisantunes.com.br) · [LinkedIn](https://www.linkedin.com/in/thalis-antunes/) · [thalisantunes.com.br](https://thalisantunes.com.br/)

## MCP servers

| Repo | What it does |
|---|---|
| [mcp-kicad](https://github.com/thalisantunes/mcp-kicad) | KiCad 10 over the IPC API and kicad-cli, with JLCPCB fabrication rules built in. v0.3.0 adds `validate`: a stage-gated, read-only review graph (ERC → DRC → fab rules → Gerbers) with graded findings, `next_actions.json` and JUnit output for CI. |
| [mcp-openscad](https://github.com/thalisantunes/mcp-openscad) | Parametric CAD with OpenSCAD: generate, render and export for laser cutting, 3D printing and CNC. |
| [mcp-freecad](https://github.com/thalisantunes/mcp-freecad) | Headless FreeCAD: inspection, STEP/STL/3MF/DXF/SVG export and fabrication scripts. |
| [mcp-mikrotik](https://github.com/thalisantunes/mcp-mikrotik) | MikroTik RouterOS 6/7. 100+ read tools, guarded writes, dead-man rollback so a bad change never locks you out. Verified on real PtP links. |
| [mcp-omada](https://github.com/thalisantunes/mcp-omada) | TP-Link Omada SDN controllers. Read-only monitoring plus one guarded write, verified against a real OC200. |
| [govbr-apis-mcp](https://github.com/thalisantunes/govbr-apis-mcp) | Spec-driven gateway that exposes Brazilian government APIs as a handful of generic tools instead of hundreds. |

## Open source contributions

Bugs I hit while using these projects, fixed upstream. Each logo links to the merged pull requests on GitHub.

<a href="https://github.com/search?q=is%3Apr+is%3Amerged+author%3Athalisantunes+org%3Akirodotdev&type=pullrequests"><img src="https://github.com/kirodotdev.png?size=80" width="40" height="40" alt="Kiro (AWS): 2 merged pull requests" title="Kiro (AWS): 2 merged pull requests"></a>&nbsp;
<a href="https://github.com/search?q=is%3Apr+is%3Amerged+author%3Athalisantunes+org%3AAdyen&type=pullrequests"><img src="https://github.com/Adyen.png?size=80" width="40" height="40" alt="Adyen: 1 merged pull request" title="Adyen: 1 merged pull request"></a>&nbsp;
<a href="https://github.com/search?q=is%3Apr+is%3Amerged+author%3Athalisantunes+user%3AVibra-Ingenn&type=pullrequests"><img src="https://github.com/Vibra-Ingenn.png?size=80" width="40" height="40" alt="Vibra Ingenn: 1 merged pull request" title="Vibra Ingenn: 1 merged pull request"></a>

| Repository | Pull request |
|---|---|
| [kirodotdev/KiroCrew](https://github.com/kirodotdev/KiroCrew) (Kiro, by AWS) | [fix(i18n): translate the command palette action titles](https://github.com/kirodotdev/KiroCrew/pull/25760) |
| | [fix(i18n): translate 18 English passthrough values in pt and es for Design Critique](https://github.com/kirodotdev/KiroCrew/pull/26065) |
| [Adyen/agent-marketplace](https://github.com/Adyen/agent-marketplace) | [Read comma-separated subagent tool strings as separate tools](https://github.com/Adyen/agent-marketplace/pull/925) |
| [Vibra-Ingenn/Janus](https://github.com/Vibra-Ingenn/Janus) | [Fix Linux support: by-value struct ABI, pinned llama.cpp b11146, stack-safe C buffers](https://github.com/Vibra-Ingenn/Janus/pull/2) |

## Claude Code tooling

- [local-ultrareview](https://github.com/thalisantunes/local-ultrareview): multi-model ensemble code review skill. Lenses are split by evidence source, findings are graded by how they were verified, and the orchestrator audits the report instead of adding opinions.

## Bench

- CO2 laser with my own machine controller, FDM printing on a Sovol SV08 MAX (ASA, vase mode, field brackets), a Raspberry Pi CM5 field router with 5G failover over Starlink.
- Embroidery: a 10-needle Brother and [Ink/Stitch](https://github.com/thalisantunes/inkstitch), where I am starting to contribute.
- Boards I use and keep public forks of: [RoboCore Vespa](https://github.com/thalisantunes/RoboCore_Vespa) and [Franzininho WiFi LAB01](https://github.com/thalisantunes/Franzininho-WiFi-LAB01-ESP-IDF).

## Talks

- Latinoware, speaker since 2012. 2026: [RAG over the talks and speakers](https://github.com/thalisantunes/latinoware-2026-rag) (Weaviate, Ollama, faster-whisper; pt/en/es).
- EECri 2026 (Nova Porteirinha, MG): [AI and the maker lab for craft work](https://github.com/thalisantunes/eecri-2026-ia-artesanato), talk and workshop, all material open.

## Elsewhere

- Day job: engineering lead at a ticketing and live-events platform. Access control, turnstiles, high-throughput check-in.
- Site: [thalisantunes.com.br](https://thalisantunes.com.br/), a bench you fly over. pt-BR, en, es.
