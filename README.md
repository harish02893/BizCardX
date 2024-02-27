# BizCardX
Extracting Business Card Data with OCR
Extracting Business Card Data with OCR
BizCardX is a Python application designed to extract information from business cards using Optical Character Recognition (OCR) technology. It utilizes various technologies such as Streamlit, EasyOCR, OpenCV, and MySQL to achieve this functionality

# Table of Contents
1.	Installation
2.	Usage
3.	Contributing
4.	License


# Installation
To install and run BizCardX, 

follow these steps:1.	Clone the repository:
bashCopy code
git clone https://github.com/your-username/bizcardx.git 
2.	Install the required dependencies:
bashCopy code
pip install -r requirements.txt 
3.	Set up the MySQL database by running the provided SQL script:
bashCopy code
mysql -u username -p < database_script.sql 
4.	Run the Streamlit application:
bashCopy code


## Usage
Once the application is running, follow these steps to extract data from business card images:
1.	Upload an image of a business card using the provided interface.
2.	Click on the "Extract" button to process the image and extract text.
3.	View the extracted information on the screen.
4.	Optionally, interact with the database to view, update, or delete the extracted data.

