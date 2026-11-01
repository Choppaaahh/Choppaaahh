
# Choppa

Hi! I'm an independent builder-researcher. Reach me on:

- Twitter: [@heychopp](https://x.com/heychopp)
- GitHub Issues: [choppa-research/issues](https://github.com/Choppaaahh/choppa-research/issues)

## Systems:

- [The Harness — system overview](https://github.com/Choppaaahh/choppa-research/blob/main/architecture/system-overview.md): cross-session AI memory + reasoning infrastructure; a fixed model compounding instead of restarting from zero.
- [Memory infrastructure](https://github.com/Choppaaahh/choppa-research/blob/main/architecture/memory-infrastructure.md): the ~4,000-note living knowledge graph + retrieval stack.
- [The autopoietic cycle](https://github.com/Choppaaahh/choppa-research/blob/main/architecture/autopoietic-cycle.md): how the system maintains and improves itself.
- [Governance layer](https://github.com/Choppaaahh/choppa-research/blob/main/architecture/governance-layer.md): commit-gate invariants, proposal queues, and why autonomy is earned.
- [scaffold-harness](https://github.com/Choppaaahh/scaffold-harness): the replicable how-to — the infrastructure layer as a build-it-yourself kit (model-agnostic, markdown-first). Made for sending to your own agents.
- [Getting started](https://github.com/Choppaaahh/choppa-research/blob/main/methodology/getting-started.md): build walkthrough — any LLM that reads markdown.

## Research:

- [Elevation vs. capability](https://github.com/Choppaaahh/choppa-research/blob/main/writeups/elevation-vs-capability-boundary-2026-08.md): where richer instructions substitute for a stronger model (+28pp, pre-registered) — and where they measurably don't. Both failures reported.
- [decorr-eval](https://github.com/Choppaaahh/decorr-eval): runnable benchmark + leaderboard — do your "different" models actually think differently? Judge-free, one API key, ~$1 a run. Headline: you can't infer decorrelation from the lab logo; measure it.
- [Decorrelation co-failure benchmark](https://github.com/Choppaaahh/choppa-research/blob/main/benchmarks/decorrelation-benchmark.md): how often different-lab LLMs all fail the *same* probe. Commit-reveal pre-registered.
- [Pre-registered benchmark freezes](https://github.com/Choppaaahh/choppa-research/blob/main/preregistered_benchmark_freezes.md): hash first, results after — the discipline, in public.
- [Weekly signal pre-registrations](https://github.com/Choppaaahh/choppa-research/blob/main/preregistered_signal_freezes.md): same commit-reveal discipline applied to research predictions.
- [Longitudinal fidelity measurements](https://github.com/Choppaaahh/choppa-research/blob/main/measurements/fidelity_longitudinal.md): does the memory actually survive? Measured, not asserted.

## GPUs and serving:

- [gpu-bunk](https://github.com/Choppaaahh/gpu-bunk): many quiet models on fewer GPUs. An idle model sleeps in host RAM or on a neighbouring GPU and wakes when a request arrives. Open code and every measurement, negative results included.

## Methodology:

- [Agent team design](https://github.com/Choppaaahh/choppa-research/blob/main/methodology/agent-team-design.md): roles, guardrails, and three-layer governance for multi-agent work.
- [Commit-gate invariants](https://github.com/Choppaaahh/choppa-research/blob/main/methodology/commit-gate-invariants.md): 26+ typed checks that run before anything ships.
- [The breadcrumb system](https://github.com/Choppaaahh/choppa-research/blob/main/methodology/breadcrumb-system.md): capture-at-the-moment memory formation.
- [Convergences](https://github.com/Choppaaahh/choppa-research/blob/main/methodology/convergences.md): where our independently-built mechanisms later showed up in the literature.

## Tools:

- [Implementation scripts](https://github.com/Choppaaahh/choppa-research/tree/main/implementation): sanitized, customizable versions of the harness's working parts.
- [sendgrid-mcp-secure](https://github.com/Choppaaahh/sendgrid-mcp-secure): a SendGrid MCP server with recipient allowlists, send caps, a review mode and an audit log.

## Merged upstream:

- DataHub: [#18341](https://github.com/datahub-project/datahub/pull/18341) incident tools for the MCP server, [#19357](https://github.com/datahub-project/datahub/pull/19357) schema-field incidents.
- Microsoft Agent Framework: [#8011](https://github.com/microsoft/agent-framework/pull/8011) stamp the AG-UI checkpoint owner on every save.
- agent-lsp: [#23](https://github.com/blackwell-systems/agent-lsp/pull/23) reject leading-dash git revisions in `detect_changes`.
