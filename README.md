
# ARC Prize 2026 – ARC-AGI-2 Submission

This repository contains my solutions and experiments for the ARC Prize 2026 competition on Kaggle.

## About ARC

The Abstraction and Reasoning Corpus (ARC) is a benchmark to evaluate AI’s ability to reason and generalize to novel, human-solvable tasks. ([Epoch AI][1])

## Project Goals

- Learn and implement reasoning-based AI
- Build rule-based and programmatic solvers
- Achieve generalization to unseen ARC tasks

## Progress

- ✅ Joined ARC Prize 2026
- ✅ Built and submitted baseline model (zero output)
- ✅ Upgraded to a simple rule-based model (color mapping)
- ✅ Submission pipeline matches required JSON format
- ✅ Automated format check and output verification

## Tech Stack

- Python 3
- NumPy

## How to Use

1. Run the notebook `arc_baseline_zero_model.ipynb`.
2. The notebook will generate `submission.json` in the required format for Kaggle.
3. (Optional) Use the provided evaluation utilities to test accuracy on the validation set.

## Next Steps

- Add more advanced rule-based and pattern-based reasoning
- Explore program synthesis and learning-based approaches
- Visualize and analyze model predictions

## Insights

ARC is about discovering and applying rules from small examples, not just scaling deep learning. Generalization and reasoning are key. ([GitHub][2])

[1]: https://epoch.ai/benchmarks/arc-agi? "ARC AGI v1 | Epoch AI"
[2]: https://github.com/fchollet/ARC-AGI? "GitHub - fchollet/ARC-AGI: The Abstraction and Reasoning Corpus"
