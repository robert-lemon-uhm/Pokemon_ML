# Pokemon_ML
A demonstration of different machine learning techniques via a classification of Pokemon types based on their stats


The purpose of this project is to see if, through simple machine learning techniques, we are able to predict the typing of a pokemon based on its stats. 
If we are able to confidently predict a pokemon’s type, then the models have discovered a learnable pattern between types and stats. If not, then the game 
of Pokemon is fairly well-balanced, avoiding certain typings to have either dominating or underpowered stats.

The dataset for this project was acquired via [PokeAPI](https://pokeapi.co/), a free API whose documentation can be found [here](https://pokeapi.co/docs/v2#stats).

### Models Used
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- K-Means (Unsupervised Learning)
- Neural Network Sequential Model

### Results
Each model was evaluated based on its accuracy and AUROC score. While the best models were able to achieve a higher accuracy and AUROC than random guessing
(~5.5% accuracy and 0.5 AUROC is equivalent to random guessing), none of them seemed to be able to find a distinct, learnable pattern between a pokemon's 
stats and their typing. 

| Model         | Accuracy | AUROC   |
| ------------- | :--------: | :--------: |
| Decision Tree | 0.1200   | 0.5533  |
| Random Forest | 0.1955   | 0.6561  |
| KNN           | 0.2133   | 0.6741  |
| K Means       | 0.0622   | N/A     |
| Neural Net    | 0.1600   | 0.7051  |
