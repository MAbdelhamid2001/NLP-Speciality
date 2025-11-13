- I have implemented a seq2seq model basic architecture using built-in Architecture and Layers
In Tensorflow, in an attempt to build an NMT `Neural Machine Translation` Model to convert `English` to `Arabic`
- according to the paper :
https://arxiv.org/abs/1409.3215

- Also, augmented the Seq2seq architecture with `Attention Mechanism` using TensorFlow built-in Layer
  which got more reasonable results than the seq2seq with only 100 epochs for training

- Benefits from this trial :
  * Knowing how data preparation is done for an NMT model
  * How the real seq2seq model works and how to connect inputs and outputs between Encoder and Decoder
  * How to make an Inference Model from the seq2seq and generate the Translations
>  **Note**: the original paper takes huge computational power and several weeks to train their model,
> 
>   So my model is considered a demo 
>
<img src="https://docs.chainer.org/en/stable/_images/lstm-rnn.png">
