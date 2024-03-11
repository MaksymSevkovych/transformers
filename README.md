# transformers

In this repository one can find various implementations concerning Large Language Models (LLMs) and transformer neural networks. 

In the `Bigram_to_Transformer` directory there is an extensive implementation based on [Adrej Karpathy's makemore playlist](https://www.youtube.com/@AndrejKarpathy/playlists). The goal is to develop a model which can create realistic names. We begin with a simple Bigram model and end up with a Multi-Head Attention Transformer network.

Moreover, in the `LoRA_finetuning` directory there is a short demo how to do a quick finetuning of an LLM using a Low Rank Adapter. 

Lastly, in the `MoE` directory one can find some code concerning Mixture of Experts (MoE) models. The idea and goal is to start with an ordinary Multi-Head Attention Transformer network and create a MoE-LLM.