# BizCardX
# Extracting_Business_Card_Data_with_OCR
Bizcard Extraction is a Python application built with Streamlit, EasyOCR, OpenCV, regex function, and PSQL database.
It allows users to extract information from business cards and store it in a PSQL database for further analysis.

# Usage
1.Run the Streamlit application:

    streamlit run Extracting_Business_Card_Data_with_OCR.py
2.Access the application in your browser at http://localhost:8501.

3.Upload a business card image to extract the information.
 
4.The application will preprocess the image using OpenCV by resizing, cropping, and enhancing it.

5.The processed image will be passed to EasyOCR for text extraction. Install thisfor latest development of easyOCR
    
    pip install git+https://github.com/JaidedAI/EasyOCR.git

6.The extracted information will be displayed on the screen, and it will be stored in the PSQL database.

7.Use the provided options to view, update, or analyze the extracted data in the database.

# Technologies Used
- Streamlit
- Streamlit_lottie
- Python
- RegEx 
- EasyOCR
- OpenCV
- PSQL

# Acknowledgments
#### Streamlit - For building interactive web applications with ease.
#### EasyOCR - For text extraction from images.
#### OpenCV - For image preprocessing and manipulation.
#### PSQL - For the database management system.

# Features
- Extracts text information from business card images using EasyOCR.
- Utilizes OpenCV for image preprocessing, such as resizing, cropping, and enhancing.
- Uses regular expressions (RegEx) to parse and extract specific fields like name, designation, company, contact details, etc.
- Stores the extracted information in a MySQL database for easy retrieval and analysis.
- Provides a user-friendly interface built with Streamlit to upload images, extract information, and view/update the database.


