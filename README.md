# NLP_donatien_roi

This project explores a corpus of French political manifestos using Natural Language Processing (NLP) techniques.

The main objectives are:

Analyze semantic similarities between documents
Detect gender-based patterns in political discourse
Identify latent political structures
Visualize documents in a low-dimensional embedding space
Detect outliers in political speech

Pipeline :

1. Preprocessing:
OCR cleaning & normalization,
Removal of punctuation & noise,
Encoding standardization,

2. Embedding:
Multilingual Sentence Transformer,
Each document → dense semantic vector,

3. Dimensionality Reduction:
UMAP → 2D projection for visualization,

4. Classification:
Using Multinomial Naive Bayes:
Gender prediction,
Political party classification,
Political support detection,

5. Outlier Detection:
Distance-based scoring (Euclidean distance in embedding space)
