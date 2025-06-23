# N8N

Each activity is called a **Node**. There are a lot of connectors available in n8n.

It has options to use this in the cloud or self-host on our own server.

The core concept remains the same for an automation: a **Trigger** and an **Event**.

Supports many **AI automations** and **AI agents**.

---

## Different Tools / Alternatives

1. Zapier  
2. Make – Not so good for AI agents  
3. LangChain → LangGraph → LangFlow  
4. n8n  
5. FlowWise – Build LLM apps easily; in the background uses LangGraph  
6. AutoGen – Only for AI agents  
7. Crew AI  
8. Swarm from OpenAI  
9. Agency Swarm – Specifically for AI agents  
10. Voiceflow  
11. BotPress – Easy to work with but expensive  

**Main priority is n8n and FlowWise.**

---

## OpenAI API Key

Visit open AI platform page and follow instructions. Straightforward and easy to follow.

---

## Test Time Compute

Based on selected models. Models think and then provide a response, and this thinking takes time. This is called **test time compute**.

Thinking also needs tokens. They are expensive and slow. So, based on the use case, we need to evaluate whether thinking models need to be used.

These models are great for:
- Logic
- Math
- Code

For creative writing, thinking models are not necessarily required.

---

## Function Calling in LLMs

Using the function calling service, we can provide more functionalities with LLMs.

Examples include:

- LLMs calling other LLMs  
- Interacting with browser services  
- Using audio and video services  
- Calling custom Python functions  
- Accessing file systems  
- Working with embeddings

## Vector Databases

### Embeddings

- Embeddings are numeric representations (vectors) of text, images, or other data.  
- They don’t "group" data in the traditional sense. Instead, they encode semantic meaning into a fixed-length vector (e.g., a 768-dimensional array).
- These vectors are stored in a vector database, where they can be efficiently compared and searched based on similarity (e.g., cosine similarity).

### Vector Databases

- Vector databases store high-dimensional vectors — often with hundreds or thousands of dimensions (not just 3D).
- They allow for fast similarity search across large datasets using algorithms like HNSW or FAISS.

### LLMs

- LLMs can query vector databases (e.g., through similarity search) to retrieve semantically relevant chunks of data (documents, text, etc.), which are then used to formulate answers or responses.
- This is a core part of Retrieval-Augmented Generation (RAG).
