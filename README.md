# Sentiment-Analysis-with-Python
This project follows my work learning sentiment analysis coding on python. The first project starts with a tutorial by Shaumik Daityari where I learned how to train Python to register Positive and Negative connotations in Tweets. It went well but the rudimentary code did not seem to assess specific custom tweets like the one below 

**custom_tweet5 = "I didn't like this product"**

**custom_tokens5 = remove_noise(word_tokenize(custom_tweet5))**

**print(classifier.classify(dict([token, True] for token in custom_tokens5)))**

**Positive**

It seems tha the output of the algorithm does not register conjunctions as negative or positive and instead assessed "like" as a positive term. This means that further coding will have to be performed for the language software to learn the negative connotaions of "didn't like". 
