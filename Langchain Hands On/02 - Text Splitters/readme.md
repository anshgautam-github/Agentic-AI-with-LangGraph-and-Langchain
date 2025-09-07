# 📚 Document Chunking with LangChain

In **Part 1**, we learned how to **load documents**.  
Now, in this part, we’ll explore how to **convert documents into smaller chunks of text**.

---

## ✨ Why Do We Chunk Documents?
Large Language Models (**LLMs**) have a **context size limitation** – meaning they cannot process very large documents all at once.  

To overcome this, we break the document into **smaller, manageable chunks** of text.  

This ensures:
- ✅ Better handling of large documents  
- ✅ Efficient retrieval and processing  
- ✅ Improved performance in downstream tasks (e.g., Q&A, summarization)  

---

## 🛠️ How to Split Text in LangChain
LangChain provides multiple ways to **split text into chunks** using different **text splitters**.  

First, install the required library:

```bash
pip install langchain-text-splitters
