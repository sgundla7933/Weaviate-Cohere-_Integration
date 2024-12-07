# Weaviate-Cohere-_Integration

Introduction
This project integrates Cohere's language model and Weaviate's vector database to create an efficient information retrieval system. The system supports dense retrieval, keyword-based search, and response reranking to deliver precise results for natural language queries.

**Features**
**Dense Retrieval**: Uses Weaviate to fetch results based on vector embeddings for a given query.
Keyword Search: Executes keyword-based searches in the Weaviate database for specific properties.
**Response Reranking**: Leverages Cohere's reranking API to order results based on relevance.
**Prerequisites**
Python 3.8+
cohere Python SDK
weaviate Python SDK

**Setup Instructions**

**Clone the repository:**

git clone https://github.com/yourusername/weaviate-cohere-integration.git
cd weaviate-cohere-integration
**Install dependencie**s:

pip install cohere weaviate-client

**Set up API keys**:

Obtain your API keys from Cohere and Weaviate.
Replace the placeholders in COHERE_API_KEY and WEAVIATE_API_KEY in the script.
Run the script:

python main.py
**Usage**
Modify the query variable in the script to test various questions.
Use the dense_retrieval() and keyword_search() methods to experiment with different retrieval strategies.
The reranked responses can be tested with the rerank_responses() method.
Google slide presentation - https://docs.google.com/presentation/d/1C9enf-uxLhxAe2u5U2RhXCGcyC4_hVZQWQF69OxhnmQ/edit?usp=sharing
