# AI701-project
# BERT

The BERT training experiment was done in the following order: 
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

# RoBERTa
The notebooks run on kaggle. 
1. Huggingface RoBERTa finetuning/finetuned (uncomment/comment necessary parts) - [roberta-llm-exam.ipynb](https://www.kaggle.com/code/sajangirova/roberta-llm-exam)
2. Kfolds is performed on Huggingface RoBERTa finetuning/finetuned (uncomment/comment necessary parts) - [roberta-kfold.ipynb](https://www.kaggle.com/sajangirova/roberta-kfold)

# RoBERTa with RAG
The process for getting suppoting information is the same as for BERT and other models in our project.
1. Huggingface RoBERTa finetuning/finetuned (uncomment/comment necessary parts) + the retrieved context - [roberta-RAG.ipynb](https://www.kaggle.com/sajangirova/roberta-rag)
2. Kfolds is performed on Huggingface RoBERTa finetuning/finetuned (uncomment/comment necessary parts) + the retrieved context - [roberta-RAG-kfold.ipynb](https://www.kaggle.com/sajangirova/roberta-rag-kfold)

# GPT3.5

gpt3.5 API was used, and the predictions are in gpt3.5_pred.csv

# Llama 2 7b chat

Llama 2 7b chat api was used. Notebooks for the inference process are llama-api.ipynb and llama-api-with-context.ipynb for inferencing without and with RAG context respectively. The predictions are in llama-2-7b-answers.csv and llama-2-7b-answers-context.csv


# LSTM

1. LSTM multiclass classification without rag - [lstm-without-rag.ipynb] (https://www.kaggle.com/code/fathinahizzati/lstm-1/notebook)
2. LSTM multiclass classification with rag - [lstm-with-rag.ipynb] (https://www.kaggle.com/fat2321321/lstm-3)
3. LSTM for next word inference - [lstm-next-token-pred.ipynb] (https://www.kaggle.com/tinaaaaaaaaa/lstm-2-2)


# Platypus
1. Platypus inference without wikipedia rag - [platypus2-70b-without-wikipedia-rag.ipynb] (https://www.kaggle.com/code/tinaaaaaaaaa/platypus2-70b-without-wikipedia-rag) 
2. Platypus inference with wikipedia rag - [platypus2-70b-with-wikipedia-rag.ipynb] ()

# Bag-of-Words

1. Bag-of-words + cosine similarity [bow-without-sklearn.ipynb](https://www.kaggle.com/code/fathinahizzati/bow-tfidf-2-new?scriptVersionId=149455334 )
2. Bag-of-words + cosine similarity with sklearn [bow-with-sklearn.ipynb](https://www.kaggle.com/code/fathinahizzati/bow-tfidf-2-new?scriptVersionId=149600051)
