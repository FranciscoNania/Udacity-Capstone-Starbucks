# Udacity-Capstone-Starbucks


## Installation
All the libraries should be part of the Anaconda package.

## Files Description
portfolio.json
id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - time for offer to be open, in days
channels (list of strings)

profile.json
age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income

transcript.json
event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours since start of test. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record
		
Project1.ipynb - Jupyter notebook file containing analysis on dataset listed above

## Project Motivation
The main purpose of this project was developing my skills as a Data Scientist, this study completes the Udacity DataScience program partnered with Starbucks to provide this great dataset.


## Results
The main findings of the code can be found at the post below:

https://francisco-nania.medium.com/how-to-improve-efficiency-on-starbucks-offers-e963ca257162

## Acknowledments


I would like to thank Udacity for a great Data Science course with several tips and Starbucks for the data.

