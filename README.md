# Work with different LLMs and parameters

A Python implementation task to work with different LLMs (Large Language Models) and request parameters

## 🎓 Learning Goals

By completing these tasks, you will learn:
- How can we configure LLM output via request parameters (`temperature`, `n`, `seed`, etc...)

## 📋 Requirements

- Python 3.13
- pip
- OPENAI API key
- ANTHROPIC API key

## 🔧 Setup

1. **Setup venv: (also can be configured via IDE)**
   ```bash
   python -m venv .venv
   ```
2. **Activate venv**
   Mac/Linux
   ```bash
   source venv/bin/activate
   ```   
   Windows
   ```bash
   venv\Scripts\activate.bat
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Project structure:**
   ```
   task/
   ├── models/
   │   ├── conversation.py          ✅ Complete
   │   ├── message.py               ✅ Complete  
   │   └── role.py                  ✅ Complete   
   ├── app/
   ├── ├──clients/
   │   │   ├── base.py              ✅ Complete
   │   │   ├── openaai_client.py    ✅ Complete
   │   │   └── anthpoic_client.py   ✅ Complete
   │   ├── constant.py              ✅ Complete
   │   └── main.py                  ✅ Complete
   ├── 1-task-models.py             🚧 TODO
   ├── 2-task-n.py                  🚧 TODO
   ├── 3-task-temperature.py        🚧 TODO
   ├── 4-task-seed.py               🚧 TODO
   ├── 5-task-max_tokens.py         🚧 TODO
   ├── 6-task-frequency_penalty.py  🚧 TODO
   ├── 7-task-presence_penalty.py   🚧 TODO
   └── 8-task-stop.py               🚧 TODO
   ```

## 📝 Your Tasks

Implement all tasks from these files:
- 1-task-models.py
- 2-task-n.py
- 3-task-temperature.py
- 4-task-seed.py
- 5-task-max_tokens.py
- 6-task-frequency_penalty.py
- 7-task-presence_penalty.py
- 8-task-stop.py     

