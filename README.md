# Super Simple RAG Demo App for testing

This is a demo application for the testing documents and prompt engineering for a future larger scale RAG application.

To get started run:
NPM install

Create a .env file with the following 

NODE_ENV = development
OPENAI_API_KEY = <Add your own Open AI key>
MONGODB_ATLAS_URI = <MongoDB Connection String>

RAG input docs are stored in the pei_docs folder in Markdown files.

To create the embeddings:
NPM run embed

Embeddings are stored alongside text chunks in a MongoDB database. 
After populating the vector database, create a search index for the collection on MongoDB.

To Run in Dev mode:
NPM run dev



# RAG-DEMO
