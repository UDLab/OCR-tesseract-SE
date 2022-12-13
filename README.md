# OCR-tesseract-SE

OCR program based on [Pytesseract](https://pypi.org/project/pytesseract/) - a wrapper for [Tesseract](https://github.com/tesseract-ocr/tesseract). It includes language models to enhance the OCR performance.


## Getting started

* Install Tesseract
  * For Mac users: brew install tesseract
  * For Windows users: The latest installer can be downloaded from [here](https://github.com/UB-Mannheim/tesseract/wiki).
  * For Linux users: sudo apt install tesseract-ocr -y 
* Add tesseract path to system environment variable
* Download language models [here](https://github.com/tesseract-ocr/tessdata).

* [Google colab notebook](https://colab.research.google.com/drive/1c92lZX2qN5vVWksmfdMTnU0o_AmNxKhC#scrollTo=aszXshJGTq5u)


## Usage

* Run [OCR_singleImage.ipynb](https://github.com/ektavats/OCR-tesseract-SE/blob/main/OCR_singleImage.ipynb) to produce a searchable Pdf and OCR text as an output.
* Run [OCR_multipleImage.ipynb](https://github.com/ektavats/OCR-tesseract-SE/blob/main/OCR_multipleImages.ipynb) to process multiple images in batches.
* Run [OCR_textExtractor.ipynb](https://github.com/ektavats/OCR-tesseract-SE/blob/main/OCR_textExtractor.ipynb) to perform text detection using pytesseract.


## For non-technical users
If you are from non-technical background, and would like to set up pytesseract on your computer from scratch, please refer to instructions here: [Mac](https://github.com/ektavats/OCR-tesseract-SE/blob/main/How_to_install_tesseract_Mac.txt), [Windows](https://github.com/ektavats/OCR-tesseract-SE/blob/main/How_to_install_tesseract_windows.txt). The guide also includes instructions to set up python and virtual environment.


## Acknowledgements

* Our implementation is based on [Google's tesseract OCR engine](https://github.com/tesseract-ocr/tesseract).


## Contact

Ekta Vats (ekta.vats@abm.uu.se) <br />
Centre for Digital Humanities <br />
Uppsala University <br />
Sweden
