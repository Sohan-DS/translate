# Language Translation App

This repository contains a simple machine translation web application built using Streamlit. The application allows users to translate text into multiple Indian languages using the Google Translate API.

Live demo:  
https://translate0demo.streamlit.app/

## Features

- Real-time text translation
- Supports Malayalam, Hindi, and Tamil
- Simple and user-friendly Streamlit interface
- Lightweight and fast

## Project Structure

translate/  
├── translate.py  
├── requirements.txt  
└── README.md  

## Installation and Setup

1. Clone the repository  
git clone https://github.com/Sohan-DS/translate.git  
cd translate  

2. (Optional) Create and activate a virtual environment  
python -m venv venv  
source venv/bin/activate  
Windows: venv\Scripts\activate  

3. Install dependencies  
pip install -r requirements.txt  

4. Run the application  
streamlit run translate.py  

## How It Works

- User enters the text to be translated
- Selects the target language
- The application uses googletrans to translate the text
- The translated output is displayed on the screen

## Dependencies

- streamlit  
- googletrans==3.1.0a0  

## Deployment

This application is deployed using Streamlit Community Cloud.

## Author

Sohan-DS
