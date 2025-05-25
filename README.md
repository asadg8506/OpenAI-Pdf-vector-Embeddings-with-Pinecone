# OpenAI-Pdf-vector-Embeddings-with-Pinecone
A lightweight Python pipeline that extracts text from PDFs, splits it into manageable chunks, generates OpenAI embeddings (text-embedding-ada-002), and stores them in Pinecone for blazing-fast semantic search. Ideal for building AI search over documents

# 📄 OpenAI PDF Vector Embeddings with Pinecone

This project extracts text from a PDF, chunks it into token-limited pieces, generates embeddings using **OpenAI's `text-embedding-ada-002`**, and stores those vectors in **Pinecone** for high-performance semantic search.

---

## 📌 Features

✅ Extracts full text from PDF  
✅ Splits text into `max 800` token chunks using `tiktoken`  
✅ Generates 1536-dimensional OpenAI embeddings  
✅ Stores vectors in Pinecone (auto-creates index)  
✅ Performs semantic search queries on embedded PDF content  

---

## 📂 Folder Structure

openai-pdf-vector-embeddings/
├── main.py # Core script
├── requirements.txt # Python dependencies
├── README.md # Project docs
└── AI.pdf # Your input PDF file (add manually)

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/asadg8506/OpenAI-Pdf-vector-Embeddings-with-Pinecone.git
cd OpenAI-Pdf-vector-Embeddings-with-Pinecone

2. Install dependencies
pip install -r requirements.txt

3. Add your keys in main.py
# Replace with your actual keys
openai_api_key = "sk-..."
pinecone_api_key = "pcsk-..."

4. Add your PDF file
Place your PDF file in the root directory and name it AI.pdf.
(Or change the path in main.py accordingly.)

▶️ Run the Project
python main.py
You’ll see:

✅ PDF text extracted successfully!
✅ Split into X chunks.
✅ All chunks embedded successfully!
✅ Embeddings stored in Pinecone!
🔍 Search Results:
🔍 Sample Search Output
🔍 Search Results:
- Score: 0.94
  Text: Artificial intelligence (AI) is the simulation of human intelligence in machines...

🧠 Technologies Used
Tool	Purpose
PyMuPDF (fitz)	Extract PDF text
tiktoken	Tokenize and chunk text
OpenAI API	Generate text embeddings
Pinecone	Store & search vectors
Python 3.x	Main programming language

📄 License
MIT License © 2025 Asad Ashfaq

🙋 Author
Asad Ashfaq
Campus Lead – AI Community of Pakistan
📧 asadashfaq101@gmail.com











