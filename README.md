# arXiv_classifier

This repo contains two classifier models based on Hugging Face's DistilBERT. Classifies arXiv papers based on their titles.

- arXiv_title_classifier: trained on arXiv data labelled by all cross-listed categories
- arXiv_no_crosslist: trained on arXiv data labelled by a single (the main) category only
  
As an example, we chose the top 20 arXiv categories for classification, but this can easily be extended to inlcude more categories.

The dataset of arXiv papers for training/testing can be obtained on Kaggle (https://www.kaggle.com/datasets/Cornell-University/arxiv/data) and either downloaded directly on the webpage (as done in this code) or via their API (see https://www.kaggle.com/docs/api).
