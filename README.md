                                                     PDF_ANSWERING
Project Overview
Description: The project aims to create a user-friendly interface allowing users
to upload a PDF document and ask questions related to its content. The
application utilizes Natural Language Processing (NLP) techniques and Global
Vectors for Word Representation (GloVe) to determine the relevance of
questions to the PDF content. The answer provided is based on the question
with the highest relevance score.
Installation Instructions
1. File Setup:
o Save all project files in a directory.
2. Dependencies:
o Ensure the following Python libraries are installed:
▪ numpy
▪ pandas
▪ flask
▪ nltk
▪ re
▪ gensim
▪ PyPDF2
▪ sklearn
3. GloVe Model:
o Place the glovemodel.mod file in the appropriate directory.
Adjust the path in your Python code accordingly.
4. Running the Application:
o Execute interface.py, which is your Flask application, on a
local host server.
o Access the application via a web browser to upload a PDF and ask
questions.
Usage
1. Upload PDF:
o Choose a PDF file from your local system.
o Upload it using the interface.
2. Ask Questions:
   Enter questions relevant to the content of the uploaded PDF.
o Submit the question to receive an answer based on the content
relevance.
Ensure that all these dependencies are installed in your Python environment
using pip install <package-name> if they are not already installed.
Summary
By following these instructions, users can effectively deploy and utilize the PDF
Answering AI application. It integrates advanced NLP and GloVe techniques to
provide accurate responses to user questions based on uploaded PDF content.
