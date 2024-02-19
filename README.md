# OCR Arabic ID

Arabic Text detection in ID using PyTesseract and bounding boxes

## PyTesseract
Purpose: PyTesseract is a Python wrapper for Google's Tesseract-OCR Engine. It is primarily used to perform Optical Character Recognition (OCR) to read text from images.
Use Cases: It's specifically designed for extracting text from images. This makes it highly useful for reading text from scanned documents, images of text, screenshots, and areas within images where text is present.
Strengths:
Good at recognizing text in a variety of fonts and languages.
Can be fine-tuned and trained on new fonts or specific types of text.


## Structure

- Use Tesseract to detect text and bounding boxes
- Save output text to output.txt
- Save output image to output.jpg


## Installation

1- Installation of pytesseract  and Pillow

```
pip install pytesseract Pillow
```

2- Install OpenCV with Arabic Script and languages


## Run

Just add the path of the image and run the cell!


## Future work
Do more tests and preprocessing for images to optimize the detection of bounding boxes




