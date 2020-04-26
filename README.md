

### Introduction

This project is based on simulated data of customer behavior and offers reactions driven from Starbucks rewards mobile APP.
Starbucks periodically sends offers and advertisement information about the new products to the app users. These offers can be one of three types: Buy One Get One (BOGO), a special discount, or an informational message and some users may not receive any offers for certain period. Each of these offers has a validity period, even the informational ones. 
Completed offers don’t mean necessarily that they were actually completed, for example: a customers may receive an offer “Spend 10 dollars and receive free 10 dollars to spend”, but never really views this offer, then the customer spends 12 dollars so there will be an offer completion record, however the customer wasn’t influenced by that offer because he didn’t view the offer.

### Problem

The problem is to identify and target the customers with the best offer that they more likely to view and complete.
My approach for solving this issue, will be to decide which one of the three offers (BOGO, Discount or informational message) should be sent to a certain customer given some feature about his demographic group and his previous transactions. 

### Included in this repository

data.zip - Contains the three original files 
proposal.pdf - The Capstone Project proposal with the project details
README.md - this file

After downloading/cloning this repository, unzip the file data.zip and create a /data folder contains the three files:
1- portfolio.json
2- profile.json
3- transcript.json

### Libraries

This project is developed using Python 3.6:
jupyter
numpy 
pandas 
math 
matplotlib 
pytorch 
scikit-learn
