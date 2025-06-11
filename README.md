## Agentic Workflow with LangGraph and SingleStore
This system implements an intelligent agentic workflow using LangGraph orchestration with dual knowledge sources. 
When users submit queries, the LangGraph agent analyzes and routes them appropriately: known topics are handled via SingleStore database using vector similarity search of custom knowledge, while unknown or current topics trigger web search for real-time external data. 
The agent intelligently decides the optimal path, retrieves relevant information, processes it through LLM generation, and delivers comprehensive responses. 
This hybrid approach ensures reliable answers from curated internal knowledge while maintaining access to up-to-date external information for complete query coverage.

### Prerequisites:
- Free [SingleStore account](https://portal.singlestore.com/intention/cloud?utm_medium=referral&utm_source=pavan&utm_term=github&utm_content=LangGraph)
- OpenAI API Key
- Tavily API Key
