# PII_Detection

The approach of detecting a certain thing in text needs the approach of NLP with NER ( Named Entity Recognition ).
As this was new to me I spend sometime over the weekend to understand on this. I also read on BERT and few thesis papers on PII detection.

I have tried PII detection using many established libraries with various model combinations and finally committed the three best working one.
I also ried Amazon Comprehend but it needs AWS account (for creating authentication credentials) which needs credit card which I was not comfortable to provide. Even if I give my credit card info, they say on their website that it can take 3-5 days to validate my account.

I tried IBM Watson as well for this purpose but it had few error ( version related ). I dropped the plan to use it anyways due the fact that after my online research I found that is is not superior to Amazon Comprehend. 

Dataset consists of 200 comma separated rows of first name, last name, country and phone number. It was generated using random name, country and phone numbers generators online but in realtime project we can use Faker package in python to do this. 

I am also in the process on figuring out my own PII detection algorithm. I am on it with my full motivation will try to complete and present ASAP ( within 1-2 days )
I am exploring Gensim for the same : https://pypi.org/project/gensim/
