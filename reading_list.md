## Basics of RNN

[Recurrent Batch Normalization](https://arxiv.org/pdf/1603.09025v4.pdf)
> Covariate shift is a change in distribution of the inputs to a model.   
> For deep feed-forward neural networks, covariate shift degrades the efficiency of training.   
> Batch Normalized LSTM:    
> ``ifog = BN(W*h_t-1) + BN(W*x) + b``    
> ``c_t = sigmoid(f) * c_t-1 + sigmoid(i) * tanh(g) ``    
> ``h_t = sigmoid(o) * tanh(BN(c_t)) ``    

## Encoder-Decoder, Attention and Memory
[Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation](https://arxiv.org/abs/1406.1078)
> Encoder-Decoder Framework and GRU

[Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473)
> Attention

[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)
> Attention on cnn features for image caption

[Effective Approaches to Attention-based Neural Machine Translation](http://stanford.edu/%7Elmthang/data/papers/emnlp15_attn.pdf)
> 1. Comparision of different schemes of Global Attention     
> dot: `` ht * hs ``    
> general: `` ht * Wa * hs ``    
> concatenate: `` vt * tanh(Wa *[ht:hs]) ``    
>     
> 2. Local Attention    
> Hard Attention: As in Show, Attend and Tell    
> Window selection: for a predict position pt, select [t-D, t+D] to attend on    
>    
> 3. Make attention jointly at each time: Input-feeding approach     
> send the attention h_t to the next input x_t+1

[Memory Networks](https://arxiv.org/abs/1410.3916)
> 

[End-To-End Memory Networks](https://papers.nips.cc/paper/5846-end-to-end-memory-networks.pdf)
> 

[Neural Turing Machines](https://arxiv.org/abs/1410.5401)
>

## Variational Autoencoder, Variational RNN
[Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)
>
> these two blogs are great on understanding VAE https://jmetzen.github.io/2015-11-27/vae.html https://jaan.io/unreasonable-confusion/

[Tutorial on Variational Autoencoders](https://arxiv.org/abs/1606.05908)
>

[A Recurrent Latent Variable Model for Sequential Data](http://papers.nips.cc/paper/5653-a-recurrent-latent-variable-model-for-sequential-data.pdf)
> 

[Sequential Neural Models with Stochastic Layers](https://arxiv.org/pdf/1605.07571.pdf)
> 
