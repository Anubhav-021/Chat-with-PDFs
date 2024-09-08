# 📚 Chat with Your PDFs using Gemini and Streamlit

Welcome to Chat with PDF using Gemini—a powerful application that lets you interactively chat with PDF documents using Google's Gemini language model. Whether you're a student, researcher, or professional, this tool will help you quickly find answers from large PDFs by simply asking questions.

## 🚀 Features

1. Seamless PDF Processing: Upload multiple PDFs, and the app extracts and processes text for easy querying.
2. Advanced Text Chunking: Using RecursiveCharacterTextSplitter, text is split into manageable chunks for efficient retrieval.
3. Google Generative AI Embeddings: Harness the power of Google Generative AI for creating text embeddings that enhance the accuracy of document search.
4. FAISS Vector Store: Store and search through document embeddings with FAISS, ensuring fast and relevant responses to your queries.
5. Conversational AI: Utilize Google's Gemini model for precise and context-aware question-answering from your documents.
6. User-Friendly Interface: Built with Streamlit, the app offers an intuitive interface that requires no coding knowledge to use.
   
## 🛠️ How It Works

1. Upload PDFs: Drag and drop your PDF files into the sidebar uploader.
2. Process Text: Click on "Submit & Process" to extract and split text into chunks, which are then embedded and indexed.
3. Ask Questions: Type your question in the input field, and the app will search the indexed data, returning a detailed and contextually accurate answer.
   
## 🧠 Behind the Scenes
This app is powered by the following technologies:

Streamlit: For building a clean and interactive UI.
PyPDF2: To extract text from PDF documents.
LangChain: For managing text splitting, embeddings, and the QA chain.
Google Generative AI: For creating high-quality embeddings and generating conversational responses.
FAISS: For efficient similarity search and retrieval.
💡 Use Cases
Research: Quickly locate specific information in lengthy research papers.
Education: Students can query textbooks and lecture notes.
Business: Extract crucial insights from reports, manuals, or contracts.
🌟 Getting Started
To run the app locally, follow these steps:

📈 Future Enhancements
Multi-language Support: Extending support for PDFs in multiple languages.
Improved Chunking: Experimenting with different text-splitting techniques for better context retention.
Enhanced UI/UX: Adding more user customization options and visual improvements.
