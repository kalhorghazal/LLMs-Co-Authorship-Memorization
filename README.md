# LLMs-Co-Authorship-Memorization

This repository contains the dataset and analysis code for the paper:

**Title:** "Remembering Unequally: Global and Disciplinary Bias in LLM Reconstruction of Scholarly Coauthor Lists"

**Authors:** Ghazal Kalhor and Afra Mashhadi

**DOI:** https://doi.org/10.1140/epjds/s13688-026-00647-0

**Abstract:** "Ongoing breakthroughs in large language models (LLMs) are reshaping scholarly search and discovery interfaces. While these systems offer new possibilities for navigating scientific knowledge, they also raise concerns about fairness and representational bias rooted in the models' memorized training data. As LLMs are increasingly used to answer queries about researchers and research communities, their ability to accurately reconstruct scholarly coauthor lists becomes an important but underexamined issue. In this study, we investigate how memorization in LLMs affects the reconstruction of coauthor lists and whether this process reflects existing inequalities across academic disciplines and world regions. We evaluate three prominent models, DeepSeek R1, Llama 4 Scout, and Mixtral 8x7B, by comparing their generated coauthor lists against bibliographic reference data. Our analysis reveals a systematic advantage for highly cited researchers, indicating that LLM memorization disproportionately favors already visible scholars. However, this pattern is not uniform: certain disciplines, such as Clinical Medicine, and some regions, including parts of Africa, exhibit more balanced reconstruction outcomes. These findings highlight both the risks and limitations of relying on LLM-generated relational knowledge in scholarly discovery contexts and emphasize the need for careful auditing of memorization-driven biases in LLM-based systems."

## Dataset

We collected the following information for each researcher:

* Name
* Google Scholar ID
* OpenAlex URL
* Citation Count
* Publication Count
* Email Domain
* Affiliation
* Field
* Subfield
* Citation Level
* Country
* Region
* Co-author count (Google Scholar)
* Co-authors' names (Google Scholar)
* Co-authors' names (OpenAlex)
* Co-authors' names (DeepSeek R1)
* Co-authors' names (Llama 4 Scout)
* Co-authors' names (Mixtral)

## Citation

If you use our dataset or analysis code in your work, please cite our paper as below.

```
@article{kalhor2026remembering,
  author    = {Kalhor, Ghazal and Mashhadi, Afra},
  title     = {Remembering Unequally: Global and Disciplinary Bias in LLM-Generated Co-Authorship Networks},
  journal   = {EPJ Data Science},
  year      = {2026},
  note      = {Accepted for publication},
  doi       = {https://doi.org/10.1140/epjds/s13688-026-00647-0}
}
```
