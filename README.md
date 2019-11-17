# Quora-Duplicate-Question-Detection
Detecting Semantically similar questions and marking them as duplicate.

# Semantic Text Similarity b/w Questions on Quora
A siemese network to check semantic similarity b/w two questions. Working:

1. Text Pre-processing
2. Embedding questions using word2vec into numeric form
3. Passing the embedded form of the two questions to the shared lstm layer.
4. Finding exponential manhattan distance between the two encoded form of questions and outputing value b/w 0 and 1 representing the extent of similarity. If the questions have high degree of similarity (1) then they are marked as duplicate.
