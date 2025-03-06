📄 **RAG PDF Chatbot**

An interactive Retrieval-Augmented Generation (RAG) chatbot for querying PDF documents using FAISS, LangChain, and Hugging Face models.

🚀 **Features**
* Upload PDFs and create a vector database using FAISS.
* Select LLMs (Meta-Llama-3, Mistral-7B) for generating answers.
* Conversational memory for maintaining context.
* Query documents and get AI-generated answers with source references.
* Gradio UI for a seamless user experience.

🛠️ **Tech Stack**
* LangChain – Conversational Retrieval & LLM Integration
* FAISS – Fast Document Indexing & Search
* Hugging Face – Embedding & LLM APIs
* Gradio – Interactive Web UI

🏗️ **Setup & Installation**
1. Clone the Repository
```
git clone https://github.com/yourusername/rag-pdf-chatbot.git
cd rag-pdf-chatbot
```

2. Install Dependencies
```
pip install -r requirements.txt
```
3. Set Your Hugging Face API Token
```
export HF_TOKEN="your_huggingface_api_key"
```
4. Run the Application
```
python app.py
```
📌 **Usage**

1. Upload a PDF file
2. Click "Create vector database" to process the document
3. Choose an LLM (Meta-Llama-3, Mistral-7B)
4. Enter your query in the chatbot
5. Receive AI-generated answers with source references

🎯 **Example Query**

* User: Summarize the key points from the document.  
* AI: [Generates a concise summary with references from the document]  

🤝 **Contributing**
Feel free to fork, raise issues, and submit pull requests!

📩 Contact: shivanshmital1909@gmail.com

🚀 Happy Chatting! 🎙️