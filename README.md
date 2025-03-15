# AI Product Description Generator using Gemini Pro
This project demonstrates how to deploy a Google Gemini Pro machine learning model for generating product descriptions automatically. 

## Description
This is an AI-powered product description generator that uses Gemini Pro and HugginFace Flan-T5 models. 

Given the name of the product, key features, and optionally the product category, this streamlit app uses a Flan-T5 model to generate the product category and then uses all this information in a Gemini Pro model to generate a compelling product description for use by the sales team.

## Prerequisites
- Google AI Studio Account
- Google AI Studio API Key
- Python 3.x
- Streamlit
- Hugging Face Account

Pip install requirements.txt to set up the environment and set your GOOGLE_API key as an environment variable under ```$GOOGLE_API_KEY``` variable.

Run the streamlit app using ```streamlit run app.py```.