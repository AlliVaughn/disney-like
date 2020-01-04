# Disney-Like
    I have decided that I'd like to know if an AI can write Disney songs which are indistinguishable to the average human from those written for Disney or Disney affiliates (ie Pixar) by employees (lyracists).  

## Description of data source
    Data scraped using a python 3 script from [All the  Lyrics](allthelyrics.com) and initially stored in a csv file. 

## Expected data cleaning steps to make the data useful for machine learning
   * Removal of duplicates and obviously non-Disney/affiliate songs. (ie. Barney's "I Love You")
   * Addition of song title and movie title, if needed. 
   * Removal of non-necessary punctuation, if it proves to be an issue
   * possible addition of a count column 
   * Save as a text file

## The machine learning models you plan on using
    GPT-2 stands for “Generative Pretrained Transformer 2”: “Generative” means the model was trained to predict (or “generate”) the next token in a sequence of tokens in an unsupervised way. To see a bit how GPT-2 works, visit:[Talk To Transformer](https://talktotransformer.com).  
   * I will be using [GP2-Simple](https://github.com/minimaxir/gpt-2-simple in [GP2 CoLab Research](https://colab.research.google.com/drive/1VLG8e7YSEwypxU-noRNhsv5dW4NfTGce?pli=1&authuser=1#scrollTo=H7LoMj4GA4n_)
   * GPT-2 is trained by OpenAI on 40GB of text from the internet. 
   * GPT-2 runs on the big processors on Google Cloud (through Max Woolf’s gpt-2-simple colab notebook)

## What metrics you plan on using to evaluate the ml model 
    Not Applicable for this Project.
    
## How you plan on demonstrating your model (web app, jupyter notebook)
    Most likely a web app that takes a song prompt from the user, runs that prompt through the model and returns the AI-inspired song's lyrics, the song's title and a movie title that the song could potentially come from. 
## How you plan on training the model 
    Colab, personal computer, other as necessary.

## Credits:  
