# AdWise-Sparky
ASU IFT 598 - Natural Language Processing Final Project
This Project is for our "IFT 598 - Natural Language Processing" course.

## Description
This is a Chatbot which will help international students with admission relation questions.

It has been implemented with Python3.6, NLTK, TensorFLow and Flask and has been trained on Dynamic Neural Network.
This Chatbot uses a JSON dataset, having intent based training questions and random answers for each intent.

## Installation
Install Python 3.6.8
```
pip install virtualenv
```
Go to repository folder.
```
virtualenv -p python .
```
**Activating virtualenv**

For Windows:
```
.\Scripts\activate
```
For Bash:
```
.\Scripts\activate
```
Install requirements.txt
```
pip install -r requirements.txt
```
Download nltk collections:
```
python -m nltk.downloader all
```

## Run the application
```
python main.py
```
