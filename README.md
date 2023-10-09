# Basic Document Classifcation
Using embeddings to visualize and classify different document types 

## Document cleaning

Remove variable PII data with NER: names, addresses, company information 
Use only first 2 pages of document for classification? 

## Generate document emdeddings

decide on which model, embedding-level: word, sentence, document 

Embeddings example:
(older)
Glove
word2vec
fasttext

Encoder only 
Bert
Distilbert
etc...

Decoder only 
GPT-2 (not recommended)
openai API

## Visualizations

PCA, t-SNE, UMAP

## Classification 

SVM, text similarity for semi-structured documents
inter and intra classification attempts

## Vector store 

Depending on classication results, create prototype system of training and inference loop
Create Dockerized Milvus instance with insurance examples with search 

## Things to think about 

- fine tuning BERT using our insurance doc dataset - needs at elast 10k examples

## Resources 

- HF Embeddings leaderboard: https://huggingface.co/blog/mteb
