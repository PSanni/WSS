# WSS
Models and code for WSS. 

The Model:
----------------

1. word2vec_blog06_feed
    - Data collection: Blog06
    - dimensions: 300
    - window size:100
    - Size: 7.6 GB
* Requirnments:
  - It requires minumum 16 GB RAM to load, and >16GB, if wants to inference. 
  - Loading using gensim (https://radimrehurek.com/gensim/) is recommended, if workign with python. 
  - Or else, for any other language, **.npy*  files can be used to load vectors. 
  - In repository: **.syn1neg.npy* contains vectors for OUT embeddings, whereas, **.vectors.npy* is IN embeddings. 
  - you can donwload model from, https://huggingface.co/PSanni/word2vec_wss_100dim
