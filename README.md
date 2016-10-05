# ufc-predictions
Statistical data analysis in the prediction of UFC fight outcomes

## Current Status of Project
- Planning: Research
- Feature Analysis Data Acquisition

## Blog
- Day 1 (10/5): Today has consisted of brainstorming and examining relevant features. After researching the past attempts of other I believe there is room for improvement. Vik Singh, a data model who posted the blog titled "Betting on UFC Fights – A Statistical Data Analysis," used the combination of physical features of the fighters, training background, and career history (aka KOs & TKOs). Vik scored an accuracy of 69%, using a random forest classier which is 19% better guessing. This is a great start, but nothing to write home about. I may start this as my initial proof of concept. 

https://partyondata.com/2011/09/21/betting-on-ufc-fights-a-statistical-data-analysis/

I believe that the key to more accurately predicting outcomes will require a model to understand how the unique fighting styles of each fighter will work against their specific opponent. This is something that is GOING TO BE HARD to do, but the data is available.

There is data available noting the type, number, and result of blows thrown among other features in each individual flight. This could have good signal in indicating the style and skill of a flight. eg. I could give a model information from the latest five fight for each opponent. My biggest worry is that in each flight a competitors style is influenced by their opponent and it may not apply when competing against someone else. 

Random thoughts: Neural Nets might be key, but I am going to start with a decision tree model for initial proof of concept. Would short-long term memory be useful at all? Stage one I'm going keep the model and the features simple! 

- Week one goals: 
Work with Sam to created a data set.
Create a feature engineering pipeline to populate features that relate fighters stats to each other
Train a random forest model that get 69%+ accuracy

- Stretch goals:
Train boosted Trees
Train a neural net

- Week 2:
Train a neural net
Add "Fight Style" features

Cheers!


