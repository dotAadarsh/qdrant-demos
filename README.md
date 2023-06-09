# Projects using Qdrant

- [Qdrant.tech](https://qdrant.tech/)
- [qdrant documentation](https://qdrant.tech/documentation/)

## Question and Answer on your data with qdrant

This project is a Question and Answer Chat Bot with knowledge from your own PDF files. We will use qdrant, a 
state-of-the-art open-source vector search engine, and OpenAI ada002 embeddings model to build out this console based 
application.

### What is qdrant?

Qdrant (read: quadrant ) is a vector similarity search engine. It provides a production-ready service with a 
convenient API to store, search, and manage points - vectors with an additional payload. Qdrant is tailored to 
extended filtering support. It makes it useful for all sorts of neural network or semantic-based matching, 
faceted search, and other applications.

Qdrant is released under the open-source Apache License 2.0. Its source code is available on [GitHub](https://github.com/qdrant/qdrant).

Our overall plan is to:
1. Create a new free qdrant cloud cluster
2. use pdfplumber to extract text from PDF and create embeddings
3. use qdrant to index the embeddings
4. use qdrant to search for the most similar embeddings based on a users input
5. Generate a response based on the most similar embedding

### Resource

- This project is from the [lablab-ai-Qdrant Example](https://github.com/lablab-ai/qdrant-q-and-a-on-pdf)
- [Article - Question and Answer on your data with Qdrant](https://lablab.ai/t/question-and-answer-on-your-data-with-qdrant)

## How to build a neural search service with BERT + Qdrant + FastAPI


### Resource
- [Neural Search Tutorial](https://qdrant.tech/articles/neural-search-tutorial/)

## Qdrant Tutorial: Text Similarity Search

This project utilizes Qdrant Vector Database to store Embeddings from Cohere's model and search using cosine similarity.

Resource

- [Qdrant Tutorial: Text Similarity Search](https://lablab.ai/t/qdrant-cohere-tutorial) 