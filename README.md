# Image-to-Text-OCR


# OCR Web Application with Keyword Search

This web application allows users to upload an image containing text in both Hindi and English, extracts the text using Optical Character Recognition (OCR), and provides a basic search functionality to find keywords in the extracted text.

## Features
- Upload an image in `JPEG`, `PNG`, or other formats.
- Extract text from the image.
- Search for keywords in the extracted text, with highlights on matches.

## Demo
You can try the live demo here: [Live Demo URL](#) 

## Installation (Local Setup)

To run this project locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/singhrimiumesh/Image-to-Text-OCR.git
cd your-repository

### 2. Create a Virtual Environment
python -m venv ocr_env
source ocr_env/bin/activate   # On Windows use: ocr_env\Scripts\activate

### 3. Install the Required Libraries
pip install -r requirements.txt

### 4. Run the Application (Gradio)
python app.py
