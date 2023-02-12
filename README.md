# Introduction
This code provides a method to compare keywords between a job description and a resume. It returns a dataframe with the top n most common words in the job description and their corresponding counts in the resume. It also creates a barplot to visualize the comparison between the job description and the resume.

# Installation
The code requires the following libraries:

- nltk
- docx2txt
- pandas
- numpy
- matplotlib
- seaborn


# Usage
The code is implemented in the KeywordMatch class. You can initialize the class by providing the path to the job description file and the resume file, and the number of keywords to compare (optional, default is 10). The class provides the following methods:

- process_text: takes a file path as input and returns a Counter object with the word counts in the file.
- compare_keywords: compares the top n most common words in the job description and their corresponding counts in the resume.
- create_dataframe: creates a dataframe with the results of the keyword comparison.
The code also creates a barplot to visualize the comparison between the job description and the resume. The barplot can be customized by changing the seaborn plotting parameters.
