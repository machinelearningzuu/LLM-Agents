# LLM-Agents

## Core Concepts of LLM-Agents

### What is an Agent?
1. Perform tasks
2. Make decisions
3. Communicate with other agents

#### Three Components of a Good Agent
1. Good LLM (GPT-x, Mistral, Claude, Gemini)
2. Good Tools (Search, Calculate, Comparision, Shell, ...)
3. Good Agent Frameworks (LangGraph, LlamaIndex, LangChain, CrewAI)

##### Good LLM
1. Handle Long Contexts
2. Handle Long Outputs
3. Good at Reasoning

##### Good Tools
1. Efficient
2. Easy to Use
3. Easy to Extend
4. Easy to Integrate

##### Good Agent Frameworks
1. Good prompts that match the LLM (Same prompt not work for all LLMs)
2. Highly customizations of LLM Tools
3. Easy to use
4. Flexibility

### What is a Task?
- In the crewAI framework, tasks are specific assignments completed by agents. 
- They provide all necessary details for execution, such as a description, the agent responsible, required tools, and more, facilitating a wide range of action complexities.