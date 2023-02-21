# language-models-comparison

> _Status: 🚧 WIP / throwaway / abandoned_

We review key advances in language modelling over the last ~10 years, leading up to the performance provided by tools like ChatGPT.

We provides Jupyter notebooks to demonstrate and contrast key concepts and capabilities.

## Contents:

1. [**N-gram language modelling**](./notebooks/language-models-comparison.ipynb)
2. TODO: **Recurrent Neural Networks (RNNs)**
    1. Explain how RNNs use a history of previous tokens to predict the next token
    2. Explain the "vanishing gradients" problem, approaches to address it e.g. LSTMs (Long Short-Term Memory) and GRUs (Gated Recurrent Units)
    3. Explain the unsolved limitations of RNNs
3. TODO...: [**What is a transformer?**](./notebooks/transformers.ipynb)
    1. Compare and contrast with RNNs.
    2. Use a simple example, such as predicting the next word in a sentence, to demonstrate how a transformer works.
4. TODO: **What is self-attention?**
    1. Explain that self-attention is based on computing a weighted sum of the input sequence, where the weights are determined by a learned attention mechanism.
    2. Use a diagram to illustrate how self-attention works, showing how the model can "pay attention" to different parts of the input sequence to make a prediction.
5. TODO: **How does the transformer architecture work?**
    1. Describe the transformer architecture in more detail, explaining that it consists of a series of encoder and decoder layers.
    2. Explain that each layer in the encoder consists of a self-attention mechanism followed by a feedforward neural network, while each layer in the decoder consists of a masked self-attention mechanism, a self-attention mechanism, and a feedforward neural network.
    3. Use a diagram to illustrate the transformer architecture, showing how information flows through the encoder and decoder layers to generate predictions.
6. TODO: **How are transformers trained?**
    1. Explain pre-training and fine-tuning phases
7. TODO: **How are transformers used in state-of-the-art NLP models?**
    1. Dive deeper into some of the state-of-the-art NLP models that use transformers, such as GPT and BERT.
