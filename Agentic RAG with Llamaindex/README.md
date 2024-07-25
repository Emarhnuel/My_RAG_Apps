This project builds a question-answering system for Airbnb listings using LlamaIndex, OpenAI's language models (gpt-4o-mini), and embeddings (text-embedding-ada-002). The system utilizes a subset of the MongoDB Airbnb dataset, performs embedding generation and storage in ChromaDB, and ultimately enables users to ask questions about Airbnb listings through a user-friendly interface.

# Key Features:
1. Data Processing: Cleans and prepares Airbnb listing data from the Hugging Face Datasets library.
2. Embedding Generation: Generates text embeddings using OpenAI's embedding model and stores them in ChromaDB for efficient retrieval.
3. LlamaIndex Integration: Uses LlamaIndex to create a VectorStoreIndex for semantic search and question-answering.
4. Query Engine: Implements a query engine tool to retrieve relevant information from the index based on user queries.
5. Agent Interaction: Demonstrates how to use a FunctionCallingAgentWorker to interact with the query engine tool and generate responses using the specified language model.

# Usage:
1. Install required packages: pip install -r requirements.txt
2. Set your Hugging Face token and OpenAI API key as environment variables.
3. Run the script to generate embeddings, build the index, and create the query engine.
4. Interact with the query engine by providing questions related to Airbnb listings.


Note: This project is intended for educational purposes and demonstrates the basic steps involved in building a question-answering system with LlamaIndex.