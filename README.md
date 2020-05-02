# chatbot
This is a robot for you to query the covid-19 information of each country.
![image](https://github.com/tax1997/chatbot/blob/master/vid.gif)

## Getting Started

Build a telegram bot by talking to [*BotFather*](https://telegram.me/BotFather) and input **/newbot** and then follow the steps it ask to create new bot.If you want to use this robot, first you need to apply for your own telegram bot and use your TOKEN instead of the TOKEN in the covid19-telegrambot.py file.

### Environments
Install Python 3.7 with Anaconda and then use conda to create a virtual environment clone from base as:
```
conda create --name covid --clone base
```
Then use conda to active the new environment and install packages under new environment:
```
conda activate covid
```

### Installation
Please install all of the additional packages under new environment.

[Install spacy](https://spacy.io/usage/)
```
pip install -U spacy
python -m spacy download en_core_web_md
python -m spacy link en_core_web_md en
```

[Install rasa_nlu](https://legacy-docs.rasa.com/docs/nlu/0.11.4/installation/)
```
pip install rasa_nlu
```

[Install tensorflow](https://www.tensorflow.org/install)
```
pip install --upgrade pip
pip install tensorflow
```
[Install sklearn](https://scikit-learn.org/stable/install.html)
```
conda install scikit-learn
pip install sklearn-crfsuite

```
## Running the tests
After create the new bot on telegram and replace the new token in the covid19-telegrambot.py, simply run the covid19-telegrambot.py and wait for a few minutes to let the program train the bot. Then you can chat with it.
