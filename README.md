# TextSummarizer
WHAT IS SUMMARY:

Text summarization is the process of condensing a block of text, hence reducing its sizewhile preserving the key points and context of the original text. Since manual textsummarization is a time expensive and laborious task, the objective is to automate thisprocess.

MOTIVATION:
• Reducing reading time

• Significant amount of information

• Improving the effectiveness of indexing

• Automatic summarization algorithms are less biased than human summarizers.

WHY TEXT SUMMARIZATION:
• Can get maximum information by spending minimum time from unstructured textual data.

• To enhance the readability of the documents.

• Can eliminate redundant, insignificant text and provide required information

• Accelerates the process of researching for information

There are two types of summazrization method, one is Extractive Summarization and another is Abstractive Summarization.

Extractive Summarization:
These methods rely on extracting several parts, such as phrases and sentences, from a piece of text and stack them together to create a summary. Therefore, 
identifying the right sentences for summarization is of utmost importance in an extractive method.

Abstractive Summarization:
These methods use advanced NLP techniques to generate an entirely new summary. Some parts of this summary may not even appear in the original text.

We have followed extractive summarization technique here.

FEATURES:
• Paste the text in the text editor and generate summary

• Upload text file from the device and generate summary

• Generate summary from a given url.

• Save the summary Reset to clean the text field and start a new

Library in Use:
• spaCy Summarizer
• beautiful soup for web scrapping

WHY SPACY:
• object oriented approach

• provides the fastest and most accurate syntactic analysis of any NLP library released to date

• offers access to larger word vectors that are easier to customize

• each function returns objects instead of strings or arrays. This allows for easy exploration of the tool

• returns result faster than any other libraries

METHOD:
• Text Preprocessing and Cleaning
  Removing stop words, Removing punctuations, Tokenization, Lowering case

• Counting word frequency

• Normalizing frequency count

• Finding Sentence score

• Return top 6 sentence as summary

FUTURE WORK:
• Implement advanced Deep Learning method

• Work with Bangla text

CONCLUSION:
Our goal is to build a system which can be very handy to give us an abstract and concise representation of a given article (e.g. news, research articles).
