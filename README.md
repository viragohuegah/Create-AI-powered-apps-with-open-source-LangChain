# Create-AI-powered-apps-with-open-source-LangChain

<br>Mentee assignment from IBM Advance AI @ Infinite Learning Course completion of Create-AI-powered-apps-with-open-source-LangChain from [IBM Skills Network](https://apps.course-dev.skills.network/learning/course/course-v1:IND+GPXX06NCEN+v1/home)

We will creating:
1. Simple Chatbot: Universal interface for various LLMs. 
<center> <img src="/workspaces/Create-AI-powered-apps-with-open-source-LangChain/preview_chatbot/preview_simple_chatbot.png"> <center>

2. Cover Letter Bot: Working with prompts to create cover letter bot.
<center> <img src="/workspaces/Create-AI-powered-apps-with-open-source-LangChain/preview_chatbot/preview_coverletter.png"> <center>

3. Customer Support Chatbot: Building chains for chatbot support.
<center> <img src="/workspaces/Create-AI-powered-apps-with-open-source-LangChain/preview_chatbot/preview_customersupport.png"> <center>

4. Summarizer Bot: Utility Functions for Accessing and Storing Files. Indexes used for file access and storage.
<center> <img src="/workspaces/Create-AI-powered-apps-with-open-source-LangChain/preview_chatbot/preview_summarizer.png"> <center>

5. Friend Chatbot: Implementation of a memory interface for chatbots.
<center> <img src=""> <center>

6. Python Code Writer Bot: Setting up agents that can use tools such as Google Search, Wikipedia, or a calculator.
<center> <img src="/workspaces/Create-AI-powered-apps-with-open-source-LangChain/preview_chatbot/preview_coderunner.png"> <center>



## Table of Contents
1. [Mentee Info](#mentee-info)
2. [Technology](#technology)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Structure](#structure)
6. [Project Status](#project-status)
7. [Instructors](#instructors)


<a name="mentee-info"></a>
## Mentee Info
| Nama             | Program              |
| ---------------- | -------------------- |
| Rizqi Hairunnisa | IBM Advance AI 🤖🌊 |



<a name="technology"></a>
## Technology
- `python`
- `langchain`
- `langchain_openai` 
- `gradio`
- `chromadb`
- `tiktoken`
- `huggingface_hub`
- `wget`
- `pysqlite3-binary`
- `numexpr`
- `langchain_experimental`


<a name="setup"></a>
## Setup
You can setup your project by cloning this repository and install the libraries above.

For specific version of the libraries, please check the `my.env` directory. You can activate the libraries by using the command below.

```bash
source my_env/bin/activate
```

<a name="usage"></a>

## Usage
You can run each of the program by using the command below. For better GUI run on `Public URL`
- Simple Chatbot
```bash
python simple_llm.py
```
- Cover Letter Chatbot
```bash
python prompt_with_template.py
```

exercise output step by step,
```bash
python exercise_prompt_step_by_step.py
```

- Customer Support Bot
```bash
python chain_customerSupport.py
```

- Summarizer Chatbot
```bash
python summarizer.py
```

- Friend Chatbot
```bash
python memory.py
```

- Python Code Writer Bot
```bash
python coderunner.py
```

<a name="structure"></a>
## Structure
```bash
.
├── README.md
├── chain_customerSupport.py
├── coderunner.py
├── exercise_prompt_step_by_step.py
├── flagged
│   └── log.csv
├── hello.py
├── memory.py
├── my_env
│   ├── bin
│   ├── include
│   ├── lib
│   ├── pyvenv.cfg
│   └── share
├── pembukaanUUD1945.txt
├── prompt_with_template.py
├── simple_llm.py
└── summarizer.py

```

<a name="project-status"></a>
## Project Status
Project is: _complete_

<a name="instructors"></a>
## Instructors
- [@Ichsan Takwa](https://github.com/Ichsan-Takwa)