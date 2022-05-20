# Project-SkimLit-NLP-DeepLearning

In this project, we're going to be putting what we've learned into practice.

More specificially, we're going to be replicating the deep learning model behind the 2017 paper [PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts.](https://arxiv.org/abs/1710.06071)

When it was released, the paper presented a new dataset called PubMed 200k RCT which consists of ~200,000 labelled Randomized Controlled Trial (RCT) abstracts.

The goal of the dataset was to explore the ability for NLP models to classify sentences which appear in sequential order.

In other words, given the abstract of a RCT, what role does each sentence serve in the abstract?

Models:
  1. Model 0: Getting a baseline
  2. Model 1: Conv1D with token embeddings
  3. Model 2: Feature extraction with pretrained token embeddings
  4. Model 3: Conv1D with character embeddings
  5. Model 4: Combining pretrained token embeddings + character embeddings (hybrid embedding layer)
  6. Model 5: Transfer Learning with pretrained token embeddings + character embeddings + positional embeddings
Then, find the most wrongs!
