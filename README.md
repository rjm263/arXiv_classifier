# arXiv_classifier

A multi-label classifier based on Hugging Face's  DistilBERT model. Classifies arXiv papers based on their title alone.

As an example, we chose the top 20 arXiv categories for classification, but this can easily be extended to inlcude more categories. The model respects cross-listing of papers and predicts the 5 most probable categories and their probabilities.
