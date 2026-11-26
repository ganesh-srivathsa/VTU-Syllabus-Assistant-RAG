🎓 VTU Syllabus Assistant – AI-Powered RAG Chatbot

An intelligent academic chatbot that allows students to interact with VTU syllabus documents and get answers to their questions using Retrieval-Augmented Generation (RAG).

🚀 Project Overview

The VTU Syllabus Assistant is built using Python, Ollama, Gemma, EmbeddingGemma, and ChromaDB.

Students can upload a VTU syllabus PDF and ask questions about subjects, semesters, modules, course outcomes, and recommended textbooks.

The system retrieves relevant information from the uploaded document and uses a Large Language Model (LLM) to generate context-aware answers.

✨ Features
Upload PDF syllabus documents.
Extract text from PDF files.
Split documents into smaller chunks.
Generate text embeddings using EmbeddingGemma.
Store embeddings in ChromaDB.
Retrieve relevant information using semantic search.
Generate answers using Gemma 3 1B through Ollama.
Interactive chatbot interface using Gradio.
🛠️ Technologies Used
Technology	Purpose
Python	Programming language
Google Colab	Development environment
Ollama	Local LLM runtime
Gemma 3 1B	Answer generation
EmbeddingGemma	Text embeddings
ChromaDB	Vector database
PyPDF	PDF text extraction
Gradio	Chatbot interface
🏗️ System Architecture
Upload VTU syllabus PDF.
Extract text using PyPDF.
Split text into smaller chunks.
Generate embeddings using EmbeddingGemma.
Store vectors in ChromaDB.
Convert user questions into embeddings.
Retrieve relevant document chunks.
Pass retrieved context to Gemma.
Generate the final answer.


▶️ How to Run
Open the project notebook in Google Colab.
Install the required Python packages.
Install and start Ollama in the Colab runtime.
Download the required models:
gemma3:1b
embeddinggemma
Execute the notebook cells in order.
Upload a VTU syllabus PDF.
Process the document and start asking questions.
Launch the Gradio interface.

Note: Ollama must be running in the Colab runtime. The Gradio demo link is temporary and requires an active runtime.
LIVE Demo Section
https://ba8c2da14aa88de724.gradio.live/?utm_source=chatgpt.com

🎯 Project Objective

To develop an AI-powered academic assistant that helps students easily understand and explore their university syllabus through natural-language conversations.

🔮 Future Enhancements
Support multiple PDF documents.
Add semester-wise subject filtering.
Improve retrieval accuracy.
Display source pages for answers.
Add conversation memory.
Support additional university syllabi.
👩‍💻 Author

Developed as an academic project to explore Retrieval-Augmented Generation, Large Language Models, vector databases, and AI-powered applications.

⭐ Acknowledgements

Thanks to the open-source communities behind Ollama, ChromaDB, Gradio, and Python.
