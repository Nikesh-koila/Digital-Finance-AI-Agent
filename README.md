# 💬 AI Agent for Digital Financial Literacy (IBM Watsonx RAG-Based Assistant)

This project is a conversational AI assistant built using **IBM Watsonx Agent Builder**. It helps users understand key digital financial concepts such as **UPI transactions**, **interest rates**, **budgeting**, and **online fraud prevention**, especially in the Indian context. The agent leverages **Retrieval-Augmented Generation (RAG)**, integrates web search tools, and provides accurate, real-time responses using a custom knowledge base.

---

## 🧠 Features

- 🔍 Retrieval-Augmented Generation using Watsonx
- 📄 Vectorized knowledge base of curated financial content (PDF)
- 🌐 Real-time integration with:
  - Google Search
  - DuckDuckGo Search
  - Wikipedia Search
- 💬 Natural language question answering
- 🇮🇳 Focused on Indian digital financial systems (e.g., UPI, RBI, SEBI)
- ☁️ Built and deployed entirely on **IBM Cloud**

---


## 🛠️ Tools & Technologies

- **Platform**: IBM Cloud  
- **Agent Builder**: IBM Watsonx  
- **Model**: Granite 3B Instruct (default), using LangGraph + ReAct  
- **Search Tools**: Google Search, DuckDuckGo, Wikipedia  
- **Storage**: IBM Cloud Object Storage for knowledge files  

---

## 🚀 How It Works

1. **Project Setup**: Created a new Watsonx Agent project on IBM Cloud.
2. **Tool Integration**: Enabled Google, DuckDuckGo, and Wikipedia search tools.
3. **Knowledge Upload**: Added and vectorized a curated PDF on Indian financial literacy.
4. **Instruction Design**: Defined the agent's role, tone, and domain.
5. **Testing**: Asked real questions like “How to send money via UPI?” and reviewed responses.
6. **Deployment**: System hosted fully on IBM Cloud with a live test environment.

---

## 🧪 Sample Questions

- "How do I send money via UPI?"
- "What is the difference between fixed and floating interest rates?"
- "How can I avoid online payment fraud?"
- "What is a safe interest rate for personal loans?"

---

## 📈 Future Scope

- Add multilingual support (e.g., Kannada, Hindi)
- Integrate official financial APIs (e.g., RBI, SEBI feeds)
- Expand the knowledge base to cover taxation, insurance, credit scores
- Improve ranking and retrieval logic
- Deploy mobile/web interface for public access

---

## 📚 References

- [RBI Official Website](https://rbi.org.in)  
- [NPCI – Unified Payments Interface](https://www.npci.org.in)  
- [SEBI India](https://www.sebi.gov.in)  
- [IBM Watsonx Documentation](https://www.ibm.com/cloud/watsonx)  
- [Wikipedia](https://en.wikipedia.org)

---

## ✍️ Author

**Nikesh**  
IBM Cloud Learner | CSE Student | AI & Product Enthusiast  


