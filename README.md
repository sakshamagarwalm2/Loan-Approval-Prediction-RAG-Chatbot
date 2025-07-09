# 📘 LoanRAG Chatbot – A Retrieval-Augmented Generation (RAG)-Powered AI Assistant for Loan Eligibility Assessment

## 📌 Overview

**LoanRAG Chatbot** is an intelligent conversational assistant built using Retrieval-Augmented Generation (RAG) that allows users to inquire about loan eligibility, documentation, and approval-related queries. It integrates traditional loan eligibility logic with advanced LLM-powered responses while leveraging custom document knowledge for contextual and accurate guidance.

---

## 🚀 Features

- 🔍 **Retrieval-Augmented Generation (RAG)** for dynamic question-answering  
- 🧾 Handles real-time loan-related queries (eligibility, interest, documentation)  
- 🗂️ Document indexing for relevant information extraction  
- 🧠 LLM-backed natural language interface  
- ✅ Validates user inputs and assists with personalized eligibility assessments  

---

## 🏗️ Architecture

1. **FastAPI Backend**
2. **LLM Client (OpenAI/Azure)**
3. **Form Logic Validation**
4. **RAG Retrieval Pipeline**
5. **Session Management for User Context**

---

## ⚙️ Setup Instructions

# 1. Clone the repository
```
git clone https://github.com/sakshamagarwalm2/Loan-Approval-Prediction-RAG-Chatbot
cd LoanRAG-Chatbot
```
# 2. Create a virtual environment
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
```
# 3. Install dependencies
```
pip install -r requirements.txt
```
# 4. Configure environment variables
```
touch .env
```
