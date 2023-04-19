# MiFID_OpenAI
This repository consists of a collection of Jupyter notebooks that leverage the power of OpenAI to perform detailed analysis on financial regulation texts. Gain valuable insights into complex regulatory frameworks with the help of cutting-edge AI technology.

Using the [OpenAI Cookbook](https://github.com/openai/openai-cookbook/tree/main/examples), some internet tutorials ([Chat with a book](https://github.com/gkamradt/langchain-tutorials/blob/main/data_generation/Ask%20A%20Book%20Questions.ipynb), [ChatGPT Chatbot for Your PDF Files]([https://www.youtube.com/watch?v=ih9PBGVVOO4](https://github.com/mayooear/gpt4-pdf-chatbot-langchain)) and its video [GPT-4 'Warren Buffett' financial analyst](https://twitter.com/mayowaoshin/status/1640385062708424708)) I replicated some concepts and made python notebooks about them, and used the [_Markets in Financial Instruments Directive (MiFID)_](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A32014L0065) as reference document.

## List of notebooks
### 1. [MiFID_local](https://github.com/capm/MiFID_OpenAI/blob/main/MiFID_local.ipynb)
Using FAISS, Pinecone and `load_qa_chain`.
### 2. [Tutorial_Langchain](https://github.com/capm/MiFID_OpenAI/blob/main/Tutorial_Langchain.ipynb)
Using OpenAI different types of query retrievals.
### 3. [Securities-Brokers](https://github.com/capm/MiFID_OpenAI/blob/main/Securities-Brokers.ipynb)
Using OpenAI API, I translated the document to english and asked questions about it, then asked question using the original language (spanish).
