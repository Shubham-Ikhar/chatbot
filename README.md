# Building a Simple Chatbot from Scratch in Python (using NLTK)


# Outline
* [Training File](#training)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Training File
The idea of this project to create chatbot of responding to a few instructions and questions asked by user.



## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
nltk.download('omw-1.4')
```

### Installation of Tensorflow
```
pip install tensorflow
```

### Installing required packages
```
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense, Activation, Dropout
from tensorflow.keras.optimizers import SGD
from tensorflow.keras.models import load_model
```

## How to run
* You can run the chatbot application using commands which also includes step by step instructions.
* Through Terminal
* First run the training file to creating the training data which is present in `intents.json`.
```
python training.py
```
* Then run the chatbot python file to start the bot.
```
python chatbot.py
```
You are reday to go once you get the `GO! Bot is running...` in the console.
