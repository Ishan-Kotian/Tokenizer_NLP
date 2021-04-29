# Tokenizer_NLP
#What is Tokenization in NLP?
Tokenization is one of the most common tasks when it comes to working with text data. But what does the term ‘tokenization’ actually mean?
Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text document into smaller units, such as individual words or terms. Each of these smaller units are called tokens.
![image](https://user-images.githubusercontent.com/55652596/116508096-3d532f80-a8de-11eb-804f-10119053a3c4.png)

# Why is Tokenization required in NLP?
I want you to think about the English language here. Pick up any sentence you can think of and hold that in your mind as you read this section. This will help you understand the importance of tokenization in a much easier manner.
Before processing a natural language, we need to identify the words that constitute a string of characters. That’s why tokenization is the most basic step to proceed with NLP (text data). This is important because the meaning of the text could easily be interpreted by analyzing the words present in the text.
Let’s take an example. Consider the below string:
“This is a cat.”
What do you think will happen after we perform tokenization on this string? We get [‘This’, ‘is’, ‘a’, cat’].
There are numerous uses of doing this. We can use this tokenized form to:
1.Count the number of words in the text
2.Count the frequency of the word, that is, the number of times a particular word is present

# The True Reasons behind Tokenization
As tokens are the building blocks of Natural Language, the most common way of processing the raw text happens at the token level.

For example, Transformer based models – the State of The Art (SOTA) Deep Learning architectures in NLP – process the raw text at the token level. Similarly, the most popular deep learning architectures for NLP like RNN, GRU, and LSTM also process the raw text at the token level.
![image](https://user-images.githubusercontent.com/55652596/116508306-ad61b580-a8de-11eb-81ea-a42f70868fda.png)

As shown here, RNN receives and processes each token at a particular timestep.
