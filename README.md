# Tag-Extraction-project
Extracting tags simplifies the process of identifying inside unstructured text relevant terms and phrases. This involves emails, updates on social media, chat conversations, and all other data forms that are not structured in any predefined manner. The technique used for automated tag extraction is a statistical approach Simple Statistical Approaches with machine learning.
Using statistics is one of the simplest methods for identifying the main keywords and key phrases within a text.

Packages used are:
Pandas
OS
Nltk
Re
Sklearn
Glob

The statical approach used for the machine learning model is explain below;
There are different types of statistical approaches, including word frequency, word collocations and co-occurrences, TF-IDF (short for term frequency–inverse document frequency).

Word Frequency
Word frequency consists of listing the words and phrases that repeat the most within a text. This can be useful for a myriad of purposes, from identifying recurrent terms in a set of product reviews, to finding out what are the most common issues in customer support interactions.
However, word frequency approaches consider documents as a mere ‘bag of words’, leaving aside crucial aspects related to the meaning, structure, grammar, and sequence of words. Synonyms, for example, can’t be detected by this keyword extraction method, dismissing very valuable information.

Word Collocations and Co-occurrences
Also known as N-gram statistics, word collocations and co-occurrences help understand the semantic structure of a text and count separate words as one.
Collocations are words that frequently go together. The most common types of collocations are bi-grams (two terms that appear adjacently, like ‘customer service’, ‘video calls’ or ‘email notification’) and tri-grams (a group of three words, like ‘easy to use’ or ‘social media channels’).
Co-occurrences, on the other hand, refer to words that tend to co-occur in the same corpus. They don’t necessarily have to be adjacent, but they do have a semantic proximity.

TF-IDF
TF-IDF stands for term frequency–inverse document frequency, a formula that measures how important a word is to a document in a collection of documents.
This metric calculates the number of times a word appears in a text (term frequency) and compares it with the inverse document frequency (how rare or common that word is in the entire data set).
Multiplying these two quantities provides the TF-IDF score of a word in a document. The higher the score is, the more relevant the word is to the document.
TD-IDF algorithms have several applications in machine learning. In fact, search engines use variations of TF-IDF algorithms to rank articles based on their relevance to a certain search query.
When it comes to tag extraction, this metric can help you identify the most relevant words in a document (the ones with the higher scores) and consider them as keywords. This can be particularly useful for tasks like tagging customer support tickets or analyzing customer feedback.
In many of these cases, the words that appear more frequently in a group of documents are not necessarily the most relevant. Likewise, a word that appears in a single text but doesn’t appear in the remaining documents may be very important to understand the content of that text.
