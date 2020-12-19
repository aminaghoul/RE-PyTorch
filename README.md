# RE-PyTorch

Ce repository contient des tutoriels sur comment faire de l'extraction de relation en utilisant Pytorch 1.4 sur Python 3.7. 

## Installation 

 - Pour installer PyTorch, les instructions sont sur [ce site.](https://pytorch.org/get-started/locally/) 

 - TorchText : ` pip install torchtext`
 
 - spaCy en anglais : `python -m spacy download en`
 
 - transformers : `pip install transformers`
 
## Données

On utilise les données [SemEval-2010 Task 8.](https://www.aclweb.org/anthology/S10-1006.pdf)

## Tutoriels

 - 1 - [CNN](https://github.com/aminaghoul/RE-PyTorch/blob/main/1_CNN_SemEval2010.ipynb) 
 
 Dans ce premier notebook, le modèle utilisé est un réseau de neurones convolutif (ou CNN) pour faire de l'extraction de relation (RE).

 - 2 - [BiLSTM+Attention](https://github.com/aminaghoul/RE-PyTorch/blob/main/2_BiLSTM_Att_SemEval2010.ipynb)
 
Ici, on utilise un modèle composé d'un modèle BiLSTM associé à un modèle d'attention.

 - 3 - [CNN+Attention](https://github.com/aminaghoul/RE-PyTorch/blob/main/3_CNN_Att_SemEval.ipynb)
 
 Dans ce notebook nous implémentons un modèle CNN auquel s'ajoute le mécanisme d'attention.
 
 - 4 - [BERT](https://github.com/aminaghoul/RE-PyTorch/blob/main/4_BERT_SemEval2010.ipynb) 

Enfin, on implémente le modèle **BERT** décrit [ici](https://arxiv.org/abs/1810.04805) en utilisant [Hugging Face.](https://github.com/huggingface/transformers) 
 
 ## Résultats
 
 ## Référence : 
 
 - [Step-by-step NER Model for Bahasa Indonesia with PyTorch and Torchtext](https://yoseflaw.medium.com/step-by-step-ner-model-for-bahasa-indonesia-with-pytorch-and-torchtext-6f94fca08406) 
 
