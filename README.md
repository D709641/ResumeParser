# ResumeParser

ResumeParser works on python3. It use the different library of python like spaCy, OCR, PDFminer, Streamlit, pyngrok etc.

spaCy is a free, open-source library for NLP in Python. It's written in Cython and is designed to build information extraction or natural language understanding systems. It's built for production use and provides a concise and user-friendly API.https://spacy.io/

## Requirement 
* python3
* Library of python: spaCy, OCR, PDFminer, Streamlit, pyngrok, PyPDF2, pdf2image, spacy(en_core_web_trf,en_core_web_sm, en_core_web_lg)


## Aim!!
Objective is to build a resume parser in Python, this project leverages the SpaCy Python library to implement several NLP (natural language processing) techniques such as tokenization, lemmatization, parts of speech tagging. Because all of the resumes are supplied in PDF format , you'll also learn how to use optical character recognition (OCR) to extract text from the documents. The resumes can also be in Word doc format. To extract critical information from a CV, such as an applicant's job history, name, geographic area, and so on, the final application will require little human participation. The list of fields which you will need to extract is in this Google Sheet. The resume parser end point can take in millions of resumes, parse the needed fields and categorise them. This resume parser should use the popular python library - SpaCy for OCR and text classifications. First, we train our model with required fields and then deploy the end point.
