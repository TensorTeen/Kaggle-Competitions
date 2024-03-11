# LLM-Science-Exam

These notebooks were written as a part of the LLM science Exam Kaggle Competition.

We have a T5Long Encoder which takes a prompt as an input. prompt contains question and context for the given question from a wiki database retrieved using a BM25 retriever. Then the encoder creates embedding vector which is connected to a classification head that is trained to classify which answer is correct
