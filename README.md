# Multilingual_retriever_systems
This ipynb notebooks contains the code for retriveing relevant answers to queries given in over 100 languages from text wirtten in over 100 languages.
Directly run the ipynb notebooks after installing the following packages:
1) Cohere
2) Langchain

Load pdf files using PyPDFLoader and .txt files using TextLoader. The PyPDFLoader splits each page of the pdf as a separate text file. While passing a non english language it is preferred to use .txt files
with properly encoded text as the encoding sometimes become wrong with the PyPDFLoader.

The code is imlement using [Cohere Embeddings](https://docs.cohere.com/docs/multilingual-language-models) and [Langchain](https://python.langchain.com/docs/get_started/introduction.html)

It supports over 100 languages which are listed [here](https://docs.cohere.com/docs/supported-languages)
