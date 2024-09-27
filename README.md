# Azure OpenAI Workshop

This repository provides a collection of Jupyter notebooks demonstrating various methods for creating ChatGPT-like experiences over your own data. It leverages Azure OpenAI Service to access models such as `gpt-35-turbo` and `gpt3`, and integrates with vector stores like Pinecone, Redis, and Azure Cognitive Search for data indexing and retrieval.  All the samples were designed to help enterprise developers who are new to generative AI. This repository provides step-by-step, hands-on tutorials and deep dives into various aspects of OpenAI's API using Jupyter Notebooks.

## Features

- **Prompt Engineering**: Examples of basic to advanced prompt creation.
- **Word Embeddings**: Techniques for generating and utilizing word embeddings.
- **Retrieval-Augmented Generation (RAG)**: Implementing RAG using local models and MongoDB.
- **Vector Store Integration**: Integration with FAISS and other vector databases.

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

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
