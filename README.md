# BizCardX-Extracting_Business_Card_Data_with_OCR
This project deals with creating a dashboard in Streamlit which enables us to extract the data from business card images with the help of easyOCR technology and transforming (and carrying out modification or updation in streamlit via python scripting ) to SQL for easy retrieval and further analysis with image and text processing.

# Introduction
BizCardX is a user-friendly tool for extracting information from business cards using Optical Character Recognition (OCR) technology. This project leverages the EasyOCR library to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. The extracted information is then accessible through a GUI built using Streamlit. The BizCardX application provides an intuitive interface for users to upload business card images, extract information, and manage the data within a database.

# Project Overview
BizCardX aims to simplify the process of extracting and managing information from business cards. The tool offers the following features:

1) Extraction of key information from business cards: company name, cardholder name, designation, contact details, etc.
2) Storage of extracted data in a MySQL database for easy access and retrieval.
3) GUI built with Streamlit for a user-friendly interface.
4) User options to upload, extract, and modify business card data.


# Libraries/Modules Used
pandas: Used to create DataFrames for data manipulation and storage.
mysql.connector: Used to store and retrieve data from a MySQL database.
streamlit: Used to create a graphical user interface for users.
easyocr: Used for text extraction from business card images.


# Workflow
a) Install the required libraries using the command pip install [Name of the library]. Install streamlit, mysql.connector, pandas, and easyocr.
b) Execute the BizCardX_main.py script using the command streamlit run BizCardX_main.py.
c) The web application opens in a browser, presenting the user with three menu options: HOME, UPLOAD & EXTRACT, MODIFY.
d) Users can upload a business card image in the UPLOAD & EXTRACT menu.
e) The EasyOCR library extracts text from the uploaded image.
f) Extracted text is classified using regular expressions to identify key information such as company name, cardholder name, etc.
g) The classified data is displayed on the screen and can be edited by the user if needed.
h) Clicking the "Upload to Database" button stores the data in a MySQL database.
i) The MODIFY menu allows users to read, update, and delete data in the MySQL database.


# How to Use
Clone this repository.
Install the required libraries using the pip install command.
Set up your MySQL database credentials in the appropriate places in your script.
Run the script BizCardX_main.py using the streamlit run command.
Use the web interface to upload business card images, extract information, and manage the data.
