# Advancing-User-Item-Interactions-with-LLMs
Utilizing Edge Information for Recommendation Optimization

This file includes the Python code used for the conference paper available at [Optimizing Recommendations through Enhanced User-Item Interactions with Large Language Models (LLMs) Utilizing Edge Information](https://www.researchgate.net/publication/390992827_Optimizing_Recommendations_through_Enhanced_User-Item_Interactions_with_Large_Language_Models_LLMs_Utilizing_Edge_Information).

Our objective is to leverage large language models (LLMs) for recommendation tasks. Existing approaches struggle to structurally incorporate edge information from graphs into LLMs. To address this limitation, we propose a two-part solution. First, we introduce an edge-aware attention mechanism by integrating edge measurements into the attention calculation. Second, we develop a tailored set of prompts for both pre-training and fine-tuning stages. Further details of our approach are presented in the accompanying paper.

For our experiments, we utilize the Amazon Review Dataset. The original dataset is publicly available at [Amazon Review Dataset](https://nijianmo.github.io/amazon/index.html).

The code consists of two main components. The first component implements the modified attention mechanism, while the second component outlines the workflow of the proposed method.
