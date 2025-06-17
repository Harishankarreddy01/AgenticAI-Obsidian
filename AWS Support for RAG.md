AWS provides powerful tools to build and scale Retrieval-Augmented Generation (RAG) systems easily and securely. Here are the key services:

---

## Amazon Bedrock

A fully-managed service to build generative AI apps using foundation models like Claude and Mistral.

### Why it helps:
- Connects models to **Knowledge Bases** (your data)
- Handles **chunking, vectorization, retrieval** for you
- No need to manage infrastructure

> Example:  
> Upload policy documents to S3 → Bedrock retrieves relevant parts when user asks,  
> “What’s our return policy for industrial tools?”