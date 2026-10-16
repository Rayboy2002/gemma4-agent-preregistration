# Results

| Prediction | Submission ref | Predicted (80% interval) | Result | Recorded (UTC) |
|---|---|---|---|---|
| predictions/2026-10-15-B0-1.md | 57199782 | 7 (5 to 9) | 0.12 (7 of 58) | 2026-10-16 |

## Registered checks

| Check | Plan commitment | Verdict | Key numbers | Recorded (UTC) |
|---|---|---|---|---|
| L0 LoRA logit check (lora-l0-logit-v1, kernel version 18) | efb0bf91 (commit 7ca8b2a) | INCONCLUSIVE: effect-to-noise precondition failed (0.70, required 3.0) | delta r 0.771 (not gated); base agreement r 0.998; 16 of 16 prompts scored; vLLM LoRA repeats not deterministic (up to 0.28 nats) while base repeats were identical | 2026-10-16 |
| Concurrency bench (concurrency-bench-v1, kernel version 19) | 8392d379 (commit 12b6075) | VALID. Design A (3-way parallel repair): DROPPED. Two-branch designs: NOT ALIVE | agent-turn slowdown 1.11 at 2 streams (90% CI 1.07 to 1.15) and 1.34 at 3 (1.22 to 1.38); level-1 drift -0.7%; no errors or preemptions; aborted requests stop decoding | 2026-10-16 |
