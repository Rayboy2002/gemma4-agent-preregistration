# Results

| Prediction | Submission ref | Predicted (80% interval) | Result | Recorded (UTC) |
|---|---|---|---|---|
| predictions/2026-10-15-B0-1.md | 57199782 | 7 (5 to 9) | 0.12 (7 of 58) | 2026-10-16 |

## Registered checks

| Check | Plan commitment | Verdict | Key numbers | Recorded (UTC) |
|---|---|---|---|---|
| L0 LoRA logit check (lora-l0-logit-v1, kernel version 18) | efb0bf91 (commit 7ca8b2a) | INCONCLUSIVE: effect-to-noise precondition failed (0.70, required 3.0) | delta r 0.771 (not gated); base agreement r 0.998; 16 of 16 prompts scored; vLLM LoRA repeats not deterministic (up to 0.28 nats) while base repeats were identical | 2026-10-16 |
