<h1 align = center>Natural Language Processing</h1>

Natural Language Processing (NLP) concerns with how we program the computer to process and analyse a large context of natural language data. As a result, computer is able to understand the context of the natural language data.

## Requirement
- nltk
- xlrd
- pandas
- re
- string

### Data Preperation
Since NLP is mostly applied on `.txt` files, we start by converting the `.xls` file into a `.txt` file. After converting the `.xls` file into a `.txt` file, We then save that `.txt` file and use that txt file further as an input of NLP program.

### Applying NLP
The Steps are as follows:
1. Convert list into strings
2. Split Strings into words
3. Split Words again to remove the punctuation
4. Compile the punctuations into a single variable
5. Remove punctuation from each word
6. Store the words into a variable after removing the punctuations from the words
7. Convert the text into lower case
8. Prepare regex for char filtering
9. Remove the character which are not alphabetic
10. Filter out the Stopwords
11. Remove the Stopwords

It can also be done using Tokenization as follows:
1. Convert list into strings
2. Tokenize the sentence
3. Tokenize the words
4. Remove all tokens that are not alphabetic
5. Split into words
6. Convert to lower case
7. Prepare regex for char filtering
8. Remove punctuation from each word
9. Remove remaining tokens that are not alphabetic
10. Filter out stopwords
11. Remove the stopwords

The output will be categories of subjects from the conversation.
