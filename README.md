# Gemma 4 Developer Agent: preregistration log

This repository holds timestamped predictions, decision rules (as hash commitments) and configuration commitments for our entry in the Kaggle "Google - The Gemma 4 Developer Agent Competition" and its paper track. Git commit times are the timestamps.

**Rules:**

- **When entries are written.** A prediction is committed before the submission it predicts. A hypothesis is committed before any data that tests it is examined.
- **No edits.** Entries are never edited after a result is known. Results are added as new commits that reference the original entry.
- **Commit-reveal.** Configurations and full hypothesis texts are published here only as SHA-256 hashes until the competition ends on 2026-12-02. The texts and archives that produce these hashes will be published after that date.
- **What is not here.** This repository contains no competition data and no solution code.

**Files:**

- `predictions/`: one file per board submission, with the archive hash, submission reference, point prediction and 80% interval.
- `commitments.md`: SHA-256 hashes of the full preregistered hypothesis texts (H1 to H4) and of configuration archives.
- `results.md`: scored outcomes, appended as they arrive, each linked to its prediction.
