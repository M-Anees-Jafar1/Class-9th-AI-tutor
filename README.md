# 📚 Class9-AI-Tutor (Conversational RAG with Llama-3)

An intelligent, conversational AI tutor designed to help Class 9 students learn Computer Science. Built using **Meta Llama-3-8B-Instruct** (quantized to 4-bit), **LangChain**, and **FAISS** vector database.

## 🚀 Key Features
* 🧠 **Conversational Memory:** Remembers past context (e.g., if you ask "What is X?" and then "What are the types of it?", it correctly resolves "it" using Llama-3 query reformulation).
* 📖 **Document-Augmented (RAG):** Answers are grounded strictly in the Class 9 Computer Science textbook PDF.
* ⚡ **Resource Optimized:** Model runs efficiently on a free T4 GPU in Google Colab using 4-bit quantization (`bitsandbytes`).

## 🛠️ Tech Stack
* **LLM:** `meta-llama/Meta-Llama-3-8B-Instruct`
* **Orchestration:** LangChain & LangChain-Community
* **Vector Store:** FAISS (Facebook AI Similarity Search)
* **Embeddings:** `all-MiniLM-L6-v2` (Hugging Face)
* **Quantization:** `bitsandbytes` (4-bit NF4)

## 💻 How to Run
1. Clone this repository.
2. Open the `.ipynb` notebook in Google Colab (with T4 GPU runtime).
3. Request access to Llama-3 on Hugging Face and use your Hugging Face Access Token to log in.
4. Upload your textbook PDF, run the cells, and start chatting!
