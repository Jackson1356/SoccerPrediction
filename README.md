## Visualization and Prediction of Soccer Games in Europe and Japan

# Introduction
Welcome to the Predicting Soccer Game Results repository! This project aims to leverage the power of statistical analysis and machine learning to predict the outcomes of soccer games using odds data provided by bookmakers. The intuition behind this project is that the odds provided by bookmakers encapsulate extensive expert analysis and market sentiment, making them a rich source of information for predicting soccer game outcomes. By analyzing these odds, which are dynamically adjusted based on various factors like team performance and player conditions, we can extract valuable insights. Utilizing statistical models and machine learning algorithms, we aim to transform this odds data into accurate predictions of game results, leveraging the quantifiable and information-rich nature of the odds.


# Japanese Soccer League (J1 League)
Visualization and prediction of Japan soccer league (J1 League) is in J1League_prediction.ipynb. I first used game results and odds from Pinnacle from 2012-2024 to predict game results. Then information about match importance and Soccer Power Index (SPI) are included.
![image](https://github.com/Jackson1356/SoccerPrediction/assets/108843164/b68634df-6a49-44c3-a523-6a8c245c35ed)


# EPL Visualization
In epl_visualization.ipynb, I analyzed game results and odds data for matches in 2019-2024 seasons with a total of 1615 matches. Several statistics about game results, total goals, half-time and full-time analysis and odds are plotted.
![image](https://github.com/Jackson1356/SoccerPrediction/assets/108843164/68b897c9-a778-4232-ba09-ab25e8ad7563)

![image](https://github.com/Jackson1356/SoccerPrediction/assets/108843164/dc8d5cc2-43ab-4efb-bc9f-047083f556b9)

# Major Leagues in Europe
In euro_leagues_prediction.ipynb, games of Germany, England, Spain and Italy leagues from 2019-2024 are analyzed and predicted by models including random forest, XGBoost and Logistic Regression. PCA, T-SNE and UMAP are also used to reduce dimensions and visualize the odds data.
![image](https://github.com/Jackson1356/SoccerPrediction/assets/108843164/5e99a085-7dad-490c-8e37-c891b67f968a)



# Data Source
odds data: https://football-data.co.uk/

spi data: https://github.com/fivethirtyeight/data/tree/master/soccer-spi
