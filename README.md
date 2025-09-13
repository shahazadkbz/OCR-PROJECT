🖼️ OCR Text Extraction with Tesseract

This project demonstrates how to extract text from images using Tesseract OCR in Google Colab. It allows you to upload an image, preprocess it, and run Optical Character Recognition (OCR) to get the text content.

📂 Project Files

ocr.ipynb → Jupyter Notebook with OCR pipeline

README.md → Project documentation

🚀 Workflow
1. Install Dependencies

Install Tesseract OCR engine

Install required Python libraries: pytesseract, Pillow, opencv-python, matplotlib

2. Import Libraries

pytesseract → OCR engine interface

PIL.Image → Image loading

cv2 (OpenCV) → Preprocessing (grayscale, thresholding)

matplotlib → Display images in Colab

google.colab.files → Upload images

3. Define OCR Function

Load the image

Convert to grayscale

Apply thresholding for cleaner text detection

Extract text using pytesseract.image_to_string()

4. Upload & Display Image

Upload any .jpg / .png file containing text

Preview the uploaded image

5. Run OCR & Extract Text

Extract and display recognized text

(Optional) Save extracted text into .txt file

🛠️ Tech Stack

Python

Tesseract OCR

OpenCV

Pillow (PIL)

Matplotlib

📌 Future Improvements

Improve preprocessing with adaptive thresholding

Handle multilingual OCR

Export results in structured formats (CSV, JSON)
