**Restaurant Name Generator**

This project is a Streamlit app that generates a restaurant name and corresponding menu items based on a selected cuisine.
It was built as part of a LangChain crash course to practice working with LLMs, chains, agents, and memory.

**Features**

Generate creative restaurant names for different cuisines

Suggest menu items tailored to the restaurant name

Interactive Streamlit UI for easy usage

Implements LangChain chains:

1.LLMChain

2.SimpleSequentialChain

3.SequentialChain

Demonstrates LangChain agents with tools like:

1.serpapi

2.wikipedia

3.llm-math

SerpAPI → An API that provides real-time Google search results (and other search engines) in JSON format.

Wikipedia Tool → A LangChain tool that fetches summaries and information directly from Wikipedia articles.

LLM-Math Tool → A LangChain tool that uses a language model to solve math problems step by step.

Uses LangChain memory (ConversationBufferMemory, ConversationBufferWindowMemory) to maintain context across queries

Hugging Face integration for lightweight local inference

**Tools & Technologies Used**

Python 3.x

Streamlit → for building the interactive web app

LangChain → for LLM chains, agents, prompts, and memory

OpenAI API → for text generation (with temperature control)

Hugging Face Transformers → integrated with LangChain for running models like google/flan-t5-base locally

SerpAPI → for search-based agent queries

Wikipedia API → for knowledge-based queries

Torch & Accelerate → backend for Hugging Face models

**Project Structure**

RestaurantNameGenerator/
│── app.py                         # Streamlit app entry point
│── langchain_helper_hug.py        # Helper functions using LangChain + HuggingFace
│── requirements.txt                # Dependencies
│── README.md                       # Project documentation
