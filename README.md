# ResumeScreening - a Guide to create your own Keyword matching model

##### Overview
This project provides a simple tool to screen multiple resumes and determine how closely they match a given job description. By extracting text from PDF and DOCX files, the script tokenizes and cleans the text, then calculates a match score based on the overlap of keywords between the resume and the job description.

##### Features
1. File Support: Works with PDF and DOCX resume files.
2. Text Preprocessing: Converts text to lowercase, removes punctuation, and filters out stop words.
3. Keyword Matching: Finds common words between the job description and resume.
4. Match Score Calculation: Computes a percentage score representing resume-to-job fit.

 ##### Requirements
 - Python 3.7+
 - Libraries: PyPDF2, python-docx, nltk
 - Install the required packages with:
   * pip install PyPDF2 python-docx nltk
 - Ensure necessary NLTK resources are downloaded:
   * import nltk
   * nltk.download('punkt')
   * nltk.download('stopwords')  
  ##### Usage
  - Run the script in your choice of editor
  - I used Google collab notebook
  - Example Output should look something like this
    - Matched Keywords:
    - data
    - analysis
    - python
      - Resume Matching Score with JD : 65 %
  - Future Enhancements
    - Weighted scoring for matching words with high importance
    - Phrase matching for coupling up the words that belong together for best matching
  - License
    - this project is licensed under the MIT License. 
 

 
