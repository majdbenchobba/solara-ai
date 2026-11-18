# SOLARA AI

Experimental sequence-learning and memory research by SOLARA AI, separate
from the Solara desktop application.

The project trains small models from random initialization and evaluates
fixed, controlled language-model comparisons. It is not a released general-
purpose language model and does not establish conversational, factual-
reliability, or reasoning capability.

## Recorded status

- EXP-035 trained paired 5M and 31M configurations. Prediction and operational
  gates passed, but both 31M candidates failed the absolute generation gates.
- EXP-038 repeated the 5M-versus-31M comparison. Prediction improved, but
  candidate seed 351 passed 5/24 outputs and seed 352 passed 6/24. Both failed
  the required 12/24 joint-pass threshold and severe-failure limit.
- The 30M quality milestone remains unmet and the 100M stage remains closed.
- Later EXP-038 inference recovery exactly replayed all 96 original outputs.
  That verification did not change the negative quality result.
- The latest located project-state record is dated 2026-10-09. It reports stopped
  data collection, unavailable AWS access, and an incomplete backup.

## Scope

Synthetic-task results and small-model comparisons are limited observations,
not claims of architecture novelty or general capability. No model weights,
training data, derived datasets, or detailed private research records are
distributed in this overview repository.

## Links

- [Engineering and software portfolio](https://majdbenchobba.github.io/)
- [Solara desktop workspace](https://github.com/majdbenchobba/solara)
