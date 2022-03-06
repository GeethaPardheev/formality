# Ensemble BERT-based models for formality classification
Classification of documents based on their formality using state-of-the-art BERT-based models like BERT, RoBERTa, ELECTRA, XLNET, DeBERTa using ensemble techniques.

Models are trained on two different datasets:  
• GYAFC (https://arxiv.org/pdf/1803.06535v2.pdf)  
• Formality Corpus (https://aclanthology.org/Q16-1005.pdf)  

The best performing ensemble models based on accuracy on validation set of GYAFC corpus:  
• BERT + RoBERTa - 94.72%  
• RoBERTa + ELECTRA - 94.70%
