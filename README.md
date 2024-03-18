# Deeplearning.ai
This is my work on the short courses on https://www.deeplearning.ai/short-courses/ their material is outstanding and completely free. The present repository is meant as a personal reference. 

# Table of content
## Understanding and Applying Text Embeddings
The course has 6 lecture each very focus on developing intution and hand-on experince using VertexAI client.
- Create embeddings using `textembedding-gecko@001`
- Compute Cosine Similarity using the package on `sklearn`
- Load stackoverflow question/answer/tags from `BigQuery`
- Get embeddings on stackoverflow data by sending batches 
- Load LLM `text-bison@001`
- Dicusssion on `Temperature`, `Top p`, `Top k`. 
- Semantic Search 
    - Compute cosine similarity with ALL embedding respect to the question
    - Improve by creating index using `ScaNN`. Then find clossest embedding to the question.
    - Use LLM to decide use relevant information or provide not answer if closest embedding is not applicable.

## Building Application with VBector Databases
The course has 6 lecture each focus on building simple applications using a vector database. The course in general follow the following structure
- Load Data
- Create embeddings and load them into Pinecone the Vector Database for this course
- Do some business logic if needed for the particular application
- Get query and obtain closest embedding to the query
- Answer directly the query or pass the query through a LLM first.

# Disclaimer
I recognize the time people spend on building intuition, understanding new concepts and hand-on material. The material uploaded here are only for reference.