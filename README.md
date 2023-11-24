# AI701-project
# BERT

The BERT training expirament was done in the following order: 
the following ipynb were run on kaggle. We have made the notebooks public(for the duration of grading) on kaggle so you can run them, if needed. 
1. Huggingface BERT is finetuned on our dataset and the best model is saved - [huggingface-bert.ipynb](https://www.kaggle.com/code/noorrabih/huggingface-bert)
2. the saved model is used for inference - [bert-mcq.ipynb](https://www.kaggle.com/code/noorrabih/bert-mcq/notebook)
3. Kfolds is performed on Huggingface BERT and is finetuned on our dataset and the best model(of all folds) is saved - [kfolds-on-bert.ipynb](https://www.kaggle.com/code/noorrabih/kfolds-on-bert)
4. The saved model(from3) is used for inference - [bert-mcq.ipynb](https://www.kaggle.com/code/noorrabih/bert-mcq/notebook)

# BERT with RAG 
RAG takes an input and retrieves a set of relevant/supporting documents given a source (e.g., Wikipedia).

1. Huggingface BERT is finetuned on our dataset + the retrieved context and the best model is saved - [huggingface-bert-with-wikipedia-rag.ipynb](https://www.kaggle.com/code/noorrabih/huggingface-bert-with-wikipedia-rag)
2. The saved model is used for inference - [bert-with-wikipedia-rag.ipynb](https://www.kaggle.com/code/noorrabih/bert-with-wikipedia-rag)
3. Kfolds is performed on Huggingface BERT and is finetuned on our dataset and the best model(of all folds) is saved - [kfolds-of-huggingface-bert-with-wikipedia-rag.ipynb](https://www.kaggle.com/code/noorrabih/kfolds-of-huggingface-bert-with-wikipedia-rag)
4. The saved model(from3) is used for inference - [bert-with-wikipedia-rag.ipynb](https://www.kaggle.com/code/noorrabih/bert-with-wikipedia-rag)

# GPT3.5

gpt3.5 API was used, and the predictions are in gpt3.5_pred.csv
