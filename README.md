# SuperTwitterBot
SuperTwitterBot will  post random images and text generated by Markovify

There is also a twitterpost script. This will automatically send a [ python twitterpost.py ]
command every 15 minutes. twitterpost.py has a random timer 40seconds to 200seconds inside to prevent a post from occuring 
EXACTLY every 15 minutes. Text is generated using Markovify

I used Jupyter notebook as an editor also.




Examples Using Twython alone:
import twython
twitter.get_home_timeline()

import twython
twitter.update_status(status='Twython Makes it so easy !')

import twython
twitter.search(q='python', result_type='popular')


import twython
twitter.search(q='trump')