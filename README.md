# Project: Sport Bettor

## Description

I have always been interested in handling repetitive or tideous real-life tasks by web automation. Such cases include automatically reloading U-pass every month or searching for desired items on online - shopping websites.

In this project, I used `Selenium` package to automatically extract football match predictions from football statistic website, and then place bets on another sport betting website based on those prefictions.

## Video demo of placing bets:

()

## Usage

1. Go to https://www.partypoker.com/ and register for an account, fund your account with minimum $50 CAD. 


2. Open the `params.py` file and type in your `user_name`, `password` and `user_id`


3. Go to https://chromedriver.chromium.org/downloads to download the chromedriver according to your current Chrome version. Open the `get_predicted_scores.py`, and paste your path of downloaded chrome driver into line 8, where it says `your path to chrome driver`.


4. Run `get_predicted_score.py`, or in terminal, navigate to the root directory of this project and run the following:
 
```
Python3 get_predicted_score.py
```


5. Run `place_bets.py`, or in terminal, navigate to the root directory of this project and run the following:
 
```
Python3 place_bets.py
```


## Dependencies:


- Selenium (version 3.141.0)

- bs4 (version 4.7,1)
