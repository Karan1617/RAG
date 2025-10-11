# 🧠 RAG using Groq API

A minimal **Retrieval-Augmented Generation (RAG)** implementation using the **Groq API**.  
This project retrieves relevant context for a user query and generates an answer using a fast LLM (like LLaMA 3) via Groq.

There is **no frontend** — everything runs in the terminal.

---

## 💡 What It Does

1. Takes a user query from the terminal
2. Retrieves relevant document chunks or preloaded context
3. Sends the query + context to Groq's language model
4. Streams the response back in real time

---

## 🛠️ Requirements

- A Groq API key

---