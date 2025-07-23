# Prompt-to-Animation-Manim-Animator-using-LLMs
Prompt-to-Animation is an AI-powered animation generator that converts natural language descriptions into fully executable Manim Community Edition Python code. Built using LLMs like Groq’s LLaMA 3.1, this tool enables creators, educators, and engineers to bring mathematical and conceptual ideas to life—without writing code manually.


**Prompt-to-Animation** is an AI-powered animation generator that transforms natural language descriptions into fully executable [Manim Community Edition](https://docs.manim.community/) Python code. It is designed for educators, researchers, and creators who want to visually explain mathematical and scientific concepts without writing complex animation code manually.

##  Overview

This project integrates **Groq’s LLaMA 3.1 model** with the **LangChain** framework to generate Manim animations directly from user prompts. It features a complete pipeline that includes:

- Prompt-based code generation  
- Manim code validation and rendering  
- Automatic video output display  
- Colab notebook integration for interactive execution  

##  Run on Google Colab

Use the project directly without any local setup:

🔗 [Launch in Colab](https://colab.research.google.com/drive/1JV3dTKxP0BWHTynykyCodXlX5NNPd-4c?usp=sharing)

## Working

1. **User Input**: You describe the animation in plain English.  
2. **LLM Generation**: The system uses Groq + LangChain to convert the prompt into clean, executable Manim CE Python code.  
3. **Execution**: The code is saved and rendered using Manim CLI.  
4. **Output**: The video is displayed or available for download within the notebook.  

## How to Get a Groq API Key

Follow these steps to obtain your Groq API key:

1. Go to the official [Groq platform](https://console.groq.com/playground?model=llama-3.3-70b-versatile) and sign up or log in.
2. Navigate to the **API Keys** section in your dashboard.
3. Click **Create API Key**.
4. Copy the generated key and use it in your environment.

In your Python code (Colab or script), set the key as:

```python
import os
os.environ["GROQ_API_KEY"] = "your-api-key-here"



