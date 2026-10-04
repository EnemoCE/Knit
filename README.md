# Knit (Knowledge Integrator)

A long-lived research agent with a working notebook (Topic 14).

## Description

Knit is an LLM agent that helps conduct research across multiple sessions: it collects materials, extracts claims with sources and dates, and maintains an up-to-date summary of the topic.

The working notebook is organized into several layers: source excerpts, linked claims, and current conclusions. When new materials arrive, the agent flags contradictions and updates its conclusions while preserving a history of changes. It answers questions using sources and reveals the original excerpts when needed.

Quality is evaluated on research histories with known facts, corrections, and contradictions. Correctness, freshness, cost, and latency are measured against simple note-taking approaches.

## Licensing

Knit follows an open-core model, with genuinely open-source components.

| Component | License |
| --- | --- |
| `.warch` specification | [CC0-1.0](LICENSES/CC0-1.0.txt) |
| SDK, CLI, MCP client, PageSpec types, and reference domain packs | [Apache-2.0](LICENSES/Apache-2.0.txt) |
| Fully functional single-user / self-hosted server | [AGPL-3.0-only](LICENSES/AGPL-3.0-only.txt) |
| Hosted multi-tenant cloud, billing, managed connectors, collaboration, and premium research engine | Proprietary; distributed separately |
| Knit name and logo | Separate [trademark policy](TRADEMARKS.md) |

Apache-2.0 for the SDK reduces integration friction. AGPL-3.0 for the server enables self-hosting and requires operators of modified versions to offer the corresponding source code to users who interact with those versions over a network. Commercial hosting is allowed under the license.

Commercial server licenses may be offered in the future to enterprise partners that need an alternative to AGPL, subject to the necessary rights from copyright holders.

This repository currently contains the project description and licensing documents. The table describes the licensing model for the planned components. See [LICENSE.md](LICENSE.md) for license scope and the default license.
