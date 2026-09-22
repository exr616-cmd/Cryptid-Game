# NOCTURNE COUNTY — V27 Playthrough QA / Integrity

V27 is the first dedicated end-to-end QA harness pass after the V25 Ultimate target and V26 stabilization.

It adds a non-invasive integrity smoke test for the accumulated runtime: required core APIs, state containers, cryptid registry coverage, localStorage availability, JSON state serialization, and renderer availability.

To expose the QA panel during local play, open `index.html?qa=1` and click **Run integrity smoke test**.

This layer is intentionally non-destructive: it does not rewrite the player's save or alter the active story state.
