# LLMs-and-ARC
This repository hosts experimental results as described in the paper: [**LLMs and the Abstraction and Reasoning Corpus: Successes, Failures, and the Importance of Object-based Representations.**](https://arxiv.org/abs/2305.18354)

## Structure
The `output-logs` directory includes two subdirectories, `direct-grid` and `object-based`, each representing different approaches in our experiment. Both contain:

- `ARC-subset`: Results for various prompting methods on the 50 ARC tasks subset, with filenames representing the prompting method as outlined in Table 1 and 3 of our paper.
- `1D-ARC` and `Vertical-Horizontal`: Results for generated tasks using the best performing prompting methods, with filenames based on the generated task types as seen in Table 2 and 4 of our paper.
The exact mapping of the 1D-ARC filenames can be found [here](https://github.com/khalil-research/1D-ARC).

**Note:** If a results file ends with 3.5 or 4, it contains the result for GPT-3.5 or GPT-4, respectively. If it does not have such an ending, it contains results for both models.

## Visualization
For a visualization of GPT-4 solutions, visit [our visualizations page](https://khalil-research.github.io/LLM4ARC).
![Visualization Screenshot](https://drive.google.com/uc?export=view&id=1JFQ8lksQv03zWKuEv5HefqWycQO5UYK6)

## Dataset
The "1D-ARC" dataset used in our experiments is available at this [GitHub repository](https://github.com/khalil-research/1D-ARC).
