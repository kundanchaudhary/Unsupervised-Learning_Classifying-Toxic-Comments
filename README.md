# Toxic Comment Classification

## Description:
Expressing oneself on online media (such as Facebook, Twitter, and YouTube) is not so easy. It often comes with the threat of abuse and harassment. This may result in people stopping to express themselves or seeking alternative platforms to express their opinions. Similarly, online chat platforms struggle to facilitate conversations which result in completely removing user comments. Thus, a tool which can help improve online conversations is indispensable given the increasingly high number of people on online platforms.


## Objective & Methodology:
In this project, we perform topic modeling to find out different types of toxicity involved in the corpus. Furthermore, using the topics' weight matrix, number of words in each text, and clustering info. as features, we classify the texts into toxic and non-toxic categories.

## Results/Conclusions:
In this project, starting from a raw text data or corpus, we need to do a significant amount of data cleaning to see any decent topics by topic modeling. In essence, the topics are coherent (coherence score: 0.8) enough to attribute different levels of toxicity to a given document. This can be significantly improved with further data preprocessing, i.e., inclusion of misspelled words and abbreviations. Importantly, the weight matrices from the topic modeling can be used as features to do supervised learning (using classification models such as Logistic Regression model). The accuracy score is 91% (precision score: 65%), but given that the dataset is imbalanced, further analysis/optimization is required to improve the precision and recall scores.

## References:

[1] https://towardsdatascience.com/topic-modeling-quora-questions-with-lda-nmf-aff8dce5e1dd

[2] https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python

[3] https://towardsdatascience.com/applying-machine-learning-to-classify-an-unsupervised-text-document-e7bb6265f52
