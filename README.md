# CryptoSentimentAnalyzerUMBC
Our Tool Analyzes the public sentiment around a cryptocurrency or token of your choice using Textblob, a Python NLP framework, and Tweepy, a Python implementation of the Twitter API. Create a Twitter Developer Account and get more information from their developer portal.
*Note, The Crypto Sentiment Analyzer utilizes Twitter V1.1 API, so for this to function properly you must get keys for that version, if for whatever reason you cannot get working keys, use the version with keys CryptoConnotationAnalysisWithKeys.ipynb*
___________________________________________________________________________________
API Keys and Tokens:
create a .env file and enter values for the fields below in this format
*values inside {} will be your own information i.e. your api keys and token*
API_KEY={Api Key}
API_KEY_SECRET={Secret} 
BEARER_TOKEN={Bearer token}
ACCESS_TOKEN={Access token}
ACCESS_TOKEN_SECRET={Access Token Secret}
___________________________________________________________________________________
Dependencies:
- os (built into python)
- Textblob
- Tweepy
- Dotenv
pip install <package>
___________________________________________________________________________________
I recommend creating a virtual enviornment for this project so there are no conflicts between your globally installed packages. 
Virtual environment steps:
1. Assuming python is installed globally on your system, through your operating system's cli go to your project folder
2. Run this command: python -m venv ./venv 
or python3 -m venv ./venv
3. Now to activate your virtual environment, run in your cli: venv\Scripts\activate 
4. Install Dependencies with pip
___________________________________________________________________________________
Execution:
Once you run the program, user will be prompted with input: for the tool to function properly, enter the name of a cryptocurrency or token. Recent Tweets about the coin will be returned along with a generated public connotation/sentiment value surrounding said coin.
