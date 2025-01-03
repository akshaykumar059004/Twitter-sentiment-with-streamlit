# Twitter Sentment Analysis

![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![Framework](https://img.shields.io/badge/Framework-sreamlit-red)


#### **Twitter Sentment Analysis Web App**  using #tag, words and username to fetch data finds Insides of data and Tells Sentiment of the perticular #tag, words or username. 


## Features Of Data Analysis Web App
- Can Fetch upto **10000 Tweets**.
- Gives a **detailed Analysis** of the tweets.
- Gives the most **trending** **#tag**, **links** and **@mentions** of the fetched tweets.
- Gives the Overall **Sentiment Analysis** of the **Tweets** in form of **graph**.
- You can **download/export** the tweets in form of csv file.



Check out the live demo: https://twitter--sentiment--analysiss.herokuapp.com/

### Vedio demo:
<p><img  alt="GIF" src="https://github.com/everydaycodings/Twitter-Sentimental-Analysis-WebApp/blob/master/presentation/demo.gif" width="800" height="450" /></p>

# Note

> #### Use this URL - [Click Me](https://github.com/everydaycodings/Twitter-Sentimental-Analysis-WebApp/issues/new) - in case if you are faccing any problem with th WebApp or source code.



Source Code: [github link](https://github.com/everydaycodings/Twitter-Sentimental-Analysis-WebApp)


## How to run the project?

1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the [requirements.txt](https://github.com/everydaycodings/Twitter-Sentimental-Analysis-WebApp/blob/master/requirements.txt) file with the command `pip3 install -r requirements.txt`
3. Create a file name `config.ini`
4. Paste the code in `config.ini` and insert key deatils which you will get keys here [developer.twitter.com](https://developer.twitter.com/en)
```
[twitter]

api_key = Your Keys
api_key_secret = Your Keys

access_token = Your Keys
access_token_secret = Your Keys
```
5. Open your terminal/command prompt from your project directory and run the file `app.py` by executing the command `streamlit run app.py`.
6. You will be automatically redirected the your localhost in brower where you can see you WebApp in live.

