# Urdu OCR Project | Code Saviours SI-26 | Amna Shahzad
# Research Summary
Optical Character Recognition (OCR) is a technology that converts text from scanned images or documents into editable and searchable digital text. Urdu OCR is more challenging than English OCR because Urdu uses a connected script, letters change shape based on their position, and many characters look similar. Urdu OCR can be used to digitize old books and newspapers and to convert printed forms and records into editable digital documents.
# Teserract Results
Image: /content/processed/0.png
Tesseract output: ای کی رر

Image: /content/processed/1.png
Tesseract output: ءا ملا ےار بھی

Image: /content/processed/10.png
Tesseract output: ک کک 
Image: /content/processed/100.png
Tesseract output: راف وی اما

Image: /content/processed/101.png
Tesseract output: ایا نان نی کے دا ریس الا مکی

# Why We Need a Better Model: 
**Tesseract fails on Urdu because** Urdu is a cursive script with connected characters, complex ligatures, and dots that are difficult to segment and recognize accurately using Tesseract's default OCR engine. In this experiment, the OCR output contained incorrect characters, missing words, repeated symbols, and meaningless text instead of the original sentences. Although preprocessing steps such as grayscale conversion, resizing, noise removal, and binarization improved the image quality, they were not sufficient to achieve accurate recognition. The results indicate that Tesseract's built-in Urdu language model is not well suited for this dataset, particularly for scanned documents with varying fonts and layouts. Therefore, more advanced preprocessing techniques (such as adaptive thresholding and deskewing) or modern deep learning-based OCR models are recommended to achieve better accuracy for Urdu text recognition.
