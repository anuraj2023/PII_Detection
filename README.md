# PII_Detection

The approach of detecting a certain thing in text needs the approach of NLP with NER ( Named Entity Recognition ).
As this was new to me I spend sometime over the weekend to understand on this. I also read on BERT and few thesis papers on PII detection.

I have tried PII detection using many established libraries with various model combinations and finally committed the three best working one.
I also ried Amazon Comprehend but it needs AWS account (for creating authentication credentials) which needs credit card which I was not comfortable to provide. Even if I give my credit card info, they say on their website that it can take 3-5 days to validate my account.

I tried IBM Watson as well for this purpose but it had few error ( version related ). I dropped the plan to use it anyways due the fact that after my online research I found that is is not superior to Amazon Comprehend. 

Dataset consists of 200 comma separated rows of first name, last name, country and phone number. It was generated using random name, country and phone numbers generators online but in realtime project we can use Faker package in python to do this. 

Edit : 24.05.2023

I tried PII detection with Binary Classification approach wherein I trained a new dataset (PII_Detection_With_Classifier.csv) with PII rows marked as 1 and 0 otherwise and tested against the test set to check for the accuracy of the model.

