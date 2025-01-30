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


## Langchain Learning

## Langgraph Learning
1. Introduction
    1. [langgraph intro](GENAIPG/langgraph/basics/1_agent_intro.ipynb)
    2. [reducers](GENAIPG/langgraph/basics/1_agent_reducers.ipynb)
    3. [multi state](GENAIPG/langgraph/basics/1_agent_multi_state.ipynb)
2. React Agent
    1. [simple react agent](GENAIPG/langgraph/basics/2_react_agent.ipynb)
3. Agents with Tools
    1. [pre-defined](GENAIPG/langgraph/basics/3_agent_with_tools_1.ipynb)
    2. [custom-defined](GENAIPG/langgraph/basics/3_agent_with_tools_2.ipynb)
4. Agents with Memory
    1. [checkpointer](GENAIPG/langgraph/basics/4_agent_with_memory_1.ipynb)
5. Agents with Human-in-the-loop
    1. [HIL](GENAIPG/langgraph/basics/5_agent_with_HIL_1.ipynb)

