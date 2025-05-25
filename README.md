# 🔍 Real-Time AI Search Agent – n8n

A real-time conversational search agent built using N8N, OpenAI’s GPT model, and SERP API. This intelligent AI agent captures user queries and responds with accurate, context-aware answers by combining live web search results and conversational memory.

---

## 📸 Screenshots

| Workflow | Agent Response |
|----------|----------------|


---

## 🧠 Key Features

- 💬 **Chat-Based Input**: Accepts user queries through chat.
- 🤖 **AI Agent Logic**: An AI agent built in n8n connects to OpenAI, simple memory, and SERP API to handle each request.
- 🌐 **Live Web Search**: Integrates SERP API to fetch the most recent and relevant data from Google.
- 🧠 **Simple Memory**: Maintains recent context to support follow-up queries and coherent conversation.
- ⚙️ **Modular Design**: Built in n8n, making the flow easy to customize and extend.

---

## 🛠 Tech Stack

- **n8n** – Workflow automation and orchestration  
- **OpenAI (Chat Model)** – Natural language understanding and generation  
- **SERP API** – Google Search results in real time  
- **Webhook/Chat UI** – Entry point for user queries  
- **Memory Handling** – Lightweight context management using n8n variables  

---

## ⚙️ How It Works

1. **User Sends a Query** via a chat interface.
2. The **AI Agent in n8n** receives the message and processes it.
3. The agent:
   - Retrieves live search results from **SERP API**.
   - References **simple memory** to maintain short-term context.
   - Passes all context and search data to **OpenAI’s chat model**.
4. **OpenAI** generates a natural, intelligent response.
5. The reply is sent back to the user through the chat or webhook response.

---


## 📈 Future Improvements

- Add long-term memory using database or vector storage  
- Deploy with a live chat UI (e.g., React frontend or Telegram bot)  
- Enhance response formatting and confidence scoring  
- Support voice input or image search extensions  

---





