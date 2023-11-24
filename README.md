# AI701-project
# BERT

The BERT training expirament was done in the following order: 

1. Huggingface BERT is finetuned on our dataset and the best model is saved - huggingface-bert.ipynb
2. the saved model is used for inference - bert-mcq.ipynb
3. Kfolds is performed on Huggingface BERT and is finetuned on our dataset and the best model(of all folds) is saved - kfolds-on-bert.ipynb
4. The saved model(from3) is used for inference - bert-mcq.ipynb

# BERT with RAG 
RAG takes an input and retrieves a set of relevant/supporting documents given a source (e.g., Wikipedia).

1. Huggingface BERT is finetuned on our dataset + the retrieved context and the best model is saved - huggingface-bert-with-wikipedia-rag.ipynb
2. The saved model is used for inference - bert-with-wikipedia-rag.ipynb
3. Kfolds is performed on Huggingface BERT and is finetuned on our dataset and the best model(of all folds) is saved - kfolds-of-huggingface-bert-with-wikipedia-rag.ipynb
4. The saved model(from3) is used for inference - bert-with-wikipedia-rag.ipynb
