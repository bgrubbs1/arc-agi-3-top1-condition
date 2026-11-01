# ARC-AGI-3 — Top-1-condition submission

This folder contains a submission-ready Kaggle notebook and kernel metadata.

- Notebook: `arc-agi-3-top1.ipynb`
- Kaggle kernel metadata: `kernel-metadata.json`
- Target competition: `arc-prize-2026-arc-agi-3`
- Hardware: `NvidiaRtxPro6000`
- Internet: disabled

The notebook is built from the strongest public lineage available locally:

- Daniel Franzen’s Milestone 2 stack
- Lalalia’s cache-safe solved-level memory patch
- The no-op repeat guard, enabled with `ARC3_NOOP_REPEAT_GUARD=1`
- The existing priority scheduler, persistent-function support, and action/death guards

It is validated as a standard Notebook Format 4 document. Kaggle entry is currently blocked by the platform’s new-entrant deadline, so this artifact is ready to push or submit the moment that gate is lifted.

**Current Kaggle status:** The support request has been submitted. Kaggle still returns `userHasEntered: false` and rejects kernel push with `You must accept this competition's rules before you'll be able to add it as a datasource: arc-prize-2026-arc-agi-3`. The new-entrant deadline shown by the API is `2026-10-26 23:59 UTC`, while the final deadline is `2026-11-02 23:59 UTC`.
