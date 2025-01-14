# genAIPG
Generative AI Playground




## Requirements
1. **langchain:** Main library to implement the chain of tasks (document loading, splitting, vector store management, etc.).
    1. **langchain-community:** Community-contributed extensions for LangChain (e.g., additional vector stores).
    2. **langchain_huggingface:** Integration that allows you to use HuggingFace endpoints within LangChain.
    3. **langchain_ollama:** Integration that allows you to use ollama endpoints within LangChain.
    4. **langgraph:** Agent development and orchestration framework.
2. **ollama:** Python client for the Ollama LLM server, enabling local inference of Llama or other models.
3. **sentence-transformers:** Provides state-of-the-art sentence embedding models.
4. **Vector DBs**
    1. **chromadb:** A vector database for storing and retrieving text embeddings.
    2. **faiss:** A vector database for storing and retrieving text embeddings.
5. **pypdf:** PDF parsing library that helps extract text from PDF documents. 
