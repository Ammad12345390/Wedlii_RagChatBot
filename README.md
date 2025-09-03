🤵 Wedlii RAG Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) Chatbot built for the Wedlii
 wedding platform.
This chatbot helps answer questions about Wedlii by retrieving information from uploaded Wedlii documents (PDF/DOCX) and generating clear, grounded responses.

✨ Features

📂 Ingests Wedlii PDFs and DOCX files (e.g., About Wedlii, Vendors, Venues, Blogs).

✂️ Splits content into searchable chunks for accurate retrieval.

🔍 Uses FAISS vector database with OpenAI embeddings for similarity search.

💬 Answers user queries using RAG (Retrieval + Generation).

🛡️ Sticks to Wedlii documents only (no hallucinations).

🔎 Provides source chunks for transparency.

⚙️ Tech Stack

Python 3.10+

LangChain

FAISS

OpenAI API
 (embeddings + LLM)
