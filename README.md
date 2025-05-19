## AI_Agent_LangGraph_Langchain Notebook

**Description**: This Jupyter Notebook demonstrates the development of an AI agent using LangChain, LangGraph, and related tools to build agentic AI applications. It showcases the integration of external tools like Arxiv, Wikipedia, and Tavily for real-time data retrieval, and leverages the Grok API for language model interactions. The notebook includes setup instructions, tool configurations, and a workflow for intelligent collaboration between agents and tools using a state graph.

**Key Components**:
- **Tool Integration**: Utilizes Arxiv, Wikipedia, and Tavily for querying academic papers, general knowledge, and real-time web search.
- **LLM Setup**: Configures a language model (Grok's `qwen-qwq-32b`) with tool-binding capabilities.
- **Workflow**: Implements a LangGraph state graph to manage agent-tool interactions, including task decomposition and conditional routing.
- **Example Queries**: Demonstrates practical use cases like querying Arxiv for paper details and searching for recent AI advancements.

**Purpose**: Ideal for AI engineers exploring agentic AI systems, tool-augmented LLMs, and workflow orchestration with LangChain and LangGraph.

**Dependencies**:
- `langchain`, `langgraph`, `langchain-community`, `langchain-groq`
- `python-dotenv`, `arxiv`, `wikipedia`
- Environment variables: `GROQ_API_KEY`, `TAVILY_API_KEY`
