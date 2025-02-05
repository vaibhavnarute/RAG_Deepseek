# RAG_Deepseek

## 📌 Overview
RAG_Deepseek is a **Retrieval-Augmented Generation (RAG)** system designed to enhance large language models (LLMs) with external knowledge sources. It enables efficient retrieval of relevant documents and integrates them into the generation process, improving response accuracy and contextual understanding.

## 🚀 Features
- **Document Retrieval:** Uses embedding-based search to fetch relevant documents.
- **Query Processing:** Enhances queries using NLP techniques.
- **Augmented Generation:** Integrates retrieved information with an LLM for accurate responses.
- **Multi-Document Support:** Handles multiple PDFs and text files.
- **Scalability:** Works with different embedding models and vector databases.

## 📂 Project Structure
```
RAG_Deepseek/
│-- LAWpal/                # Core application files
│-- app.py                 # Main application entry point
│-- rag.py                 # RAG model implementation
│-- requirements.txt       # Dependencies
│-- README.md              # Project documentation
```

## 🛠️ Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/vaibhavnarute/RAG_Deepseek.git
cd RAG_Deepseek
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```sh
python rag.py
```

## 📖 Usage
1. Upload documents (PDFs, text files, etc.).
2. Input a query in natural language.
3. The system retrieves relevant content and generates a response.

## 🧩 Technologies Used
- **Python** (Flask, FastAPI)
- **Hugging Face Transformers**
- **LangChain**
- **FAISS / ChromaDB** (Vector database)
- **DeepSeek / OpenAI LLMs**
- **Tesseract / OCR** (for extracting text from images)

## 🔥 Future Enhancements
- Support for real-time data sources.
- Integration with multiple LLM providers.
- Enhanced query understanding with reinforcement learning.

## 🤝 Contributing
Feel free to submit issues and pull requests to improve the project!

## 📜 License
This project is licensed under the MIT License.

## 📧 Contact
For any queries, reach out to [Vaibhav S. Narute](https://github.com/vaibhavnarute).

