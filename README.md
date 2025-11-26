# CrewAI-News-Content-Generation
AI News Blog Content Generation with CrewAI

This project demonstrates **CrewAI**, a powerful **agent orchestration framework** that enables multiple AI agents to collaborate and autonomously complete complex tasks. Using CrewAI, we create a **Senior Researcher** agent to uncover the latest tech trends and a **News Writer** agent to craft engaging articles on those trends.  

---

## Why CrewAI?

CrewAI is at the core of this project and provides:  

- **Multi-Agent Coordination:** Easily manage multiple agents with specialized roles.  
- **Task Orchestration:** Execute tasks sequentially or in parallel with configurable dependencies.  
- **Memory & Context:** Agents retain knowledge and share context for coherent outputs.  
- **Delegation:** Agents can delegate subtasks to other agents for optimized workflow.  
- **Scalability & Customization:** Add or modify agents, tools, and tasks easily.  

CrewAI allows you to build complex workflows for research, content creation, summarization, or fully autonomous AI-driven pipelines.  

---

## Features

- **Autonomous Research:** Identify emerging trends and innovations in tech or AI topics.  
- **Content Creation:** Generate professional news articles and blogs from research findings.  
- **Flexible Task Execution:** Tasks can run sequentially or concurrently.  
- **Tool Integration:** Connect external tools like SerperDev for web searches and real-time data.  
- **Agentic AI Architecture:** Each agent has a defined role, memory, and backstory to improve creativity and reasoning.  

---

## Project Structure

- **agents.py:** Defines the Senior Researcher and News Writer agents.  
- **crew.py:** Orchestrates the crew and executes the workflow.  
- **tasks.py:** Contains research and writing tasks.  
- **tools.py:** Provides internet search capabilities via SerperDev.  
- **requirements.txt:** Lists all dependencies.  
- **.env:** Stores API keys and environment variables.  
- **new-blog-post.md:** Example output of generated news articles.  

---

## Installation

1. Clone the repository.  
2. Install dependencies from `requirements.txt`.  
3. Create a `.env` file with your API keys, including Gemini and SerperDev.  

---

## How It Works

1. **Agents:** Specialized AI agents are defined with specific roles and goals—one researches trends, the other writes articles.  
2. **Tasks:** Tasks are assigned to agents with expected outputs, e.g., reports or blog articles.  
3. **Crew:** Agents and tasks are grouped into a Crew managed by CrewAI, which orchestrates execution.  
4. **Execution:** CrewAI runs the workflow sequentially or in parallel, manages delegation, and stores context.  
5. **Output:** A polished news article or blog post is generated and saved.  

---

## Output

After execution, the system produces a structured news article that summarizes the latest trends in the specified topic. This output is saved as a markdown file for easy publishing.  

<img width="1214" height="704" alt="image" src="https://github.com/user-attachments/assets/ef125843-d230-4eab-9fc1-d6c584eedf51" />

<img width="1221" height="556" alt="image" src="https://github.com/user-attachments/assets/a13b664c-7845-4bca-971d-4183cef8f024" />
<img width="1207" height="601" alt="image" src="https://github.com/user-attachments/assets/e2170f2b-615e-4751-af8d-639eef1608aa" />
<img width="1217" height="599" alt="image" src="https://github.com/user-attachments/assets/afd717da-e713-41ac-84c3-911196c65aad" />
<img width="1224" height="502" alt="image" src="https://github.com/user-attachments/assets/52c65bf1-7680-4d3c-bbec-cc005aa48db0" />
<img width="1224" height="502" alt="image" src="https://github.com/user-attachments/assets/bc5b1b1e-1bfb-4415-92c9-3440d98db0a3" />


---

## Tools

**CrewAI:** Manages multi-agent workflows and orchestration.  
**SerperDev Tool:** Provides internet search capabilities for research.  
**LLM (Gemini 2.0 Flash):** Powers natural language understanding and content generation.  

---

If you want, I can also **draft a visually appealing diagram showing the CrewAI workflow with Researcher and Writer agents** for your README—it would make it more engaging for GitHub visitors.

Do you want me to create that diagram?
