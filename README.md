# Rahim Iqbal

I'm interested in the part of AI-for-science that starts after a model says
something plausible.

Can the claim be checked? Can it fail cleanly? Can it be repaired? Can part of
it be made formal?

The cleanest place to start is
[`claim-checking-trace-lab`](https://github.com/abdulrahimiqbal/claim-checking-trace-lab):
a small repo where I am keeping the trail from claim to check to result.

Two current traces:

- Trace 001: bounded Kerr horizon claim -> numeric sanity checks -> Lean
  proof-status check.
- Trace 002: overbroad Kerr claim -> missing discriminant assumption -> repaired
  theorem -> Lean check.

The repos below are different pieces of the same question: generate candidates,
test them, and keep enough evidence that someone else can inspect the result.

## Start Here

### Central Trace

[`claim-checking-trace-lab`](https://github.com/abdulrahimiqbal/claim-checking-trace-lab)

This is where the traces live. They are intentionally small: one claim, one
check, what passed or broke, and what still isn't proved.

Trace 001:

```txt
AI-selected Kerr horizon claim
-> deterministic numeric sanity check
-> Lean proof check
-> explicit proof boundary
```

Trace 002:

```txt
overbroad Kerr claim
-> failed discriminant assumption
-> repaired theorem
-> Lean check with explicit assumption
```

### Generate

[`aristotle_new_orchestrator`](https://github.com/abdulrahimiqbal/aristotle_new_orchestrator)

LLM-driven Lean/Aristotle research orchestration.

First-click sample campaign:
[`docs/sample_campaign_erdos_44.md`](https://github.com/abdulrahimiqbal/aristotle_new_orchestrator/blob/main/docs/sample_campaign_erdos_44.md)

### Test

[`OpenAtoms`](https://github.com/abdulrahimiqbal/OpenAtoms)

A reproducibility layer for AI-driven science and empirical research loops.

First-five-minutes trace:
[`examples/first_five_minutes.py`](https://github.com/abdulrahimiqbal/OpenAtoms/blob/main/examples/first_five_minutes.py)

### Verify

[`KerrFormalization`](https://github.com/abdulrahimiqbal/KerrFormalization)

Lean/formalization work around Schwarzschild and Kerr black-hole geometry.

Proof-status map:
[`PROOF_STATUS.md`](https://github.com/abdulrahimiqbal/KerrFormalization/blob/main/PROOF_STATUS.md)

First checked claim:

```lean
KerrFormalization.Kerr.outerHorizonIsDeltaRoot
```

## Contact

- Website: https://rahimiqbal.com
- X: https://x.com/ariqbalkhan
- LinkedIn: https://www.linkedin.com/in/rahim-iqbal/
- Substack: https://rahimiqbal.substack.com/
