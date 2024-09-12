# DocChat
DocChat is a lightweight Retrieval-Augmented Generation (RAG) app that enables users to upload PDF documents and interact with them through natural language questions. Using Google's Gemini AI, this tool processes the content of PDF files and generates accurate answers based on the context of the documents. It provides a simple yet powerful interface for document-based conversational AI.

# ✨ Key Features
PDF Upload: Upload and process multiple PDF files.

Text Chunking: Break PDF text into manageable chunks for better retrieval and querying.

AI-Powered Q&A: Ask questions based on the uploaded PDFs and receive context-aware answers powered by Google Gemini AI.

Vector Store: Save and load document embeddings with FAISS for fast similarity searches.

# 🔧 Tech Stack
Streamlit: Provides the user interface for the app.

Google Gemini AI: Generative AI used to answer queries.

FAISS: Handles the creation and retrieval of vector embeddings from document chunks.

LangChain: Facilitates chaining conversational models.

PyPDF2: Used for extracting text from PDF files.

Google Generative AI Embeddings: For embedding document text into vectors.

# 🚀 Usage
Upload PDFs: Use the sidebar to upload one or more PDF files.

Process PDF: Click on the "Submit & Process" button to process the files and store them in the FAISS index.

Ask Questions: Enter a natural language query based on the uploaded PDFs in the main input box. The AI will respond with an answer derived from the document content.

# 🛠️ Future Enhancements
Expand support for other file types (e.g., DOCX).

Integrate document summarization capabilities.

Optimize search algorithms for faster, more relevant responses.


