# Quora-Duplicate-Question-Detection
Detecting Semantically similar questions to avoid posting of duplicates on the Quora platform

## Dependencies
* re
* numpy
* pandas
* itertools
* datetime
* nltk
* gensim
* sklearn
* keras
* tensorflow

## Semantic Text Similarity b/w Questions on Quora
Duplicate questions are detected using a siemese network which computes the semantic similarity between a pair of questions.

**Steps**
1. Text Pre-processing
2. Embedding questions using word2vec into numeric form
3. Passing the embedded form of the questions to a shared LSTM layer.
4. Finding exponential manhattan distance between the encoded forms of questions and outputing value b/w 0 and 1 representing the extent of similarity. If the questions have high degree of similarity (1 or close to 1) then they are marked as duplicate.

