# Advancing-User-Item-Interactions-with-LLMs
Utilizing Edge Information for Recommendation Optimization

This file includes the Python code used for the conference paper available at URL = ""

Our objective is to leverage large language models (LLMs) for recommendation tasks. Existing approaches struggle to structurally incorporate edge information from graphs into LLMs. To address this limitation, we propose a two-part solution. First, we introduce an edge-aware attention mechanism by integrating edge measurements into the attention calculation. Second, we develop a tailored set of prompts for both pre-training and fine-tuning stages. Further details of our approach are presented in the accompanying paper.

For our experiments, we utilize the Amazon Review Dataset. The original dataset is publicly available at URL = "https://nijianmo.github.io/amazon/index.html".

The code consists of two main components. The first component implements the modified attention mechanism, while the second component outlines the workflow of the proposed method.
