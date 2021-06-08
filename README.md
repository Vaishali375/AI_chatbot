# AI_chatbot

a retrieval based chatbot using NLTK, Keras, Python.

## About the Project
In this Python project  we have  built a chatbot using deep learning techniques. 
The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. 
We use a ANN to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

## Prerequisites
The project requires knowledge of Python, Keras, and Natural language processing (NLTK). 
Along with them, we will use some helping modules which you can download using the python-pip command.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install tensorflow, keras, pickle, nltk
```
## Run the chatbot

To run the chatbot, we have two main files; train_chatbot.py and chatapp.py.

First, we train the model using the command in the terminal:

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
python train_chatbot.py
```
If we don’t see any error during training, we have successfully created the model. Then to run the app, we run the second file.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
python chatgui.py
```
The program will open up a GUI window within a few seconds. With the GUI you can easily chat with the bot.
