Coding Infrastructure:
Github Repository
Will likely move this to the AGI House github organization if we host a hackathon around contributing to this.

NerfEval:
Dataset of prompts which get nerfed by Fable
Use performance comparison to Opus 4.8 to evaluate this
Create a dataset of tasks on which to attempt to evaluate this (ML Bench jumps to mind)
Design question: Task level or Prompt level?
Feature space for the prompts:
Embeddings?


Consider other textual features.

Product:
A Claude Code harness (LMAO we could use the leak) that runs a classifier on prompts before routing the request either to Opus 4.8 or Fable based on whether or not it is going to be nerfed.
Result - replicating the behavior of claude code on bio (where there’s a dropback to Opus 4.8) for AI research tasks.

