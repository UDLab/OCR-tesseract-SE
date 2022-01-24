# OCR-tesseract-SE

OCR program based on pytesseract - a wrapper for [Tesseract](https://github.com/tesseract-ocr/tesseract). It includes language models to enhance the OCR performance.


## Getting started

* Install Tesseract
  * For Mac users: brew install tesseract
  * For Windows users: The latest installer can be downloaded from [here](https://github.com/UB-Mannheim/tesseract/wiki).
  * For Linux users: sudo apt install tesseract-ocr -y 
* Add tesseract path to system environment variable
* Download language models [here](https://github.com/tesseract-ocr/tessdata).


## Usage

* Run OCR_singleImage.ipynb to produce a searchable Pdf and OCR text as an output.
* Run OCR_multipleImage.ipynb to process multiple images in batches.
* Run OCR_textExtractor.ipynb to perform text detection using pytesseract.


## Acknowledgements

* Our implementation is based on [Google's tesseract OCR engine](https://github.com/tesseract-ocr/tesseract).


## Contact

Ekta Vats (ekta.vats@abm.uu.se)
