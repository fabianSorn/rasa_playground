# Rasa Playground

## Goal of this project

Goal of this project is an implementation of a simple chatbot based on the 
chatbot-framework [rasa](https://rasa.com). This chatbot can then be used as a 
method of invoking custom action implementations which are accessible as 
webservices.

## Dependencies on external custom actions

The project depends on a already running rasa action server, which provides an
implementation for the action  `actions_sts`. An implementation can be found in
my [STS project](https://github.com/fabianSorn/semantic_text_similarity)

The endpoint, where this service is running can be configured in the 
[endepoint file](./endpoints.yml).

## Installation

To install the dependencies of this project, run:
```shell script
pip install -r requirements.txt
```
To run the chatbot

