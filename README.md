# Flight-Price-Predictor
- Used pandas and sklearn.RandomizedSearchCV to clean and train a RandomForestRegressor model of flight fares between 5 major cities in India for 11 major airlines.
- Model accurately predicts flight fares with an r2 score of  0.801. 
- Built accompany GUI using Flask which fully works.
- I've also built the same GUI in React.
### Next Steps: integrating the React frontend with backend in Flask and training another model of US domestic flights

## To run the program: 
```
conda create -n fpp python=3.9
conda activate fpp
pip install flask flask_cors pandas seaborn sklearn openpyxl
flask run
```
## Screenshot of the program:
<img width="1468" alt="SS" src="https://github.com/xuelikesnow/Flight-Price-Predictor/assets/77033634/d092fb2b-e216-41e1-a904-fbc0b60fcd0f">
