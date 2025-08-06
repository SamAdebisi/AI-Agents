# AI‑Agents 🚀

**AI‑Agents** is a modular framework for building and orchestrating autonomous AI agents capable of complex multi-step reasoning, planning, tool use, and delegation. It leverages LLMs (e.g., GPT-4, Claude, LLaMA) via frameworks such as LangChain, LangGraph, and other agentic protocols to create goal-driven systems with real-world capabilities.

---

## Key Features

- 🔌 **Tool Integration**: Agents can invoke external tools (e.g., calculators, code runners, search APIs).
- 🧠 **Planning + Execution**: Agents first plan tasks and then execute them in a loop or sequentially.
- 🔁 **Reflexion Loop**: Agents reflect on their output and improve results through iteration.
- 👥 **Multi-Agent Orchestration**: Supervisor agents can delegate subtasks to sub-agents.
- 📝 **Modular Prompt Templates**: Customize agent behavior through prompt engineering.

---

## 🧠 Setup 

git clone https://github.com/SamAdebisi/AI-Agents.git
cd AI-Agents
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

---

Setup your openai [API key](https://platform.openai.com/)

Remember to deactivate the virtual environment once you're done by simply typing:
```bash
deactivate
```

---

## Set up your OAI_CONFIG_LIST file for autogen
- Create a file named: OAI_CONFIG_LIST containing your API keys for OpenAI as demonstrated below:

```
[
    {
        "model": "gpt-4o",
        "api_key": "YOUR API KEY HERE"
    }
]
``` 
