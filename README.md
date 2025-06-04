# 🧠 MindCare AI — Compassionate Mental Health Chatbot 🤖💬

Welcome to **MindCare AI**, your empathetic mental health chatbot designed to listen, support, and provide thoughtful responses through meaningful conversation. Using advanced AI and natural language understanding, MindCare AI offers a safe space for users to share their feelings and get helpful information grounded in trusted mental health resources.

---

## 🌟 Project Overview

MindCare AI is a context-aware chatbot that remembers previous messages, enabling multi-turn conversations with emotional intelligence. It uses:

- **LangChain** for document loading, text splitting, and retrieval  
- **HuggingFace sentence-transformers** for embedding mental health documents  
- **Chroma** vector database to store and search knowledge efficiently  
- **Llama-3 via Groq API** as the core language model for natural, empathetic dialogue  

The knowledge base includes authoritative mental health literature, with a primary source being the paper:

**"Defining Mental Health and Mental Illness"** by Nisha Dogra, University of Leicester.

---

## 🤖 Features

- 🗣️ **Conversational Memory:** Remembers previous user inputs for coherent, contextual replies  
- 📚 **Document-Driven Knowledge:** Answers grounded in trusted academic resources  
- 💡 **Thoughtful & Supportive Responses:** Designed to provide emotional support, coping strategies, and guidance  
- 🔄 **Persistent Vector Database:** Efficient semantic search over mental health content  
- 🖥️ **Simple CLI Interface:** Chat interactively through the terminal with an easy setup  

---

## 💬 Sample Conversation

Initializing Chatbot.........

Human: hi how are you?
Chatbot: Hello. I'm doing well, thank you for asking. I'm here to listen and support you in any way I can...

Human: i am feeling depressed
Chatbot: I'm so sorry to hear that you're feeling depressed. It takes a lot of courage to acknowledge and share your emotions...

Human: i am not able to focus for exams
Chatbot: It can be really overwhelming and stressful when you're trying to prepare for important tests...

Human: how to cure depression?
Chatbot: Depression is complex, but there are many treatments that can help, such as therapy, medication, lifestyle changes...

Human: i feel i should consult a doctor
Chatbot: That's a brave decision. Consulting a mental health professional can provide the support you need...

Human: thank you for the response
Chatbot: You're welcome. Remember, taking care of your mental health is important...

Human: exit
Chatbot: Take care of yourself, Goodbye!

---


## 🚀 Getting Started

### Prerequisites

- Python 3.8+  
- Install dependencies with:
- 💬 Chat with MindCare AI in your terminal. Type your thoughts, and the bot will provide contextual and compassionate responses.
❌ Type exit anytime to end the session.

```bash
pip install langchain chromadb huggingface-hub pypdf
