Introduction ¶
Tokenization is one of the first step in any NLP pipeline. Tokenization is nothing but splitting the raw text into small chunks of words or sentences, called tokens. If the text is split into words, then its called as 'Word Tokenization' and if it's split into sentences then its called as 'Sentence Tokenization'. Generally 'space' is used to perform the word tokenization and characters like 'periods, exclamation point and newline char are used for Sentence Tokenization. We have to choose the appropriate method as per the task in hand. While performing the tokenization few characters like spaces, punctuations are ignored and will not be the part of final list of tokens.

NLP_Tokenization

Why Tokenization is Required? 
Every sentence gets its meaning by the words present in it. So by analyzing the words present in the text we can easily interpret the meaning of the text. Once we have a list of words we can also use statistical tools and methods to get more insights into the text. For example, we can use word count and word frequency to find out important of word in that sentence or document.

Tokenization Techniques 
There are multiple ways we can perform tokenization on given text data. We can choose any method based on language, library and purpose of modeling.

Tokenization Using Python's Inbuilt Method 
NLP_Tokenization

We can use split() method to split a string into a list where each word is a list item.
By default split() use whitespace as separater, but we can change it to anything.
Word Tokenization
