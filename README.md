# BizCardX
Extracting Business Card Data with OCR
Extracting Business Card Data with OCR
BizCardX is a Python application designed to extract information from business cards using Optical Character Recognition (OCR) technology. It utilizes various technologies such as Streamlit, EasyOCR, OpenCV, and MySQL to achieve this functionality



## Project Objective and Scope:

Clearly defined the project objective, which is to develop a Streamlit application for extracting information from business cards using OCR technology.
Scope of the project includes designing a user-friendly GUI, implementing OCR functionality, integrating with a database system for data storage, and providing functionalities for data manipulation (read, update, delete).

## Approach and Methodology:

Demonstrated a systematic approach to project development by outlining steps from installation of necessary packages to testing and improvement.
Methodology includes designing the user interface, implementing OCR using easyOCR, integrating with a database management system, and continuous improvement through testing and enhancement.

## Technical Implementation:

Successfully implemented OCR functionality using easyOCR library, enabling extraction of relevant information from uploaded business card images.
Designed an intuitive user interface using Streamlit, allowing seamless interaction for uploading images and displaying extracted data.
Integrated SQLite or MySQL database for efficient storage and retrieval of extracted information, enabling functionalities for data management.

## Quality Assurance and Testing:

Ensured the application functions as expected through thorough testing, validating functionalities such as image upload, OCR extraction, data display, and database interaction.
Conducted extensive testing to identify and resolve bugs, ensuring a smooth user experience.

## Documentation and Code Organization:

Provided comprehensive documentation including project requirements, installation instructions, and usage guidelines for stakeholders.
Maintained clean and organized code structure, facilitating readability, maintenance, and future enhancements.
Included comments within the codebase to enhance understanding and promote collaboration among developers.

## Conclusion and Future Recommendations:

Concluded the project by summarizing the achieved results, including the successful development of a functional Streamlit application for business card data extraction.
Recommended future enhancements such as adding user authentication, optimizing performance, and incorporating additional features based on user feedback.

## Overall Assessment:

Evaluated the project's success in meeting the stated objectives and delivering a valuable solution for digitizing business card information.
Highlighted strengths such as effective utilization of OCR technology, user-friendly interface design, and robust database integration.
Identified areas for improvement and outlined strategies for addressing them in future iterations.


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

