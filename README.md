# fine_tuning_bert

This lab is taken from https://colab.research.google.com/github/DerwenAI/spaCy_tuTorial/blob/master/BERT_Fine_Tuning.ipynb 

In it we will train a text classifier by adding an untrained layer of neurons to the end of 
a pretrained BERT model and update that layer using [labeled data](https://nyu-mll.github.io/CoLA/) for our 
specification classification task to determine if a sentence is grammatically correct.

All computation will be run on free Google resources via Colab using the pytorch interface for BERT provided by Hugging Face. 
