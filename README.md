# Chatbot
Chatbot implementation using Cornell Movie Dialogs Dataset in PyTorch.The bot can converse with the user and can answer the questions asked though it doesn't pass the [Turing Test](https://en.wikipedia.org/wiki/Turing_test).

It is bulit using Sequence to Sequence architecture with Attention Mechanism.

Sequence To Sequence model introduced in Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation has since then, become the Go-To model for Dialogue Systems and Machine Translation. It consists of two RNNs (Recurrent Neural Network) : An Encoder and a Decoder. The encoder takes a sequence(sentence) as input and processes one symbol(word) at each timestep. Its objective is to convert a sequence of symbols into a fixed size feature vector that encodes only the important information in the sequence while losing the unnecessary information.Each hidden state influences the next hidden state and the final hidden state can be seen as the summary of the sequence. This state is called the context or thought vector, as it represents the intention of the sequence. From the context, the decoder generates another sequence, one symbol(word) at a time.

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

The dataset can be downloaded here : [Cornell Movie Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
# Requirements

1. PyTorch
2. Python
3. CUDA (if you want to train on a GPU)

*The overall implementation is inspired by [this](https://pytorch.org/tutorials/beginner/chatbot_tutorial.html) post on [pytorch.org](https://pytorch.org/)*
