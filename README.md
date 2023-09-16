# OCR Text Extraction with Azure AI and Streamlit

## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)

## Overview

This project leverages Azure AI services for Optical Character Recognition (OCR) to extract text from images and PDF documents. The extracted text is then presented through a user-friendly web interface built using Streamlit, allowing users to easily upload and process their files.

## Demo

[Watch Demo Video](https://youtu.be/example-demo-video-link)

## Features

- **Text Extraction**: Utilizes Azure AI services to accurately extract text from a wide range of images and documents.
- **User-Friendly Interface**: Streamlit provides an intuitive and interactive interface for users to upload and process their files.
- **Customizable**: Easily extend or modify the project to suit specific requirements or integrate with other services.

## Getting Started

To get started with the project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/AjibolaMatthew1/text-extraction-azure.git
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Azure AI Credentials**:

   - Obtain Azure AI Cognitive Services API credentials and update the `.env` file.

4. **Run the App**:

   ```bash
   streamlit run app.py
   ```

   The app will be accessible at `http://localhost:8501`.


## Usage

1. Launch the app by running `streamlit run app.py`.
2. Open your web browser and go to `http://localhost:8501`.
3. Upload an image or PDF document.
4. Click the "Extract Text" button.
5. View and copy the extracted text.

