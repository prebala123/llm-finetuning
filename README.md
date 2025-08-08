# LLM Finetuning

This project includes Named Entity Recognition using BERT transformer and Mistral 7B Model. It tunes the model to recognize entities in sentences like names or places. The project uses PyTorch and peft packages to train the model.

First we download the wnut 17 dataset for training NER tasks. Then the notebook file for the BERT model shows how to tokenize the dataset and set up the configuration for training. Then it gives example outputs from the test data. 

For example the sentence "John lives in New York" should recognize John as a person and New York as a location. 

In the mistral notebook it also show the LoRA config for efficient training of LLMs. The example uses rank 4 matrices to train the model.