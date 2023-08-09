# AI Huggingface
Reading URLS and generating answers based on users questions:

---

### Introduction
This code repository contains code that demonstrates the integration of various modules from the LangChain library for text processing and natural language processing tasks. The provided code illustrates the use of Hugging Face models for text embeddings, loading content from PDFs and URLs, vectorization using FAISS, and question answering employing a retrieval-based model.

### Code Components

The code is organized into distinct sections, each with a specific purpose:
1.	**Environment Setup**: The code begins by setting the environment variable "HUGGINGFACEHUB_API_TOKEN" to authenticate and access the Hugging Face model hub.
2.	**Import Statements**: The code imports essential libraries and modules from the LangChain library. These include text splitters, embeddings, vector stores, question answering chains, document loaders, and more.
3.	**Usage Example 1**: **Document Loading from URLs:** The code demonstrates how to load content from URLs using the UnstructuredURLLoader.
4.	**Usage Example 2**: **Splitting the Data and Vectorization:** The code showcases how to create a vectorized index using the VectorstoreIndexCreator class. It utilizes Hugging Face embeddings and a character-based text splitter.
5.	**Usage Example 3**: **Retrieving Answers from Questions:** The code utilizes a retrieval-based question answering chain. It loads a language model from the Hugging Face model hub, configures a retrieval-based chain, and links it to the vectorized index.
6.	**Usage Example 4**: **User Interaction for Question Answering:** The code includes a user interaction loop where users can input questions. The code then retrieves answers based on the input questions and displays them.

