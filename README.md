# Chatbot with LangChain and Llama2 / OpenAI

This project demonstrates the use of **LangChain** to create a chatbot powered by either **OpenAI's GPT** or **Llama 2**. The chatbot interfaces are built using **Streamlit** for easy web interaction, and the models can be switched based on your preference.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Setup](#setup)
- [Running the App](#running-the-app)
- [File Descriptions](#file-descriptions)
- [License](#license)
  
## Overview

The project consists of two different Python scripts:

1. **`app.py`**  
   This script uses **OpenAI's GPT-4** model, which is a paid service. You will need an OpenAI API key to use this version.

2. **`olamapp.py`**  
   This script uses the **Llama 2** model via **Ollama**. It is free and open-source. If you're looking for a cost-free solution, this is the version for you.

## Requirements

Make sure to install the required libraries using `requirements.txt`. You can install them by running:

```bash
pip install -r requirements.txt
