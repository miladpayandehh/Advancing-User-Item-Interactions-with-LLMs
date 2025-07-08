# Advancing-User-Item-Interactions-with-LLMs
Utilizing Edge Information for Recommendation Optimization

This file includes the Python code used for the conference paper available at URL = "https://www.researchgate.net/publication/390992827_Optimizing_Recommendations_through_Enhanced_User-Item_Interactions_with_Large_Language_Models_LLMs_Utilizing_Edge_Information?_sg%5B0%5D=BM44eMSux8Hwssgp_c95DPjJMvF58n14pW1gkVR6FfWMmi1pyR9N1pEiJjPDYYkzD7qQOxhDoz1eMPjNSKPhVq7IhvUcFXpXFRaSeqLk.b1HQ_czyJZOYQ8DqjUlYvwP4xnmQff0vws8H0WBvO4PDQYo4sbPDrNXsYX6cAeLUH8ICgDVluRULIqRSPQn8dw&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6ImhvbWUiLCJwYWdlIjoicHJvZmlsZSIsInByZXZpb3VzUGFnZSI6InByb2ZpbGUiLCJwb3NpdGlvbiI6InBhZ2VDb250ZW50In19"

Our objective is to leverage large language models (LLMs) for recommendation tasks. Existing approaches struggle to structurally incorporate edge information from graphs into LLMs. To address this limitation, we propose a two-part solution. First, we introduce an edge-aware attention mechanism by integrating edge measurements into the attention calculation. Second, we develop a tailored set of prompts for both pre-training and fine-tuning stages. Further details of our approach are presented in the accompanying paper.

For our experiments, we utilize the Amazon Review Dataset. The original dataset is publicly available at URL = "https://nijianmo.github.io/amazon/index.html".

The code consists of two main components. The first component implements the modified attention mechanism, while the second component outlines the workflow of the proposed method.
