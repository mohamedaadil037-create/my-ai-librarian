# 🤖 My AI Librarian (RAG Chatbot)

This is a Retrieval-Augmented Generation (RAG) chatbot. 
It answers questions based ONLY on the text found in `data/z_phone_manual.txt`.

## How it Works
1. **Embeddings:** Uses `SentenceTransformer` to turn text into vectors.
2. **Retrieval:** Uses Cosine Similarity to find the best paragraph.
3. **Generation:** Uses `Flan-T5` to write a natural answer.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the bot: `python app.py`