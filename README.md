Image to PDF Text Extractor

Description

This project extracts text from an image using OCR (Optical Character Recognition) and saves the extracted text as a PDF file.

The user selects an image from the computer, and the program automatically reads the text inside the image. If text is found, it creates a PDF named Extracted_Text.pdf and saves it in the Downloads folder.

This project is useful for converting printed documents, notes, or screenshots into editable text stored in a PDF.

Features

- Select an image using a file picker.
- Extract text from the image using Tesseract OCR.
- Support for common image formats like PNG, JPG, JPEG, BMP, TIF, and TIFF.
- Save the extracted text as a PDF file.
- Automatically save the PDF in the Downloads folder.
- Show messages if no image is selected or no text is found.

Technologies Used

- Python
- Tkinter
- Pillow (PIL)
- pytesseract
- FPDF

Libraries Required

Install the required libraries before running the program.

pip install pillow pytesseract fpdf2

Also, install Tesseract OCR on your computer and update its installation path in the code if needed.

How It Works

1. Run the Python program.
2. Select an image from your computer.
3. The program reads the text from the image using OCR.
4. The extracted text is converted into a PDF.
5. The PDF is saved in the Downloads folder as Extracted_Text.pdf.

Output

- A PDF file named Extracted_Text.pdf containing the text extracted from the selected image.

Future Improvements

- Support multiple languages.
- Allow users to choose the PDF file name.
- Convert multiple images at once.
- Improve text formatting in the generated PDF.
- Add a simple graphical user interface with more options.