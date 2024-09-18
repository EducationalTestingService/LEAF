# LEAF: Language Learners' English Essays and Feedback Corpus

This repository provides the **LEAF dataset**, introduced in our [NAACL 2024 paper](https://aclanthology.org/2024.naacl-short.36/). The dataset contains approximately 6,000 English essays paired with corresponding feedback sourced from the "EssayForum" website. LEAF is a valuable resource for developing personalized feedback generation systems, addressing issues such as grammar correction, argument structure, and coherence in essays.

## About the Dataset
This repository contains the second version of the LEAF dataset, available as `leaf.jsonl`.

### Notable Changes from the Paper
- **Feedback Source**: In this version, only feedback comments provided by Educational Consultant Mary Rose are included to ensure higher-quality feedback. As a result, this version is slightly smaller than the dataset reported in the paper. Future releases will include feedback from a more diverse set of educators.
- **Dataset Splits**: The dataset is now split as follows:  
  - Test: 500  
  - Dev: 400  
  - Train: 4,018

## Disclaimer
We have made significant efforts to clean the dataset by removing noise, forum-related information, and personal names using heuristics and named entity recognition systems. However, some noise may still remain.

Additionally, essay prompts provided by students can appear in various locations within the essays. While we have addressed many of these variations, prompts may still occasionally appear at the beginning of the `essay_text` field in some instances.

## License and Usage Terms
The LEAF corpus is released under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.en).

The original content is sourced from EssayForum.com, which operates under the following terms of use:

*"By posting on EssayForum.com, you grant us a royalty-free, perpetual, non-exclusive, unrestricted worldwide license to use, reproduce, modify, and distribute your content in any medium, for any purpose, including commercial purposes."*

We have also contacted EssayForum and received confirmation that the data can be used for **research purposes**, provided proper attribution is given. Please reference their site when using this dataset.

## Citation
If you find this dataset useful for your research, please cite our paper:

>Shabnam Behzad, Omid Kashefi, Swapna Somasundaran. 2024. [LEAF: Language Learners' English Essays and Feedback Corpus](https://aclanthology.org/2024.naacl-short.36/). In NAACL, pages 433–442, Mexico City, Mexico.