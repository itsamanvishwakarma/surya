## Installation

Clone the repo and after that simply install the pip packge for that as it will also install all the required dependencies for that

```
pip install surya-ocr
```

## how to use the surya-ocr package & get the text from a pdf file

use the following command to run the OCR and the results will be saved in the final_results/{filename}

```
python ocr_text.py testpdf.pdf --langs hi,en
```

where testpdf.pdf is the file you want to run OCR on and hi,en are the languages you want to run OCR on.
