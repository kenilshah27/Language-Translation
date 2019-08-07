# Language-Translation

I have implemented three models.

1. Seq2Seq : It applies a Bidirectional LSTM to the encoder-decoder architecture.
2. Seq2SeqWithAttention : It applies a Bidirectional LSTM to the encoder-decoder architecture with an attention layer in between
3. Transformer :  It is an encoder-decoder structure without the RNN architecture. It makes use of multi-headed attention layers.

Links:

1. Seq2Seq
    
    https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf
    
    https://towardsdatascience.com/word-level-english-to-marathi-neural-machine-translation-using-seq2seq-encoder-decoder-lstm-model-1a913f2dc4a7
    
    Dataset : http://www.manythings.org/anki/

2. Seq2SeqWithAttention
   
   https://towardsdatascience.com/attn-illustrated-attention-5ec4ad276ee3
   
   https://nlp.stanford.edu/pubs/emnlp15_attn.pdf
   
   https://www.youtube.com/watch?v=IxQtK2SjWWM
   
   Dataset : http://www.manythings.org/anki/

3. Transformer
   
   https://www.analyticsvidhya.com/blog/2019/06/understanding-transformers-nlp-state-of-the-art-models/
   
   https://towardsdatascience.com/how-to-code-the-transformer-in-pytorch-24db27c8f9ec
   
   https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf
   
   Dataset : http://www.manythings.org/anki/
   

Note:

     For all of this models i ran it on Google colab with GPU. I have used very less data and hence the result might not be as expected. But with larget dataset and more epochs, you can simply run this codes to get a good accuracy.
