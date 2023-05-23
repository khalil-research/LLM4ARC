# LLM-and-ARC
This repository hosts experimental results as described in the paper: **LLMs and the Abstraction and Reasoning Corpus: Successes, Failures, and the Importance of Object-based Representations.**

## Structure
The `output-logs` directory includes two subdirectories, `direct-grid` and `object-based`, each representing different approaches in our experiment. Both contain:

- `ARC-subset`: Results for various prompting methods on the 50 ARC tasks subset, with filenames representing the prompting method as outlined in Table 1 and 3 of our paper.
- `1D-ARC` and `Vertical-Horizontal`: Results for generated tasks using the best performing prompting methods, with filenames based on the generated task types as seen in Table 2 and 4 of our paper.

## Visualization
For a visualization of GPT-4 solutions, visit [our visualizations page](https://xuwil.github.io/GPT-ARC-Visuals/).

## Dataset
The "1D-ARC" dataset used in our experiments is available at this [Github repository](https://github.com/khalil-research/1D-ARC).


