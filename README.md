# Thalis Antunes

Computer engineer in Brazil. I build the plumbing between AI agents and
real-world systems: MCP servers for network gear, EDA tools and government
APIs, and the hardware, networks and machines around them.

## MCP servers

| Repo | What it does |
|---|---|
| [mcp-kicad](https://github.com/thalisantunes/mcp-kicad) | KiCad 10 over the IPC API and kicad-cli, with JLCPCB fabrication rules built in. v0.3.0 adds `validate`: a stage-gated, read-only review graph (ERC → DRC → fab rules → Gerbers) with graded findings, `next_actions.json` and JUnit output for CI. |
| [mcp-openscad](https://github.com/thalisantunes/mcp-openscad) | Parametric CAD with OpenSCAD: generate, render and export for laser cutting, 3D printing and CNC. |
| [mcp-freecad](https://github.com/thalisantunes/mcp-freecad) | Headless FreeCAD: inspection, STEP/STL/3MF/DXF/SVG export and fabrication scripts. |
| [mcp-mikrotik](https://github.com/thalisantunes/mcp-mikrotik) | MikroTik RouterOS 6/7. 100+ read tools, guarded writes, dead-man rollback so a bad change never locks you out. Verified on real PtP links. |
| [mcp-omada](https://github.com/thalisantunes/mcp-omada) | TP-Link Omada SDN controllers. Read-only monitoring plus one guarded write, verified against a real OC200. |
| [govbr-apis-mcp](https://github.com/thalisantunes/govbr-apis-mcp) | Spec-driven gateway that exposes Brazilian government APIs as a handful of generic tools instead of hundreds. |

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
