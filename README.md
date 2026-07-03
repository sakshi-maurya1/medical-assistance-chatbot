# 🩺 Medical Assistance Chatbot

An AI-powered Medical Assistance Chatbot that provides reliable medical information using Retrieval-Augmented Generation (RAG). The chatbot combines information from medical textbooks and structured disease datasets to answer user queries with relevant, context-aware responses.

> ⚠️ **Disclaimer:** This chatbot is intended for educational and informational purposes only. It is **not a substitute for professional medical advice, diagnosis, or treatment.**

---

## 📌 Features

- 🤖 AI-powered conversational medical assistant
- 📚 Answers questions using trusted medical documents
- 🔍 Semantic search with vector embeddings
- 🧠 Retrieval-Augmented Generation (RAG)
- 📄 Supports PDF medical books as knowledge sources
- 🦠 Disease dataset containing:
  - Disease Name
  - Description
  - Symptoms
  - Precautions
- 💬 Interactive Streamlit interface
- ⚡ Fast and relevant responses using vector search

---

## 🏗️ System Architecture

```
                  User Query
                       │
                       ▼
              Streamlit Frontend
                       │
                       ▼
            Embedding Generation
                       │
                       ▼
          Pinecone Vector Database
                       │
        Retrieve Relevant Documents
                       │
                       ▼
             Large Language Model
                       │
                       ▼
               Final AI Response
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Streamlit | Frontend |
| LangChain | RAG Pipeline |
| Pinecone | Vector Database |
| Sentence Transformers / BioClinicalBERT | Embeddings |
| BioGPT / Medical LLM | Response Generation |
| PDF Knowledge Base | Medical Reference |
| Pandas | Dataset Processing |
| PyPDF | PDF Text Extraction |

---

## 📂 Project Structure

```
medical-assistance-chatbot/
│
├── app.py
├── requirements.txt
├── data/
│   ├── medical_book.pdf
│   └── disease_dataset.csv
│
├── vectorstore/
│
├── embeddings/
│
├── utils/
│
├── models/
│
├── images/
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/sakshi-maurya1/medical-assistance-chatbot.git

cd medical-assistance-chatbot
```

### Create Virtual Environment

```bash
python -m venv venv
```

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file and add:

```env
PINECONE_API_KEY=your_api_key
PINECONE_ENVIRONMENT=your_environment
OPENAI_API_KEY=your_api_key
```

*(Modify according to the APIs used in your project.)*

---

## ▶️ Run the Project

```bash
streamlit run app.py
```

---

## 📊 Dataset

The chatbot utilizes:

- Medical textbook (PDF)
- Disease dataset containing:
  - Disease
  - Symptoms
  - Description
  - Precautions

The dataset is converted into semantic embeddings and stored in Pinecone for efficient retrieval.

---

## 🔍 How It Works

1. User enters a medical query.
2. The query is converted into embeddings.
3. Pinecone retrieves the most relevant medical documents.
4. Retrieved context is sent to the language model.
5. The chatbot generates a context-aware response.

---

## 🚀 Future Improvements

- Voice-based interaction
- Multi-language support
- Medical image analysis
- Drug interaction checker
- Appointment booking integration
- Chat history
- User authentication
- Deployment on AWS/Azure

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Chat Interface
- Sample Conversation
- Response Output

Example:

```
images/
    home.png
    chatbot.png
    output.png
```

---

## 👩‍💻 Author

**Sakshi Maurya**

- GitHub: https://github.com/sakshi-maurya1
- LinkedIn: https://www.linkedin.com/in/sakshi-maurya-a495a7216/

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- LangChain
- Streamlit
- Pinecone
- Hugging Face
- BioGPT
- BioClinicalBERT
