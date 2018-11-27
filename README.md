# Parsing-Data-and-Text-Preprocessing
Parsing raw unstructured textual data to structured JSON and XML files and performing text pre-processing on the given data

# Tasks to perform:
# Task 1. Parsing Raw Text Files
Our job is to extract the data and transform the data to the XML and JSON format. We will use an efficient regular expression to extract.

Dataset: The data contains several job postings including information such as job title, , job description, start date, required qualifications. 

# Task 2. Text Pre-Processing
We are to write python code to preprocess a set of resumes and convert them to numerical representations

Dataset: The data set we are given contains around 250 distinct CVs distinguished by their Ids

The task2 contains the following subtasks:
● The word tokenization must use the following regular expression, "\w+(?:[-']\w+)?"
● The context-independent and context-dependent (with the threshold set to %98) stop words must be removed from the vocab. The stop words list (i.e, stopwords_en.txt)
provided in the zip file must be used.
● Tokens should be stemmed using the Porter stemmer.
● Rare tokens (with the threshold set to %2) must be removed from the vocab.
● Tokens must be normalized to lowercase except the capital tokens appeared in the
middle of a sentence/line.
● Tokens with the length less than 3 should be removed from the vocab.
● First 200 meaningful bigrams (i.e., collocations) must be included in the vocab.


