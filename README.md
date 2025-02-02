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

### Basics
1. [Models](GENAIPG/langchain/basics/models.ipynb)
2. [Prompts](GENAIPG/langchain/basics/prompts.ipynb)
3. [Langchain Function, Tools, and Agents](GENAIPG/langchain/basics/functions_tools_agents.ipynb)
4. Question Answering and RAG
    1. [Document QA](GENAIPG/langchain/qa-rag/DocQA.ipynb)
    2. [Webpage QA](GENAIPG/langchain/qa-rag/WebQA.ipynb)
5. [Summarisation](GENAIPG/langchain/summarizer.ipynb)


### Applications
1. [News IE](GENAI/langchain/apps/news_info_extraction.ipynb)
2. [Research Trend Analyser](GENAI/langchain/apps/research_trend_analyser.ipynb)

## Langgraph Learning

### Basics
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

### Applications
1. Research Assistant Chatbot
2. Literature Reviewer
    1. [v1](GENAIPG/langgraph/apps/literature_reviewer.ipynb)
        1. Multi-Agent Literature Reviewer
        2. Uses Search Tools (arxiv, travily)
        3. LLM-based report planning
    2. [v2](GENAIPG/langgraph/apps/literature_reviewer_v2.ipynb)
        1. Multi-Agent Literature Reviewer
        2. Uses user-uploaded input files (currently supports .txt only)
        3. User schema based report planning (reads from schema.txt)

## References
1. [Langchain Tutorials](https://python.langchain.com/docs/tutorials/)
2. [Langgraph Tutorials](https://langchain-ai.github.io/langgraph/tutorials/)
3. [Prompt Engineering Guide](https://www.promptingguide.ai/)
4. [Ollama Models](https://ollama.com/search)