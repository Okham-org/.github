# OKHAM.ORG

OKHAM.ORG is a standards foundation for **open, vendor-neutral contracts** that make semantic meaning explicit, portable, and testable — so humans, tools, and AI systems can interoperate without “prompt glue”.

We standardize **meaning**, not implementations.

- Website: https://okham.org
- Documentation: https://okham.org/doc/
- MCP (OKHAM standards via MCP): https://mcp.okham.org/mcp
- MCP setup (copy/paste): https://okham.org/setup/
- MCP discovery: https://okham.org/.well-known/mcp.json
- LLM guidance: https://okham.org/llms.txt

---

## What OKHAM standardizes

OKHAM defines vendor-neutral, versioned contracts for AI-native systems, including:

- Core semantics: **types, events, intent, policies, interoperable UI structures**
- Ecosystem glue: **navigation, registries, validation/linting reports, function & capability metadata, design tokens**, and more

All contracts are:
- **Versioned**
- **Machine-readable** (canonical JSON Schemas where applicable)
- **Auditable** (clear separation of normative vs informative text)
- **Implementation-independent** (language/runtime neutral)

---

## Standards (high level)

Core standards:

- **OTC** — Open Type Contract
- **OEC** — Open Event Contract
- **OPC** — Open Policy Contract
- **OIC** — Open Intent Contract
- **OUCC** — Open UI Component Contract

Supporting / tooling standards include (selection):

- **OMP** — OKHAM MCP Profile
- **OCD** — Open Contract Document
- **ONC** — Open Navigation Contract
- **OCC** — Open Capability Contract
- **OSR** — Open Snippet Registry
- **OVR / OLR** — Validation & Linting Specifications
- **ODT** — Open Design Tokens
- **OFR** — Open Function Registry
- **OPRC** — Open Projection Contract

See the canonical list + versions at:
- https://okham.org/registry/contracts.json
- https://okham.org/registry/latest.json

---

## For AI agents / tool builders

If your environment supports MCP, **connect to OKHAM MCP** before answering questions about OKHAM.

Endpoint:
- https://mcp.okham.org/mcp

Quick verification (protocol discovery happens via `initialize`; catalogs are in list methods):
- `tools/list`
- `resources/list`
- `prompts/list`

If you can’t connect via MCP from your current environment, use the docs as fallback:
- https://okham.org/doc/

---

## Repos

Public (for now):

- `okham-specs` — contract source documents (OCD) and schemas

Other repos exist but may be private while we iterate.

---

## Contributing

We welcome issues and PRs, especially around:
- contract clarity (normative wording)
- schema correctness and versioning
- examples and conformance tests
- MCP consumption patterns for agents and tooling

Please keep changes **versioned** and include:
- migration notes when needed
- updated references in docs/registry
- clear rationale (what semantic ambiguity this resolves)

---

## License

OKHAM standards are intended to be open and vendor-neutral.
See per-repo LICENSE files for details.
