
# 🏛️ Indian Penal Code (IPC) Conversational AI Chatbot

Memory-Enabled Legal Question Answering System using RAG

## 📌 Project Overview

This project is a Conversational AI chatbot for the Indian Penal Code (IPC) that allows users to ask legal questions in natural language and receive accurate, context-aware answers from official IPC documents.

The system is built using Retrieval-Augmented Generation (RAG) and conversational memory, ensuring reliable responses grounded in legal text while supporting multi-turn conversations.

## 🚀 Key Features

- 📄 PDF-based Knowledge Ingestion (Official IPC document)

- 🧠 Conversational Memory for context-aware follow-up questions

- 🔍 Semantic Search using Vector Embeddings

- 🗂️ Chroma Vector Database for fast similarity retrieval

-  🤖 LLM-powered Response Generation

- ⚖️ Domain-specific AI for Legal Tech

## 🏗️ System Architecture

IPC PDF Document
       ↓
Text Extraction & Chunking
       ↓
Embedding Generation (OpenAI)
       ↓
Chroma Vector Database
       ↓
Retriever (Semantic Search)
       ↓
LLM + Context + Memory
       ↓
Conversational Legal Answers

## 🧪 Tech Stack

| Category    | Tools                        |
| ----------- | ---------------------------- |
| Language    | Python                       |
| Framework   | LangChain                    |
| LLM         | OpenAI                       |
| Vector DB   | ChromaDB                     |
| NLP         | Text Chunking, Embeddings    |
| Memory      | Conversational Buffer Memory |
| Data Source | IPC PDF                      |

## 🧠 How It Works

1.Document Loading
  The IPC PDF is loaded and converted into raw text.

2.Text Chunking
  The text is split into smaller overlapping chunks to preserve context.

3.Embedding Generation
  Each chunk is converted into vector embeddings.

4.Vector Storage
  Embeddings are stored in ChromaDB for efficient similarity search.

5.Query Handling
  User queries are matched with relevant IPC sections using semantic search.

6.RAG Pipeline
  Retrieved legal context is passed to the LLM for grounded response generation.

7.Memory Integration
  Conversation history is stored to support follow-up questions.

## 🧩 Example Use Case

User: What is the punishment for theft?
Bot: Provides IPC section, explanation, and legal context.

User: What if it is repeated?
Bot: Understands context and answers without re-asking details.

## Screenshots of Output
--
<img width="1353" height="524" alt="Screenshot (89524)" src="https://github.com/user-attachments/assets/2ee3a299-9025-4ad6-b2b8-6e53839af7ca" />

--
<img width="1356" height="510" alt="Screenshot (89526)" src="https://github.com/user-attachments/assets/b603b970-594a-4762-8cd4-069a56d9a8bb" />

--
<img width="1349" height="509" alt="Screenshot (89528)" src="https://github.com/user-attachments/assets/30541e96-67fe-4986-9e36-dad88a2d25ee" />

--
<img width="1363" height="506" alt="Screenshot (89532)" src="https://github.com/user-attachments/assets/b6fd0ac7-10ca-40d4-953a-e992586aeb43" />

--





## 📈 Project Outcomes

- Accurate legal responses grounded in IPC text

- Maintains conversational context across queries

- Demonstrates real-world RAG + Memory implementation

## Future Enhancements

- Web-based UI (Streamlit / React)

- Support for multiple Indian laws

- Role-based legal explanations

- Citations with IPC section numbers

