# License Plate Detection and Text Extraction using Tesseract OCR
## License Plate Detection

Welcome to the repository for our project on license plate detection and text extraction using Tesseract OCR. This project demonstrates the process of detecting license plates in images and then utilizing Tesseract OCR to extract the text from those license plates.

### Project Overview
In this project, we focus on automating the task of license plate detection and text extraction. The primary steps include:

License Plate Detection: We use computer vision techniques to locate license plates within images. This involves object detection and localization.

Text Extraction: Once the license plates are detected, we employ Tesseract OCR to recognize and extract the text from the license plates.

Contents
license_plate_detection.ipynb: Jupyter Notebook containing the license plate detection pipeline using image processing and object detection.
images/: This directory contains sample images for testing the license plate detection and text extraction processes.
Getting Started
To run the license plate detection and text extraction processes locally, follow these steps:

Clone the Repository: Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/AbhishekSingh010/licence-plate-detector.git
Install Dependencies: Install the required Python packages using pip:

Detect License Plates: Open and run the license_plate_detection.ipynb notebook to detect license plates within sample images.

Text Extraction with Tesseract: Open and run the tesseract_ocr.ipynb notebook to use Tesseract OCR for text extraction from the detected license plates.

Model and Data
For license plate detection, we utilize a pre-trained object detection model. In this project, we demonstrate the process using sample images. However, a custom-trained model can be used for better accuracy on specific license plate types.

Tesseract OCR
Tesseract is an open-source OCR engine that we use to extract text from images. The integration involves preprocessing the detected license plates and then running Tesseract for text recognition.

Contribution
Contributions to this project are appreciated! If you encounter issues, have suggestions, or wish to enhance the project, please open an issue or submit a pull request.


License
This project is licensed under the MIT License, allowing you to modify and distribute the code for your purposes.

We hope you find this license plate detection and text extraction project informative and valuable. For any inquiries or feedback, feel free to reach out!
