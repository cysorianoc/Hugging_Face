# Hugging_Face
This repository contains some notebooks applying open source models with Hugging Face

## Notebook 1: Natural Language Processing (NLP)

The idea here is using transformers library from Hugging Face to load pre-trained language models and build chatbots.
Some models include pipelines that reduce the code lines necessary to load and run the model.

NLP can be used for the following type of tasks:
- Text generation
- Sentence similarity
- Summarization
- Machine translation

As example there were used two models in the notebook:
- blenderbot-400M-distill
- Qwen3-0.6B


## Notebook 2: Translation and Summarization

Application of models to perform:
- Translation: `nllb-200-distilled-600M`
- Summarization: `bart-large-cnn` and `Falconsai`
  
*Note: one of the issues with pipelines is they do not work for summarization and translation when importing transformers library v5.0*


