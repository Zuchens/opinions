# opinions
OPTA info: http://zil.ipipan.waw.pl/OPTA  
Embeddings taken from : http://mozart.ipipan.waw.pl/~axw/models/orth/  

Graphviz installation for model plotting
sudo apt install python-pydot python-pydot-ng graphviz

To train the network run:
```python opinions/rnn/train.py <path_to_data> <path_to_embedding_file>```

To compare with crf run:
```python opinions/rnn/eval.py  ```  
( it runs with default paths)



To predict:
```python opinions/rnn/predict.py <path_to_data>```  



Embedding file has to be in word2vec format
