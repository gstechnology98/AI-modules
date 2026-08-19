# AI-modules
## Module Name = Recipe Recommendation System
To create the system, we can follow these steps
# Step 1: Generate OpenAI API
Open this link and create API key <a href="https://platform.openai.com/api-keys" target="_blank" rel="noopener noreferrer">OpenAI API</a>

# Step 2: Create Virtual Environment
python -m venv env<br>
.\env\Scripts\activate.ps1

# Step 3: Install Necessary Libraries
pip install streamlit <br>
pip install openai <br>
pip install langchain_community

# Step 4: Import necessary libraries

import streamlit as st <br>
from langchain_community.llms import OpenAI

# Finally run the project using following code
streamlit run "app.py_file_path"
