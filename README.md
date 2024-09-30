# Azure OpenAI Workshop

This repository provides a collection of Jupyter notebooks demonstrating various methods for creating ChatGPT-like experiences over your own data. It leverages Azure OpenAI Service to access models such as `gpt-35-turbo` and `gpt3`, and integrates with vector stores like Pinecone, Redis, and Azure Cognitive Search for data indexing and retrieval.  

All the samples were designed to help enterprise developers who are new to generative AI. This repository provides step-by-step, hands-on tutorials and deep dives into various aspects of OpenAI's API using Jupyter Notebooks.

## Learning Objectvies

- **Prompt Engineering**: Examples of basic to advanced prompt creation.
    - 1.Prompts_Basic.ipynb
    - 2.Prompts_Parameters.ipynb
    - 3.Prompts_More.ipynb
- **Word Embeddings**: Techniques for generating and utilizing word embeddings.
    - 4.Word_Ebeddings.ipynb
- **Retrieval-Augmented Generation (RAG)**: Implementing RAG patterns.
    - 5.RAG.ipynb
    - 6.LoadData.ipynb
- **Local LLM Model**: Implementing RAG patterns locally downloaded LLM.
    - 7.Local-Llama2-RAG.ipynb
- **Use MongoDB for embedding**: MongoDb Embedding
    - 8.MongoDb_Embeddings.ipynb

## Getting Started

### Prerequisites

- Python 3.8+
- Azure OpenAI Service
- Jupyter Notebook

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/cyberkoolman/openai.workshop.git
    cd openai.workshop
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Configure your environment variables by copying the `.env.sample` file to `.env` and updating the necessary values.

### Usage

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the notebook of your choice and follow the instructions.
