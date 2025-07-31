# RAG-Chatbot-Assesment-Task-from-JVAI
## Financial Policy RAG Chatbot

Welcome to the Financial Policy RAG Chatbot!  
This notebook lets you interactively explore financial policy PDF documents using an AI-powered chatbot. It’s designed to help you ask smart questions, get answers with real source references, and quickly dig into the details of financial policies—no matter how complex the document.

---

## Quick Start Guide

**1. Get Started in Google Colab**

- Download or clone this repository.
- Open [Google Colab](https://colab.research.google.com/) in your browser.
- Upload the notebook file: `RAG_ChatBot (3).ipynb`.

**2. Install the Dependencies**

- Run the first few code cells to automatically install all required Python libraries (`langchain`, `chromadb`, `faiss-cpu`, `sentence-transformers`, `pypdf`, and more).
- No manual package installation needed!
- ```bash
pip install langchain chromadb faiss-cpu sentence-transformers pypdf PyPDF2 langchain_community
```

**3. Upload Your PDF**

- When prompted, upload your own financial policy PDF (any document you want to explore).
- The notebook will extract, split, and analyze its contents for you.

**4. Run All Cells**

- Click “Run All” or step through each cell.
- The notebook will extract key sentences, bullet points, and tables, then build a powerful semantic search database from your document.

**5. Start Chatting! **

- At the end, you’ll see a prompt:  
  `Type financial policy questions below (type 'quit' to quit):`
- Ask anything about your policy document—e.g.:
  - `What are the key financial objectives?`
  - `Tell me about debt management.`
  - `What does the budget say about infrastructure?`
- The chatbot will reply with answers pulled directly from your document, always showing the page and section for easy reference.

---

## 🛠️ Features

- **Semantic Search:** Finds answers that actually match your meaning, not just keywords.
- **Memory:** Remembers your last topic, so you can ask natural follow-ups.
- **Source References:** Every answer cites the page and section in your PDF.
- **Bullet Points & Tables:** Extracts and displays structured info for quick review.
- **Easy to Use:** No setup—just upload and run in Colab.

---

## ⚡ Requirements

- [Google Colab](https://colab.research.google.com/) (recommended for GPU support)
- Your financial policy PDF file

*All Python dependencies are installed automatically by the notebook.*

---

## 👀 Example Workflow

1. **Upload notebook to Colab.**
2. **Upload your PDF when prompted.**
3. **Run all cells.**
4. **Ask your questions in the chatbot cell.**
5. **Get answers with clear references to the source document.**

---

##  Notes

- This notebook uses the Flan-T5 model alongside sentence-transformer embeddings for smart retrieval.
- Works best with well-structured PDF documents (budgets, policy statements, reports, etc).
- For large PDFs, processing may take a few moments.

---

##  Need Help?

If you have questions or want to suggest improvements, please open an issue in this repository.

---

Happy exploring your financial policy documents with AI!
