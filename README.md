# Contains sample data and a few sample notebooks

# Notebooks
[Book Indexer](./notebooks/QueryWithContextFromEmbeddings.ipynb) converts book chapters into embeddings, indexes into pinecone, which can later be QnA'd using OpenAI API while context is populated using cosine-similarity generated from indexed documents.
[Query with context](./notebooks/QueryWithContextFromEmbeddings.ipynb) fetches context from indexed embeddings and queries for details using both Pinecone and OpenAI
