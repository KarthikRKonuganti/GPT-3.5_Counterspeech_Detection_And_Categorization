# Detecting and Classifying Counterspeech by Fine-Tuning and Prompting GPT-3.5

This repository is the official implementation of Detecting and Classifying Counterspeech by Fine-Tuning and Prompting GPT-3.5. 

## Requirements

To install requirements:

```setup
pip install openai
```

>📋  Describe how to set up the environment, e.g. pip/conda/docker commands, download datasets, etc...
We set up the environment by using Google Colab and running the line "!pip install openai".

Code for training and/or evaluation are included in each of the three files.
Once we had the data, we kept it in a google spreadsheet and created the three charts, as seen in the results section of our paper.

Our full code and setup are available in the code folder.

## Results

The GPT-3.5 fine-tuning model achieves a F1-score of 0.83 on the dataset mentioned in the paper and code.
Our full results are available in the results folder.
