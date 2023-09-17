# COVID-19 Tweets Country of Origin Classification Kaggle Competition

## Dataset
This dataset consists of Covid-19 related tweets posted  by users coming  from six  English-speaking  countries:  Australia,  Canada,  Ireland,  New  Zealand,  the  United  Kingdom, and the United States.  A total of 6 columns were provided, but only the tweet text and country were used to train the models. </br>

Dataset was extend to provide better results by replacing emojis with their respective word and expanding the shortened urls to the original link in order to extract relevant words.


| text                                              | country     |
| ------------------------------------------------- | ----------- |
| Remember the #WuhanCoronaVirus? The pandemic w... | us          |
| While we hit 150,000 in #COVID19 deaths, the P... | new_zealand |
| 🇺🇸 Pandémie de #coronavirus: 30 pasteurs améri...	| us          |


## Modeling
| model                    | accuracy |
| ------------------------ | -------- |
| Ensemble Model           | 51.3%    |     
| Logistic Regression      | 45.2%    |
| Linear SVC               | 48.7%    |
| Multinomial Naive Bayes  | 49.4%    |

Ensemble model combined results from a CNN built using keras and a Multinomial Naive Bayes model built using Scikit-learn.

![](https://github.com/thomasdurkin/Capstone-Kaggle-Competition/blob/master/Confusion%20Matrix.PNG)






