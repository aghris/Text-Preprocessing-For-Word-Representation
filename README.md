
# Effects of Preprocessing in Word Embedding Demo
> Aymane BERRADI - Taoufik AGHRIS  

A demo for the paper "**A Comprehensive Analysis of Preprocessing for Word Representation Learning in Affective Tasks**", we focus on the classification task and the news corpus. We investigate the effect of 4 preprocessing techniques:
1. Punctuation (Punc)
2. Stemming (Stem)
3. Stopwords removal (Stop)
4. Pos-Tagging (POS)

# Architecture of the project
## Folder 1: data
It contains the corpus data **News** and the classification dataset **IMDB**.

## Folder 2: Embeddings
It contains the different embeddings generated using **CBOW** and **Skip gram** for each preporcessing technique.

## Folder 3: Weights
It stores the best weights obtained from the **LSTM** model.

## Notebooks Description :
* `Stop_Embedding.ipynb`: It contains the code for generating embeddings for stopwords removal applied to the corpus.
* `Stem_Embedding.ipynb`: It contains the code for generating embeddings for Stemming applied to the corpus.
* `Punctuation_Embedding.ipynb`: It contains the code for generating embeddings for Punctuation applied to the corpus.
* `Pos_Tag_Embedding.ipynb`: It contains the code for generating embeddings for Pos-Tagging applied to the corpus.
* `Gather_All_Embedding.ipynb`: It contains the code for generating embeddings for all of the 4 preporcessing techniques applied to the corpus.

# Disclaimer
Most of the code used in our work is based on [NastaranBa](https://github.com/NastaranBa/preprocessing-for-word-representation) repository, one of the paper's writers.
