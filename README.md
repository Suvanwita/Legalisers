# Legalisers - Legal Document Analysis Chatbot

A sophisticated legal document analysis system that combines RAG (Retrieval-Augmented Generation) with modern web technologies to provide intelligent document processing and chat capabilities.

## 🚀 Features

- Document upload and processing (PDF, DOCX support)
- Intelligent chat interface for legal document analysis
- RAG-based document retrieval and generation
- Real-time communication between frontend and backend
- Cross-Origin Resource Sharing (CORS) enabled for development

## 🛠️ Tech Stack

### Frontend
- React 18
- Vite
- Axios for API communication
- Modern CSS styling

### Backend
- FastAPI
- ChromaDB for document storage
- Sentence Transformers for text embedding
- Google's Generative AI
- spaCy for NLP tasks
- PyPDF2 and python-docx for document processing

## 📋 Prerequisites

- Node.js (for frontend)
- Python 3.x (for backend)
- npm or yarn package manager

## 🚀 Getting Started

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run development server:
   ```bash
   npm run dev
   ```
   The frontend will be available at http://localhost:5173

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install Python dependencies:
   ```bash
   pip install fastapi uvicorn chromadb sentence-transformers google-generativeai spacy pypdf2 python-docx
   ```

3. Run the FastAPI server:
   ```bash
   uvicorn legal_rag_api:app --reload
   ```
   The backend API will be available at http://localhost:8000

## 🏗️ Project Structure

```
.
├── README.md
├── backend/
│   └── legal_rag_api.py         # FastAPI backend server
└── frontend/
    ├── src/
    │   ├── components/
    │   │   ├── ChatBox.jsx      # Chat interface component
    │   │   ├── MessageBubble.jsx # Individual message component
    │   │   └── UploadBox.jsx    # Document upload component
    │   ├── App.jsx              # Main application component
    │   └── main.jsx             # Application entry point
    ├── index.html
    ├── package.json
    └── vite.config.js
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- [vanditajain-29](https://github.com/vanditajain-29)
- []
- []
- []
