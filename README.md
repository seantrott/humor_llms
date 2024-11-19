# Humor detection, appreciation, and comprehension in humans and LLMs

This repository contains data and analysis code for the paper:

> Trott, S., Walker, D. E., Taylor, S., & Coulson, S. (Under Review). Turing Jest: Do Large Language Models have a Sense of Humor?

## `data`

The `data` directory contains both the original *joke stimuli* (`data/raw/coulson_stimuli.csv`) as well as all data from the LLMs and humans. 

The following directories contain the **human data**:

- `human_data`: contains cleaned human responses for the comprehension probe task. 
- `human_data_appreciation`: contains cleaned human responses for the joke detection and appreciation tasks.

The results of the pre-registered GPT-3 analyses can be found in the following files:

- `data/processed/llm_appreciation.csv`
- `data_processed/llm_classification.csv`
- `data/processed/comprehension_probe0shot.csv`
- `data/processed/comprehension_probe1shot.csv`

Finally, the results for the replication with open-source HuggingFace models can be found in `data/processed/hf_models`.


## LLM notebooks

Pre-registered and exploratory LLM experiments can be found in the **Jupyter notebooks**:

- `humor_classification.ipynb`: Code for the classification and appreciation tasks with GPT-3. 
- `humor_comprehension.ipynb`: Code for the comprehension task with GPT-3. 
- `Supplementary Analysis 3.ipynb`: Code for the entropy analysis.  


## 


