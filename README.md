# PII_Detection

The approach of detecting a certain thing in text needs the approach of NLP with NER ( Named Entity Recognition ).
As this was new to me I spend sometime over the weekend to understand on this. I also read on BERT and few thesis papers on PII detection.

I have tried PII detection using many established libraries with various model combinations and finally committed the three best working one.
I also wanted to try Amazon Comprehend but it needs AWS account which needs credit card which I was not comfortable to provide.

Dataset consists of 200 comma separated rows of first name, last name, country and phone number. It was generated using random name, country and phone numbers generators online but in realtime project we can use Faker package in python to do this. 

I am also in the process on figuring out my own PII detection algorithm. I am on it with my full heart and will try to complete and present ASAP
