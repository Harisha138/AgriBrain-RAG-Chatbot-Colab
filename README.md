# AI-Powered RAG Chatbot for Agriculture

AgriBrain is a domain-specific, AI-powered chatbot designed to provide real-time agricultural assistance using a **Retrieval-Augmented Generation (RAG)** architecture. Built in Google Colab, it integrates powerful language models with document retrieval and structured evaluation, enabling accurate, context-aware answers to farmers' queries on crops, soil, pests, and more.

---

## 🚀 Project Highlights

- ✅ Retrieval-Augmented Generation pipeline using **LangChain**
- ✅ Semantic document search with **ChromaDB**
- ✅ Embedding generation using **Google Generative AI**
- ✅ Interaction powered by **Google Gemini Pro**
- ✅ Rigorous evaluation using **RAGAS** and **DeepEval**
- ✅ Real-time document ingestion from PDF knowledge bases

---

## 🧰 Tech Stack and Tools

| Tool/Library           | Purpose                                               |
|------------------------|-------------------------------------------------------|
| **Google Colab**       | Notebook-based development and testing                |
| **LangChain**          | LLM orchestration and RAG pipeline                    |
| **Gemini Pro**         | Large Language Model for response generation          |
| **ChromaDB**           | Vector store for context document retrieval           |
| **Google GenAI Embeddings** | Convert text into semantic vector representations |
| **PyMuPDFLoader**      | Extract text from agricultural PDFs                   |
| **RAGAS**              | Generate synthetic QA datasets for evaluation         |
| **DeepEval**           | Evaluate faithfulness, hallucinations, and precision  |

---

## 🔁 Workflow Overview

### 1. 📥 Document Ingestion
Load agricultural documents in PDF format using `PyMuPDFLoader`.

### 2. 🧹 Text Preprocessing
Clean and split documents into text chunks to prepare for embedding.

### 3. 🧠 Embedding Generation
Convert chunks into semantic vectors using **Google Generative AI Embeddings**.

### 4. 💾 Vector Storage
Store vectors in **ChromaDB** to enable fast and relevant document retrieval.

### 5. 🔍 Context Retrieval
Retrieve contextually relevant chunks based on user queries via LangChain retrievers.

### 6. 🧩 Prompt Engineering
Construct prompts using the retrieved context and memory buffers for coherent conversations.

### 7. 🤖 Answer Generation
Use **Gemini Pro** to generate responses grounded in retrieved information.

### 8. 🧪 Evaluation
Use **RAGAS** to generate a synthetic golden reference QA dataset.  
Evaluate answers using **DeepEval** for:
- ✅ Contextual precision and recall
- ✅ Faithfulness
- ✅ Answer relevancy
- ✅ Hallucination rate

---

## 📊 Evaluation Metrics

| Metric                  | Description                                             |
|-------------------------|---------------------------------------------------------|
| **Faithfulness**        | Measures factual correctness based on retrieved context |
| **Answer Relevancy**    | Assesses how relevant the generated answer is           |
| **Contextual Precision**| Checks if correct context was used                      |
| **Hallucination Rate**  | Identifies made-up or unsupported content               |

---

---

## ✨ Key Takeaways

- Developed a complete **RAG-based NLP pipeline** for agricultural assistance
- Applied **prompt engineering** and **retrieval chaining** using LangChain
- Built a **domain-specific vector knowledge base**
- Used **state-of-the-art evaluation** tools to assess answer quality
- Demonstrated practical integration of **LLMs with real-world data**

---

## 📚 References

- [LangChain Documentation](https://docs.langchain.com/)
- [Google Generative AI](https://ai.google/discover/generative-ai/)
- [ChromaDB](https://docs.trychroma.com/)
- [DeepEval](https://docs.confident-ai.com/)
- [RAGAS](https://github.com/explodinggradients/ragas)

