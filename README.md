# Web-Scale RAG Pipeline with Llama 3.1 + LangChain

A **Retrieval-Augmented Generation (RAG)** system built to retrieve and summarize **web-based data** using **LangChain**, **Llama 3.1**, and **Chroma**.  
This project demonstrates how to automatically extract information from live web sources, embed it, and generate grounded answers through Llama 3.1, enabling real-time insights from unstructured web content.

---

## 🚀 Project Overview
This project implements a **web data ingestion and retrieval pipeline** powered by **LangChain** and **Llama 3.1**.  
It automatically downloads, cleans, embeds, and indexes text from web pages.  
When queried, the system retrieves relevant snippets and crafts **context-aware summaries** or **answers grounded in actual data**.

The focus is on **reliability**, **transparency**, and **grounded generation** — producing accurate, source-backed responses to open-domain questions.

---

## 🧩 Tech Stack
- **LLM:** Llama 3.1 (via watsonx.ai interface)
- **Framework:** LangChain  
- **Embeddings:** Watsonx Embeddings (SLATE model)  
- **Vector Store:** ChromaDB  
- **Language:** Python  
- **Environment:** Google Colab  

---

## 📂 Project Structure
rag-webdata-llama3/
├── .gitignore
├── LICENSE
├── README.md
└── src/
└── rag_webdata_llama3.py


---

## ⚙️ How It Works
1. **Fetch Web Data:** Retrieve text from online sources using HTTP requests.  
2. **Preprocess & Split:** Clean whitespace and split content into smaller chunks.  
3. **Embed:** Generate embeddings using Watsonx Embeddings.  
4. **Store:** Save and query embeddings via **ChromaDB**.  
5. **Retrieve & Generate:** Use **Llama 3.1** to answer questions grounded in retrieved content.  

---

## 🧠 Key Features
- **Web-based RAG pipeline:** Processes unstructured web pages in real time.  
- **Grounded Llama 3.1 responses:** Ensures output is fact-based, not hallucinated.  
- **Efficient retrieval:** Vector search using Chroma for fast, accurate context lookup.  
- **Modular design:** Easy to replace document sources, models, or retrievers.  

---

## 🔒 Data Privacy
This repository does **not** contain any private data or API keys.  
If running locally, replace placeholders (`your_watsonx_instance_url`, `your_api_key`) with your own credentials.

---

## 🪪 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 👩‍💻 Author
**Kavitha Lingarajegowda**  
AI Product Management enthusiast passionate about scalable, retrieval-augmented systems that make complex information accessible and trustworthy.
