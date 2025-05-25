# Humor detection, appreciation, and comprehension in humans and LLMs

This repository contains data and analysis code for the paper:

> Trott, S., Walker, D. E., Taylor, S. M., & Coulson, S. (2025). Turing Jest: Distributional Semantics and One‐Line Jokes. Cognitive Science, 49(5), e70066. [[Link]](https://onlinelibrary.wiley.com/doi/10.1111/cogs.70066?af=R)

## `data`

The `data` directory contains both the original *joke stimuli* (`data/raw/coulson_stimuli.csv`) as well as all data from the LLMs and humans. 

The following directories contain the **human data**:

- `data/processed/human_data`: contains cleaned human responses for the comprehension probe task. 
- `data/processed/human_data_appreciation`: contains cleaned human responses for the joke detection and appreciation tasks.

The results of the pre-registered GPT-3 analyses can be found in the following files:

- `data/processed/llm_appreciation.csv`
- `data_processed/llm_classification.csv`
- `data/processed/comprehension_probe0shot.csv`
- `data/processed/comprehension_probe1shot.csv`

Finally, the results for the replication with open-source HuggingFace models can be found in `data/processed/hf_models`.


## LLM notebooks

Pre-registered and exploratory LLM experiments (i.e., to reproduce the GPT-3 studies) can be found in the **Jupyter notebooks**:

- `humor_classification.ipynb`: Code for the classification and appreciation tasks with GPT-3. 
- `humor_comprehension.ipynb`: Code for the comprehension task with GPT-3. 

Additionally, `Supplementary Analysis 3.ipynb` contains code for the entropy analysis.  


## Data analyses

Finally, all **pre-registered** and **exploratory** analyses can be found in `src/analysis`.

- `src/analysis/human_appreciation_analysis.Rmd`: R analysis for the pre-registered detection and appreciation task with humans. 
- `src/analysis/llm_appreciation.Rmd`: R analysis for the pre-registered detection and appreciation task with LLMs. 
- `src/analysis/human_comprehension_analysis.Rmd`: R analysis for the pre-registered comprehension task with humans. 
- `src/analysis/humor_comprehension.Rmd`: R analysis for the pre-registered comprehension task with LLMs. 
- `src/analysis/hf_analysis.Rmd`: R analysis for the replication analyses with the open-source HF models.

Note that we have also included **knitted** `.html` files for these analyses. In particular `hf_analysis` contains several figures used in the final manuscript.

