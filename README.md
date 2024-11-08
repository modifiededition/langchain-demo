# RAG Application with LangChain and LangGraph

This repository demonstrates building both **stateful** and **stateless Retrieval-Augmented Generation (RAG)** applications using [LangChain](https://github.com/hwchase17/langchain) and [LangGraph](https://github.com/langgraph).
## Features

- **Content Fetching**: Retrieves content directly from websites.
- **Chunking and Indexing**: Processes and chunks content for optimal indexing and retrieval.
- **Complex Runnable Creation**: Uses LangChain Expression Language to define a runnable chain that combines various components for streamlined content retrieval.
- **Prompt Template Design**: Constructs dynamic prompts to answer user queries based on retrieved content.
- **Conversational Experience**: Wraps the LangChain application with LangGraph, defining a schema that ensures relevant information is persisted across calls.

## Technical Stack

- **LLM**: OpenAI GPT-4-mini for generating responses.
- **Vector Database**: Chroma for vector storage and similarity search.
- **Embedding and Similarity Scoring**: Uses OpenAI embeddings to represent text and perform similarity-based content retrieval.
