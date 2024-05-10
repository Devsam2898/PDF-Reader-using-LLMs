RAG on Complex PDF using Llama 3 8B, Langchain, LlamaParse, and Groq.
This project is a Jupyter notebook that demonstrates a multi-RAG (Retrieval Augmented Generation) PDF reader using the Llama 3 8B language model, LangChain, LlamaParser, and Groq. 
It allows you to query a collection of PDF documents and retrieve relevant information based on the query.

## Features

- Loads and processes PDF documents using LlamaParser
- Embeds the PDF content using a Groq-based embedding model
- Stores the embeddings and metadata in a Chroma vector store
- Provides a retriever to search for relevant documents based on a query
- Uses a custom prompt template for the question-answering retrieval
- Implements a ChatGroq class that extends the BaseLanguageModel from LangChain
- Generates responses to user queries by combining the retrieved documents and the language model

## Requirements

- Python 3.7 or higher
- Jupyter Notebook
- Llama 3 8B language model
- LangChain
- LlamaParser
- Groq
- Chroma vector store

## Usage

1. **Set up the required dependencies and libraries**
2. **Load and process the PDF documents using LlamaParser**
3. **Create a Chroma vector store and store the embeddings and metadata**
4. **Define a retriever to search for relevant documents based on a query**
5. **Set up a custom prompt template for the question-answering retrieval**
6. **Implement the ChatGroq class that extends the BaseLanguageModel from LangChain**
7. **Generate responses to user queries by combining the retrieved documents and the language model**
8. **Run the notebook and interact with the PDF reader**

## Example Query

```python
query = "What is the main topic of the paper?"
result = qa.run(query)
print(result)
```

This will execute the query against the PDF documents and display the relevant information.

## Acknowledgments

- Llama 3 8B language model
- LangChain
- LlamaParser
- Groq
- Chroma vector store

## License

This project is licensed under the [MIT License](LICENSE).
