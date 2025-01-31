Word Frequency Counter

This Python script counts the frequency of words in a given text input. It uses the Natural Language Toolkit (NLTK) for tokenization and processes the text by removing punctuation and converting words to lowercase to ensure accurate counting.

Features
Accepts user input for a block of text.
Tokenizes the text into individual words.
Filters out punctuation and converts words to lowercase.
Counts the frequency of each word.
Displays the word frequencies in a readable format.

Requirements
To run this script, you need to have the following Python packages installed:

nltk: For natural language processing tasks, such as tokenization.

You can install the required package by running:

pip install nltk

Additionally, the script uses the nltk.download('punkt') to download the necessary resources for tokenization.

Usage
Run the script:

python word_frequency_counter.py

The script will prompt you to enter your text:

Enter your text:
After entering the text, the script will output the frequency of each word in the input text, excluding punctuation.

Example Output:
Enter your text: Hello world! Hello everyone, welcome to the world of Python.

Word Frequency:
'hello': 2
'world': 2
'everyone': 1
'welcome': 1
'to': 1
'the': 1
'of': 1
'python': 1


Code Breakdown

Tokenization: The script uses nltk.word_tokenize() to split the input text into a list of words.

Preprocessing: The words are converted to lowercase and non-alphabetical characters (such as punctuation) are removed.

Counting Frequencies: The script uses Counter from the collections module to count the frequency of each word.

Output: The word frequencies are printed in a readable format.

License

This project is open source and available under the MIT License.
