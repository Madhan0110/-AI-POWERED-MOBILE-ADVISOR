## NOTE : Project File will show as invalid file , download it ad execute in your VSCode

# 📱 Mobile Details Chatbot

A conversational chatbot that answers questions about mobile phones using **semantic search (FAISS)** and a **local language model**, wrapped in an interactive **Gradio UI**.

---

## 🚀 Features

- 🔍 Semantic search using **Sentence Transformers**
- ⚡ Fast similarity search with **FAISS**
- 🤖 Local LLM for natural language responses
- 📊 Mobile dataset–driven answers
- 🌐 User-friendly **Gradio** web interface

---

## 🛠️ Tech Stack

- Python 3.9+
- Gradio
- Pandas
- Sentence-Transformers
- Transformers
- FAISS (CPU)

---

# 📂 Project Structure

├── Mobile_details_bot.ipynb # Main notebook
├── README.md # Project documentation
├── dataset.csv # Mobile phone dataset (if applicable)

# How It Works

1. Load Dataset – Mobile phone details are loaded using Pandas
2. Create Embeddings – Sentence Transformers convert text to vectors
3. Build FAISS Index – Enables fast similarity search
4. Load Local LLM – Generates human-like answers
5. Chat Logic – Matches user queries with relevant data
6. Gradio UI – Web-based chatbot interface

# 🧪 Running the Project

Open and run the notebook:
    code Mobile_details_bot.ipynb
Then execute all cells to launch the Gradio app.
