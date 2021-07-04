# QuoteSearch
This module is created to find the author of a given quote.

The dataset used for this module is Quotes-500k (https://github.com/ShivaliGoel/Quotes-500K).

The current program does a simple check from the dataset to check if a user input quote is present in the dataset.
If present, it returns the author of the quote, with the source ( if available ). 

## TODO : Future works
### 1. Use word embeddings
To make the model more intelligent, the next step is to create embedding based search. 
In natural language processing, word embedding is a term used for the representation of words for text analysis, typically in the form of a real-valued vector that encodes the meaning of the word such that the words that are closer in the vector space are expected to be similar in meaning. 

By using embeddings in our search, we can find quotes which are similar in meaning to the ones the user inputs, even though it is not an exact match. 

### 2. Better data structure to store the quotes
To search the large dataset, a better data structure to access the quotes would be helpful to make the program more efficient.
Currently, it is using a dictionary to store the quotes as keys and values as authors. While the efficiency is O(1), there could be a better intuitive method to it.




