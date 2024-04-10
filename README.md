# INVOICE OCR
Invoice OCR is a Python project for extracting key information from invoices using optical character recognition (OCR) techniques. It utilizes the Tesseract OCR engine to extract text from images of invoices and parses the extracted text to retrieve important details such as customer name, vendor name, invoice number, etc.

Features
Extracts key information from invoices using Tesseract OCR.
Parses the extracted text to retrieve specific details such as customer name, vendor name, invoice number, etc.
Supports various image formats including JPEG, PNG, and TIFF.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/invoice-ocr.git
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Place your invoice images in the images/ directory.

Run the main.py script:

bash
Copy code
python 
The extracted information will be saved to a JSON file named output.json.

Configuration
You can customize the project configuration by modifying the settings in the config.py file.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
This project utilizes the following open-source libraries:

Tesseract OCR
Pytesseract
Pillow
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements or feature additions.

Contact
For any inquiries or feedback, please contact harshalkotwal4@gmail.com.
