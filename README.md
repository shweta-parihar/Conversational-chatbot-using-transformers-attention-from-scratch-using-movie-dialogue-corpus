# Conversational-chatbot-using-transformers-attention-from-scratch-using-movie-dialogue-corpus

## Introduction
The use of artificial neural networks to create chatbots is increasingly popular nowadays, however, teaching a computer to have natural conversations is very difficult and often requires large and complicated language models.Traditionally, chatbots have been solved in a recurrent way – with models like Long Short-Term Memory networks or LSTMs. With the  introduction of Transformers, these model approaches have really taken over from LSTMs thanks to the self-attention mechanism. 

## About the problem and methodology

Here, I attempt to build a chatbot which is trained on transformers using multi-headed attention mechanism from scratch. The data used is Cornell's movie dialogue corpus. This corpus contains a large metadata-rich collection of fictional conversations extracted from raw movie scripts - 220,579 conversational exchanges between 10,292 pairs of movie characters.

#
The input is divided into question and answer pairs converted into tokens and fed into the model so that the model can to learn to interact. Note that the conversations are dependent on the context of the movies, so during evaluation, the model will respond based on those conversations that it has learned. If we wish to develop a domain specific chatbot, we will pass domain specific conversations to the chatbot.
