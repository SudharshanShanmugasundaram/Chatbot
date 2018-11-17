# Chatbot
Chatbot implementation using Cornell Movie Dialog Dataset in PyTorch.The bot can converse with the user and can answer the questions asked 
though it doesn't pass the [Turing Test](https://en.wikipedia.org/wiki/Turing_test).

# What is a chatbot ???

A [chatbot](https://en.wikipedia.org/wiki/Chatbot) (also known as a smartbots, talkbot, chatterbot, Bot, IM bot, interactive agent, Conversational interface or Artificial Conversational Entity) 
is a computer program or an artificial intelligence which conducts a conversation via auditory or textual methods.Such programs are often 
designed to convincingly simulate how a human would behave as a conversational partner, thereby passing the Turing test. Chatbots are 
typically used in dialog systems for various practical purposes including customer service or information acquisition. Some chatterbots 
use sophisticated natural language processing systems, but many simpler systems scan for keywords within the input, then pull a reply 
with the most matching keywords, or the most similar wording pattern, from a database.

The term "ChatterBot" was originally coined by Michael Mauldin (creator of the first Verbot, Julia) in 1994 to describe these 
conversational programs.Today, most chatbots are either accessed via virtual assistants such as Google Assistant and Amazon Alexa, via 
messaging apps such as Facebook Messenger or WeChat, or via individual organizations' apps and websites.Chatbots can be classified into 
usage categories such as conversational commerce (e-commerce via chat), analytics, communication, customer support, design, 
developer tools, education, entertainment, finance, food, games, health, HR, marketing, news, personal, productivity, shopping, social, 
sports, travel and utilities.

# Dataset

This corpus contains a large metadata-rich collection of fictional conversations extracted from raw movie scripts:

* 220,579 conversational exchanges between 10,292 pairs of movie characters

* involves 9,035 characters from 617 movies

* in total 304,713 utterances

* movie metadata included:

    * genres

    * release year

    * IMDB rating

    * number of IMDB votes

    * IMDB rating

* character metadata included:

    * gender (for 3,774 characters)

    * position on movie credits (3,321 characters)

* see README.txt (included) for details

# Requirements

1. PyTorch
2. Python
3. CUDA (if you want to train on a GPU)
