# 🩺 Medical Assistance Chatbot

An AI-powered Medical Assistance Chatbot built using Python and Streamlit that provides medical information through a conversational interface. The chatbot leverages a pretrained medical language model along with a structured disease dataset to answer user queries related to symptoms, diseases, and precautions.

> **Disclaimer:** This project is intended for educational and learning purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.

---

# ✨ Features

* Interactive chatbot interface built with Streamlit
* Answers medical-related queries in natural language
* Uses a pretrained medical language model
* Integrates a structured disease dataset containing:

  * Disease Name
  * Description
  * Symptoms
  * Precautions
* User-friendly interface
* Fast response generation

---

# 🛠️ Tech Stack

| Technology                | Purpose                 |
| ------------------------- | ----------------------- |
| Python                    | Backend Development     |
| Streamlit                 | Frontend Interface      |
| Hugging Face Transformers | Medical Language Model  |
| Pandas                    | Dataset Processing      |
| PyPDF                     | PDF Processing          |
| Torch                     | Deep Learning Framework |

---

# 📂 Project Structure

```text
medical-assistance-chatbot/
│
├── app.py
├── requirements.txt
├── data/
│   ├── medical_book.pdf
│   └── disease_dataset.csv
│
├── models/
├── utils/
├── images/
└── README.md
```

---

# ⚙️ How It Works

1. The user enters a medical query through the Streamlit interface.
2. The backend processes the query.
3. The pretrained medical language model interprets the user's question.
4. Information from the structured medical dataset is used where applicable.
5. The chatbot generates and displays a response.

---

# 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/sakshi-maurya1/medical-assistance-chatbot.git
```

Move into the project folder:

```bash
cd medical-assistance-chatbot
```

Create a virtual environment:

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

# 📊 Dataset

The chatbot utilizes:

* A medical reference PDF
* A structured disease dataset containing:

  * Disease
  * Description
  * Symptoms
  * Precautions

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience with:

* Python application development
* Streamlit web applications
* Hugging Face Transformers
* Medical language models
* Natural Language Processing (NLP)
* Dataset preprocessing
* Prompt-based AI applications
* AI project deployment workflow

---

# 🚧 Future Improvements

The next version of this project will include:

* Retrieval-Augmented Generation (RAG)
* Pinecone or ChromaDB vector database
* Semantic search using embeddings
* Source citations in responses
* User authentication
* Conversation history
* Voice input
* Multilingual support
* FastAPI backend
* Docker deployment

---

# 📸 Screenshots

Add screenshots of:

* Home Page
* Chat Interface
* Sample Medical Query
* Generated Response

---

# 👩‍💻 Author

**Sakshi Maurya**

GitHub: https://github.com/sakshi-maurya1

LinkedIn: https://www.linkedin.com/in/sakshi-maurya-a495a7216/

---

# 📜 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ on GitHub.
