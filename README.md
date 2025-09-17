LangChain for LLM Application Development

Welcome to my LangChain for LLM Application Development repository! This repo contains all course materials, exercises, and practical examples from the short course taught by Harrison Chase and Andrew Ng.

LangChain is a powerful framework that expands the capabilities of Large Language Models (LLMs) for application development, allowing you to build intelligent, conversational, and reasoning-based applications.

Course Overview

You will gain hands-on experience with:

Models, Prompts, and Output Parsers – Call LLMs, craft prompts, and parse responses.

Memories for LLMs – Store and manage conversation context with buffer, window, token, and summary memories.

Chains – Create sequences of operations using LLMChain, SimpleSequentialChain, SequentialChain, and RouterChain.

Question Answering over Documents – Apply LLMs to proprietary data using retrieval-augmented generation (RAG) with vector embeddings.

Agents – Build reasoning agents that can interact with tools and Python code.

Evaluation and Example Generation – Generate examples and evaluate model predictions using LLM-assisted grading.

Repository Structure
LangChain_Course/
│
├── 01_Models_Prompts_Parsers.ipynb         
├── 02_Memories_for_LLMs.ipynb             
├── 03_Chains.ipynb                         
├── 04_QA_over_Documents.ipynb              
├── 05_Agents.ipynb                         
├── Data/                                   
│   └── OutdoorClothingCatalog_1000.csv
├── README.md                               
└── requirements.txt                        

Getting Started

Clone the repo:

git clone https://github.com/yourusername/LangChain_Course.git
cd LangChain_Course


Create a virtual environment:

python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows


Install dependencies:

pip install -r requirements.txt


Add your OpenAI API key in a .env file:

OPENAI_API_KEY=your_openai_api_key_here


Open and run the Jupyter notebooks to explore the examples.

Learning Outcomes

Build complex LLM applications using LangChain.

Implement conversation memory and multi-step reasoning chains.

Apply LLMs to real-world data for retrieval and QA.

Gain experience with LangChain Agents and evaluation techniques.
