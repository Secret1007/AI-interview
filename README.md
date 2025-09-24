# AI-interview

## Week 1：LLM 基础与术语

### 一、LLM/RAG 基础问答
1. What is the Transformer architecture, and how is it used in LLMs?

>The Transformer architecture is a deep learning model introduced by Vaswani et al. in 2017, designed to handle sequential data with improved efficiency and performance than previous models like recurrent neural networks (RNNs) and long short-term memory (LSTMs).
It relies on self-attention mechanisms to process input data in parallel, making it highly scalable and capable of capturing long-range dependencies.
In LLMs, the Transformer architecture forms the backbone, enabling models to process large amounts of text data efficiently and generate contextually relevant and coherent text outputs.
>
>Transformer 架构是一种深度学习模型，由 Vaswani 等人在 2017 年提出，旨在比以往的循环神经网络（RNN）和长短期记忆网络（LSTM）更高效、更强大地处理序列数据。它依赖于自注意力机制（self-attention）来并行处理输入数据，从而具备极强的可扩展性，并能捕捉长距离依赖关系。在大型语言模型（LLM）中，Transformer 架构是核心骨干，使模型能够高效处理海量文本数据，并生成上下文相关、连贯的文本输出。

2.Explain the concept of "context window" in LLMs and its significance.
>The context window in LLMs refers to the range of text (in terms of tokens or words) that the model can consider at once when generating or understanding language. The significance of the context window lies in its impact on the model's ability to generate logical and relevant responses.A larger context window allows the model to consider more context, leading to better understanding and text generation, especially in complex or lengthy conversations. However, it also increases computational requirements, making it a balance between performance and efficiency.
