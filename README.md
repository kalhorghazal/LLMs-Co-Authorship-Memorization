# LLMs-Co-Authorship-Memorization

This repository contains the dataset and analysis code for the paper:

**Title:** "Remembering Unequally: Global and Disciplinary Bias in LLM-Generated Co-Authorship Networks"

**Authors:** Ghazal Kalhor and Afra Mashhadi

**Abstract:** "Ongoing breakthroughs in Large Language Models (LLMs) are reshaping search and recommendation platforms at their core. While this shift unlocks powerful new scientometric tools, it also exposes critical fairness and bias issues that could erode the integrity of the information ecosystem. Additionally, as LLMs become more integrated into web-based searches for scholarly tools, their ability to generate summarized research work based on memorized data introduces new dimensions to these challenges. The extent of memorization in LLMs can impact the accuracy and fairness of the co-authorship networks they produce, potentially reflecting and amplifying existing biases within the scientific community and across different regions. This study critically examines the impact of LLM memorization on the co-authorship networks. To this end, we assess memorization effects across three prominent models, DeepSeek R1, Llama 4 Scout, and Mixtral 8x7B, analyzing how memorization-driven outputs vary across academic disciplines and world regions. While our global analysis reveals a consistent bias favoring highly cited researchers, this pattern is not uniformly observed. Certain disciplines, such as Clinical Medicine, and regions, including parts of Africa, show more balanced representation, pointing to areas where LLM training data may reflect greater equity. These findings underscore both the risks and opportunities in deploying LLMs for scholarly discovery."

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
