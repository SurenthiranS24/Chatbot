# Chatbot
Multilingual Chatbot

This is a simple multilingual chatbot built with Streamlit and Hugging Face Transformers. It supports multiple languages and provides basic rule-based chatbot responses with translation capabilities.

Features

Supports multiple languages (English, Hindi, Tamil, Telugu, Malayalam, French, Spanish, German)

Uses Hugging Face facebook/m2m100_418M model for translations

Simple rule-based chatbot responses

Interactive UI built with Streamlit

Installation

Prerequisites

Make sure you have Python 3.7+ installed.

Clone the Repository

git clone https://github.com/your-username/multilingual-chatbot.git
cd multilingual-chatbot

Install Dependencies

pip install -r requirements.txt

Running the Chatbot

streamlit run app.py

File Structure

multilingual-chatbot/
│── app.py                # Main application script
│── requirements.txt       # Dependencies
│── README.md             # Documentation

Requirements

The required dependencies are listed in requirements.txt:

streamlit
transformers
torch
sentencepiece

Usage

Run the application using Streamlit.

Select your preferred language.

Enter a message and receive responses in the selected language.

Contributing

Feel free to fork the repository and submit a pull request with improvements.
