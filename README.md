# english_text_analysis
This project demonstrates text analysis and visualization using Python. It involves reading a text file, preprocessing the content, and visualizing the results through a bar chart and a word cloud.
Features
Text Preprocessing:

Encoding Detection: Automatically detects the file encoding using chardet to handle various text encodings.
Tokenization: Uses WordPunctTokenizer from NLTK to tokenize the text, splitting it into words and punctuation.
Stopwords Removal: Removes common stopwords using both NLTK's predefined list and a custom list of stopwords.
Word Filtering: Filters out short and overly long words to focus on meaningful terms.
Frequency Analysis:

Word Frequency Distribution: Calculates the frequency of each word in the text using NLTK's FreqDist.
Visualization:

Bar Chart: Displays the top 30 most common words using a bar chart.
Word Cloud: Generates a word cloud to visually represent the frequency of words in the text.
Requirements
Python 3.x
Libraries: nltk, wordcloud, matplotlib, chardet
You can install the required libraries using pip:

bash
Copy code
pip install nltk wordcloud matplotlib chardet
Usage
Download NLTK Data:
Run the script once to download necessary NLTK data (e.g., stopwords):

python
Copy code
nltk.download('stopwords')
Prepare Your Files:

Place your text file (e.g., Brian-Tracy-Goals.txt) in the specified directory.
Ensure you have a custom stopwords file if applicable (e.g., steve_stopword_list.txt).
Run the Script:
Execute the script to perform text analysis and generate visualizations:

bash
Copy code
python your_script_name.py
Make sure to update the file paths in the script to match your setup.

Example Output
Top 10 Most Common Words:
Displays the most frequent words in the text.

Bar Chart:
A bar chart of the top 30 most common words.

Word Cloud:
A word cloud visualization highlighting the most frequent words in a visually appealing format.
