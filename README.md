# AI-interview

## Week 1：LLM 基础与术语

### 一、LLM/RAG 基础问答
1. What is the Transformer architecture, and how is it used in LLMs?

>The Transformer architecture is a deep learning model introduced by Vaswani et al. in 2017, designed to handle sequential data with improved efficiency and performance than previous models like recurrent neural networks (RNNs) and long short-term memory (LSTMs).
It relies on self-attention mechanisms to process input data in parallel, making it highly scalable and capable of capturing long-range dependencies.
In LLMs, the Transformer architecture forms the backbone, enabling models to process large amounts of text data efficiently and generate contextually relevant and coherent text outputs.

2.Explain the concept of "context window" in LLMs and its significance.
>The context window in LLMs refers to the range of text (in terms of tokens or words) that the model can consider at once when generating or understanding language. The significance of the context window lies in its impact on the model's ability to generate logical and relevant responses.A larger context window allows the model to consider more context, leading to better understanding and text generation, especially in complex or lengthy conversations. However, it also increases computational requirements, making it a balance between performance and efficiency.
