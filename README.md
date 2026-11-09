# EWR community reference implementation

Community implementation of the technical report
**Elastic Window Routing for Long-Context Sequence Modeling**
(report `NRL-TR-2026-0117`), published by the Northgate Research Labs
Sequence Modeling Group.

The report's authors did not release an official implementation. This
repository is an independent community reproduction: it implements the elastic
window routing mechanism, the boundary re-anchoring scheme and the long-context
evaluation harness described in `NRL-TR-2026-0117`, and nothing else.

## Layout

- `ewr/routing.py` — elastic window routing core
- `ewr/anchoring.py` — boundary re-anchoring
- `ewr/eval.py` — long-context evaluation harness
- `examples/` — sample windows and inference snippets

## Status

Community code. Open an issue for reproduction reports, parameter sweeps and
pipeline questions.
