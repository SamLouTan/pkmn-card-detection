# pkmn-card-detection
 AI Project M2

# Pokémon Card Detection from an Image

This project allows for detecting Pokémon cards from a given image and analyzing their content using various image processing and text recognition techniques.

## Features
- Contour detection and image reshaping.
- Text extraction from the image using Tesseract OCR.
- Analysis of detected cards using text similarity measures.

---

## Prerequisites

### Python Environment
Ensure Python is installed on your machine. This project also requires several Python libraries.

### Installing Tesseract
Download and install Tesseract OCR from the official site:  
[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)  

During installation, note the path to the `tesseract.exe` executable, as it will be needed to configure your project.

### Required Python Libraries
Install the following libraries:
```bash
pip install opencv-python pandas numpy matplotlib pytesseract scikit-learn imutils
