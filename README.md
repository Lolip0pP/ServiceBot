# ServiceBot

A bot for Outlook mailbox based on BERT-like retrieve&rerank model.
This is a draft, though somehow a working one. Main files are:

1) parsing - for making a training sample
2) LaBSE - for training a model (retrieve-part)
3) testing_models - for making sure that it is working at least a bit
4) bot - implementing a model with logging
5) reranking - for a fine-tuning after watching logs