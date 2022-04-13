# Language_Identificaiton

This repository present a python script that uses a deep learning library called HugginFace (https://huggingface.co/) that group different pre-trained 
models for several topics. The model used named 'xlm-roberta-base-language-detection' which is a fine-tuned version of xlm-roberta-base on the Language 
Identification dataset.
This model is an XLM-RoBERTa transformer model with a classification head on top (i.e. a linear layer on top of the pooled output).

The model was fine-tuned on the Language Identification dataset, which consists of text sequences in 20 languages. The training set contains 70k samples, while the validation and test sets 10k each. The average accuracy on the test set is 99.6% (this matches the average macro/weighted F1-score being the test set perfectly balanced).
