# AlphabetSoup

## Analysis

#### Looking at the outcomes of the model's performances, the risk of overfit is high with this dataset and advance model's as we used for this challenge. When a more extreme model rendered it was much worse loss and the accuracy was reduced nearly 20%. I believe my second model (extreme) was overfit and no longer a useful model.
### Extreme evaluation/overfit model - Loss: 8926.684716670534, Accuracy: 0.5331778526306152


#### When a more balanced approach was used for the third model loss was more inline with the first conservative trial but the accuracy again was as low as the extreme model, to me this looks like we overfit this model to the data. 
### Balanced evaluation/still overfit - Loss: 0.6913789567516427, Accuracy: 0.5331778526306152

#### Lastly, if we look at the first attempt, and most successful, that gives a conservative approach with just 2 hidden layers and 8 neurons for the first layer and 4 for the second, we get the best outcome. While we didn't hit the 75% mark we were looking for, what was accomplished is a better understanding of the dataset's match with deep neural net model. I believe we could find a simpler approach more fit to the data. If the deep neural net model is preferred smaller changes to the dataframe or to the model's parameters might get us to the 75% but not with out considerably more time doing trial and error than possibly desired. 
### Conservative evaluation - Loss: 0.5582751734263696, Accuracy: 0.7248979806900024
