# Chatbot for PDFs using RAG MultiQuery Retriever



## Overview

This project focuses on developing a powerful chatbot capable of PDF retrieval, including the extraction of tables and text. The chatbot utilizes a Retrieval-Augmented Generation (RAG) MultiQuery Retriever for efficient and accurate information extraction from PDFs.

## Features

- 📄 **Document Loading**: Efficiently loads PDF documents for processing.
- 🔄 **Chunk Division and Deduplication**: Divides documents into manageable chunks and removes or deduplicates redundant chunks.
- 🤗 **Transformer Model**: Utilizes the "sentence-transformers/all-MiniLM-L6-v2" model from Hugging Face for embeddings.
- 🌐 **Ollama Server**: Runs locally to manage the retrieval and query processes.
- 🦙 **Llama3.1 Integration**: Incorporates the Llama3.1 model for generating responses.
- 🧩 **ChromaDB**: Embeds chunks and manages data using ChromaDB.
- 🔍 **Contextual Similarity**: Uses similarity scores to provide relevant context in responses.
- 💬 **Querying**: Prompts and queries the Llama3.1 model for accurate information retrieval.
- 📈 **Evaluation**: Evaluates the model using semantic similarity metrics.

## Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/pdf-chatbot-rag.git
    cd pdf-chatbot-rag
    ```

2. **Create a virtual environment and activate it**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Load the PDF document**
    - Place your PDF files in the `data/` directory.

2. **Run the server**
    - Start the Ollama server locally:
    ```bash
    python server.py
    ```

3. **Query the chatbot**
    - Use the interface provided to upload PDF documents and query the chatbot for information extraction.

## Process and Techniques

1. **Loading the Document** 📄
2. **Dividing into Chunks and Removing/Deduplicating Chunks** 🔄✂️
3. **Loading the Transformer Model from Hugging Face** 🤗
4. **Running Ollama Server Locally** 🌐⚙️
5. **Pulling Llama3.1** 🦙💻
6. **Embedding Chunks and Using ChromaDB** 🧩🗃️
7. **Using Context with Similarity Score** 🔍📊
8. **Prompting and Querying the Llama3.1 Model** 💬❓
9. **Evaluating the Model Using Semantic Similarity** 📈🔬

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.


## Acknowledgements

- Special thanks to my mentor for the guidance and support throughout this project.

