# smolagents

![smolagents license to call](https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/smolagents/license_to_call.png)

This module covers how to build effective agents using the [`smolagents`](https://github.com/huggingface/smolagents) library, which provides a lightweight framework for creating capable AI agents.

## Module Overview

This module provides a comprehensive overview of key concepts and practical strategies for building intelligent agents using smolagents. With so many open-source frameworks available, it's essential to understand the components and capabilities that make smolagents a valuable option—or to determine when another solution might be a better fit.  We'll explore critical agent types, including code agents designed for software development tasks, tool calling agents for creating modular, function-driven workflows and retrieval agents that access and synthesize information. Additionally, we'll cover the orchestration of mutiple agents, the integration of vision capabilities and web browsing to unlock new possibilities for dynamic and context-aware applications.

## Contents

### 1️⃣ [Why Use smolagents](./why_use_smolagents)

`smolagents` is one of the many open-source agent frameworks available for application development. Alternative options include `LlamaIndex` and `LangGraph`, which are also covered in other modules in this course. This library offers several key features that might make it a great fit for specific use cases, but there are also some limitations that may lead you to consider other solutions. This module explores the advantages and drawbacks of using `smolagents`, helping you make an informed decision based on your project's requirements.

### 2️⃣ [CodeAgents](./code_agents)

`CodeAgents` are the primary type of agent in **smolagents**. Instead of generating JSON or text blobs, these agents produce Python code to perform actions. This module explores their purpose, functionality, and how they work, along with hands-on examples to showcase their capabilities.  

### 3️⃣ [ToolCallingAgents](./tool_calling_agents)

`ToolCallingAgents` are the second type of agent supported by **smolagents**. Unlike `CodeAgents`, which generate Python code, these agents rely on JSON/text blobs that the system must parse and interpret to execute actions. This module covers their functionality, key differences from `CodeAgents`, and provides a coding example to illustrate their use.  

### 4️⃣ [Tools](./tools)

Tools are functions that an LLM can use within an agentic system, acting as essential building blocks for agent behavior. This module covers how to create tools, their structure, and different implementation methods using the `Tool` class or the `@tool` decorator. You'll also learn about the default toolbox, how to share tools with the community, and how to load community-contributed tools for use in your agents.  

### 5️⃣ [Retrieval Agents](./retrieval_agents)

Retrieval agents combine models with knowledge bases, allowing them to search, synthesize, and retrieve information from multiple sources. They leverage vector stores for efficient retrieval and implement **Retrieval-Augmented Generation (RAG)** patterns. These agents are particularly useful for integrating web search with custom knowledge bases while maintaining conversation context through memory systems. This module explores implementation strategies, including fallback mechanisms for robust information retrieval.  

### 6️⃣ [Multi-Agent Systems](./multi_agent_systems)

Orchestrating multiple agents effectively is crucial for building powerful, multi-agent systems. By combining agents with different capabilities—such as a web search agent with a code execution agent—you can create more sophisticated solutions. This module focuses on designing, implementing, and managing multi-agent systems to maximize efficiency and reliability.  

### 7️⃣ [Vision Agents](./vision_agents)

Vision agents extend traditional agent capabilities by incorporating **Vision-Language Models (VLMs)**, enabling them to process and interpret visual information. This module explores how to design and integrate VLM-powered agents, unlocking advanced functionalities like image-based reasoning, visual data analysis, and multimodal interactions.  

### 8️⃣ [Browser Agents](./browser_agents)

Browser agents are a specialized type of **vision agent** that enable web browsing with visual understanding. By integrating vision models, these agents can interact with web content in new ways, such as interpreting images, extracting relevant information from videos, and navigating web pages autonomously. This module covers various use cases, including dynamic content extraction and visual web automation.

## Resources

- [smolagents Documentation](https://huggingface.co/docs/smolagents) - Official docs for the smolagents library
- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) - Research paper on agent architectures
- [Agent Guidelines](https://huggingface.co/docs/smolagents/tutorials/building_good_agents) - Best practices for building reliable agents
- [LangGraph Agents](https://langchain-ai.github.io/langgraph/) - Additional examples of agent implementations
- [Function Calling Guide](https://platform.openai.com/docs/guides/function-calling) - Understanding function calling in LLMs
- [RAG Best Practices](https://www.pinecone.io/learn/retrieval-augmented-generation/) - Guide to implementing effective RAG
