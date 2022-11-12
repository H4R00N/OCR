# OCR
Optical Character Recognizer takes a picture and converts it to text.

There are 2 classifiers, the first is digitClassifier, which is only for numbers, so it will convert handwritten numbers to text.
The second is charClassifier, which is for numbers and letters, so it will convert both handwritten characters to text.

If you want to run the .ipynb files for training the classifiers, you will need anaconda and jupyter note book installed.
Also, you will need to pip install cv2 and possibly other libraries used.
The training classifier files do not need to be accessed for OCR, they only needed to be used for creating the classifier saved as a .h5 file.

RUN OCR.ipynb to use OCR. It is configured to use charClassifier and test.jpg image.