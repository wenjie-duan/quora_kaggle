#  Kaggle competition: Quora Question Pairs



#### Reference:https://www.kaggle.com/c/quora-question-pairs


Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Currently, Quora uses a Random Forest model to identify duplicate questions. In this competition, Kagglers are challenged to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.

## Problem:
- Given 2 questions, predict the probability that they are duplicate questions. 
## Process & Model & Deliver
- Benchmark: naive prediction, always predict the same probability.
- Self-defined distance between 2 sentences.
- Implemented deep learning model(GRU) with Pytorch.


## Lesson Learn
- Modifying the binary-classification threshold helps increase accuracy, but doesn't help with logloss, which is the evaluation metrics in this competition.



