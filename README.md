# 🏡 RealEstate Research Tool

We are going to build a **user-friendly news research tool** designed for effortless information retrieval. Users can input article URLs and ask questions to receive **relevant insights** from the real-estate domain. *(But its features can be extended to any domain.)*

## ✨ Features

- 🔗 **Load URLs** or upload text files containing URLs to fetch article content.
- 📝 **Process article content** through **LangChain's UnstructuredURL Loader**.
- 🔍 **Construct an embedding vector** using **HuggingFace embeddings** and leverage **ChromaDB** as the vectorstore, to enable swift and effective retrieval of relevant information.
- 🤖 **Interact with the LLMs** (**Llama3 via Groq**) by inputting queries and receiving answers along with source URLs.

---

## 🚀 Set-up

1. 📥 **Install dependencies** by running the following command:
   ```sh
   pip install -r requirements.txt
   ```

2. 🔑 **Create a `.env` file** with your **GROQ credentials** as follows:
   ```sh
   GROQ_MODEL=MODEL_NAME_HERE
   GROQ_API_KEY=GROQ_API_KEY_HERE
   ```

3. ▶️ **Run the Streamlit app** using:
   ```sh
   streamlit run app/main.py
   ```


