# OCR-with-Tesseract
This Jupyter Notebook demonstrates how to perform Optical Character Recognition (OCR) on an image using Tesseract OCR and OpenCV. The extracted text is processed and optionally compared against data from a CSV file for validation or analysis. Ideal for automating text extraction from documents or screenshots.

🧠 Features:

Installs Tesseract OCR and required libraries.
Loads an image from local path.
Converts the image to grayscale for better text recognition.
Uses pytesseract to extract text from the image.
Optionally reads a CSV file for comparison.
Uses difflib for fuzzy matching or comparing extracted text.
