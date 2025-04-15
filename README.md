# 🧠 JOY – Mental Health Chatbot with LLaMA 3.3 & Streamlit

**JOY** is a friendly and empathetic AI chatbot designed to support mental wellness. Built with the **LLaMA 3.3 70B model**, JOY offers a beautifully styled user experience through Streamlit and uses AI to engage in emotionally aware conversations.

> 💬 "Hi, I'm JOY. I'm here to listen, support, and help you reflect. Let's talk."

---

## 🌟 Demo Avatar: Meet JOY

<img src="joy_avatar_drawing.png" alt="JOY Avatar Drawing" width="200"/>

---

## 🎨 Behind the Avatar: The Story of JOY

JOY’s avatar isn’t just a random illustration — it’s deeply personal.

> ✍️ "I was casually sketching one day, just doodling to relax. As I looked at what I created, it felt warm, calm, and expressive — the kind of presence I wished someone could have in tough times. That’s when I realized: this drawing could be JOY. I digitized it, cleaned it up, and gave it life as the face of this chatbot."

This drawing became the emotional foundation of JOY — a reminder that creativity and code can blend into care.

---

## 🚀 Overview

- 🤖 **Powered by LLaMA 3.3 70B** using LangChain & Groq API
- 📊 **Data Science pipeline** with PDF parsing, embeddings & vector similarity search
- 🎨 **Custom-designed frontend UI** using HTML/CSS inside Streamlit
- 🖼️ Avatar-driven user experience with JOY’s illustration
- ☁️ **Colab + ngrok** for live public deployment

---

## 🔍 Features

| Layer        | Description |
|--------------|-------------|
| **Frontend** | Streamlit + animated HTML/CSS + Avatar |
| **Backend**  | LangChain + Groq LLaMA 3.3 70B |
| **Data**     | PDF ingestion, chunking & HuggingFace embeddings |
| **Search**   | Contextual Retrieval with Chroma vector DB |
| **Deployment** | Google Colab with ngrok tunnel |

---

## 🧪 Data Science Components

- **Text Preprocessing**: chunking, cleaning, and structuring
- **Embedding**: HuggingFace `bge` models
- **Vector DB**: Chroma for context-aware document retrieval
- **LLM**: LLaMA 3.3 70B for generating replies
- **PDF Support**: Extract content from documents for context

---


---

## 🧑‍💻 How to Use This Project

All the code for this chatbot — frontend, backend, and data processing — is contained in a single Google Colab notebook:  
📘 `Mental_Health_Chatbot_GEN_AI.ipynb`

Follow these steps to get JOY running:



### 🚀 Getting Started in Google Colab

1. Open the notebook in [Google Colab](https://colab.research.google.com) and run the cells one by one.  
2. Install required Python packages by running:

   ```python
   !pip install langchain_groq streamlit pyngrok chromadb pypdf sentence_transformers langchain_community
3. Set up ngrok to make your Streamlit app public:

   - Create a free ngrok account 👉 https://dashboard.ngrok.com/get-started/setup

   - Copy your auth token from the ngrok dashboard.
  
4. Run the chatbot app and get your public link. Once the URL appears in the output, open it in your browser and start chatting with JOY 💬

## 🖼️ UI Preview
JOY’s interface includes:

- 🎬 Animated headers (fade-in title)

- 🧘‍♀️ Calming fonts and layout

- 💬 Chat and input bar

- 🖼️ Avatar always visible for warmth and connection

🛑 Disclaimer:
JOY is not a licensed mental health professional.
This chatbot is intended for support and education, not diagnosis or treatment.
If you're experiencing a mental health crisis, please contact a local mental health service or helpline.
  





