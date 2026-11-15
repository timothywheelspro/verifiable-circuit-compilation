# Run log

One row per experiment. "Model" = which AI made the change, and why that one.
Cost = the task's own cost from its verifier. Score = leaderboard score, if submitted.

| Date | Task | Change | Verifier | Cost before | Cost after | Score | Model (why) | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-11-14 | all | Sample submission, unchanged (baseline check) | official metric: pass | — | — | 1.00000 | none (no AI used) | First submission; notebook4f94a7bd66 v1, 70 MiB zip |
| 2026-11-14 | invsqrt | Measured the sample circuit with the local verifier (no change) | pass (770 s, default shots) | 2,076,774.23 | — | — | none (no AI used) | 260 qubits × 7,987.59 Toffoli-equivalents (7,735 Toffolis, 37 rotations, 1 T); worst error 0.477 of tolerance |
