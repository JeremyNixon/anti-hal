# Anti-HAL

![Anti-HAL](src/HKdOi58X0AAg2qw.png)

## Coding Infrastructure

- GitHub repository
- Likely move this to the AGI House GitHub organization if we host a hackathon around contributing to this.

## NerfEval

A dataset of prompts that get nerfed by Fable.

- Use performance comparisons to Opus 4.8 to evaluate this.
- Create a dataset of tasks for evaluation. ML Bench comes to mind.
- Design question: task level or prompt level?
- Feature space for prompts:
  - Embeddings
  - Other textual features

## Product

A Claude Code harness that runs a classifier on prompts before routing requests to either Opus 4.8 or Fable based on whether they are likely to be nerfed.

The result is similar to Claude Code's behavior on bio tasks, where it falls back to Opus 4.8, but applied to AI research tasks.
