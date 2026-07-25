# 🤖 SupportAI: Intelligent Helpdesk Agent using Hybrid Search and Large Language Models

SupportAI is an AI-powered customer support assistant that intelligently answers user questions using a combination of keyword search, semantic search (TF-IDF), and Large Language Models (LLMs). The project simulates a real-world helpdesk system by retrieving the most relevant FAQ, generating natural language responses, tracking conversations, and escalating unresolved queries to human support.

---

## 📌 Project Overview

Traditional FAQ systems rely only on keyword matching, which often fails when users ask paraphrased questions. SupportAI improves the customer support experience by combining multiple retrieval techniques with an LLM to provide accurate, conversational, and context-aware responses.

The system is built in four progressive stages:

- **Task 1:** FAQ Knowledge Base & Keyword Search
- **Task 2:** OpenRouter LLM Integration
- **Task 3:** Intelligent FAQ Matching using TF-IDF and Hybrid Search
- **Task 4:** Complete Multi-turn Helpdesk Agent

---

## 🚀 Features

- Structured FAQ Knowledge Base
- Case-insensitive Keyword Search
- FAQ Search by Category
- FAQ Search by ID
- TF-IDF Semantic Matching
- Cosine Similarity Ranking
- Hybrid Search (Keyword + TF-IDF)
- OpenRouter GPT-4o-mini Integration
- Context-aware Prompt Engineering
- Multi-turn Conversation Support
- Confidence-based Response Generation
- Conversation History Tracking
- Human Support Escalation
- Mock Ticket Generation
- Interactive Command-Line Chat Interface

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- Requests
- OpenRouter API
- GPT-4o-mini
- Google Colab
- Dataclasses

---

## 📂 Project Structure

```
supportai-intelligent-helpdesk-agent/
│
├── README.md
├── requirements.txt
├── SupportAI.ipynb
└── faqs.json
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/supportai-intelligent-helpdesk-agent.git
```

Move into the project folder:

```bash
cd supportai-intelligent-helpdesk-agent
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure OpenRouter API

Create an environment variable for your OpenRouter API key.

Example:

```python
import os

os.environ["OPENROUTER_API_KEY"] = "your_api_key_here"
```

The project uses the following model:

```
openai/gpt-4o-mini
```

---

## ▶️ Running the Project

Open the notebook:

```
SupportAI.ipynb
```

Run all cells from top to bottom.

The notebook demonstrates:

- FAQ creation
- Keyword Search
- LLM Integration
- Intelligent FAQ Matching
- Hybrid Search
- Complete Helpdesk Agent

---

## 📖 Project Workflow

```
                User Question
                      │
                      ▼
              Hybrid Search Engine
          (Keyword + TF-IDF Matching)
                      │
          ┌───────────┴───────────┐
          │                       │
          ▼                       ▼
   FAQ Found                 No FAQ Found
          │                       │
          ▼                       ▼
 OpenRouter GPT-4o-mini      Fallback Response
          │                       │
          ▼                       ▼
 Natural Language Reply    Human Escalation
          │
          ▼
 Conversation History
```

---

## 💡 Example

### User

```
I forgot my login credentials.
```

### SupportAI

```
No worries! To reset your password, click the "Forgot Password" option on the login page. Enter your registered email address, and a password reset link will be sent to your inbox. The reset link remains valid for 24 hours.
```

---

## 📊 Implemented Components

### Task 1

- FAQ Knowledge Base
- Keyword Search
- Search by Category
- Search by FAQ ID

### Task 2

- OpenRouter API Integration
- LLMClient Class
- Prompt Engineering
- Conversational Response Generation

### Task 3

- TF-IDF Vectorization
- Cosine Similarity
- FAQMatcher Class
- Hybrid Search

### Task 4

- SupportAgent Class
- Conversation History
- Confidence Scoring
- Human Escalation
- Interactive Chat Interface

---

## 📈 Future Improvements

- LangChain Integration
- FAISS / ChromaDB Vector Database
- Streamlit Web Application
- Conversation Memory
- RAG-based Document Retrieval
- Multi-language Support
- Authentication and User Profiles
- Real-time Database Integration

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing (NLP)
- Information Retrieval
- Prompt Engineering
- Large Language Models (LLMs)
- REST API Integration
- Semantic Search
- Hybrid Search Techniques
- AI-powered Customer Support Systems
- Object-Oriented Programming
- Python Application Development

---

## 👨‍💻 Author

**Harsha Bhukesh**

B.Tech – Computer Science and Engineering

Aspiring AI/ML Engineer

GitHub: https://github.com/Harsha-Bhukesh

LinkedIn:www.linkedin.com/in/elipeharshabhukesh

---

## 📄 License

This project is developed for educational purposes as part of an Artificial Intelligence and Machine Learning capstone project.
