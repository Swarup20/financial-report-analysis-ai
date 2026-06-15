# Financial Report Analysis

## Problem Statement
Financial documents such as balance sheets and earnings reports contain
dense numerical and textual data, making manual analysis time-consuming.
This project builds an AI-powered system to extract and summarize key
financial insights from financial document images.

## Approach
1. Financial document images are loaded using Python.
2. Text is extracted from images using Tesseract OCR.
3. Extracted data is structured and prepared for analysis.
4. An open-source language model (FLAN-T5) generates a financial summary.

## Tools and Technologies
- Python
- Google Colab
- Tesseract OCR
- HuggingFace Transformers (FLAN-T5)
- PIL, Matplotlib

## Output
The system generates a concise, investor-friendly summary highlighting
key financial metrics, trends, risks, and overall financial health.

## Note on API Credits
Due to limited API credits, the project uses a free open-source language
model instead of paid vision APIs. The complete AI pipeline is implemented
and is deployable with paid APIs if required.
