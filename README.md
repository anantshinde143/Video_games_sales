# Video_games_sales
The purpose of this Project is to investigate whether or not an accurate Machine Learning model can be built to forecast video game sales in units based on the features given in this dataset. This hypothesis is investigated with numerous supervised ML models.

Ultimately, a decision to forecast only aggregated global sales was made due to the inherently global nature of the video game industry. Several features were droppped in the process as well due to a huge potential influx of dummy variables post-feature engneering.

Seven models were trained, out of which the lowest MSRE and best generalization is seen achieved by a Gradient Boosting Regressor model, which managed to outperform my first ever Deep Neural Network.

As a whole, this sort of prediction model could be used as one input out of many in business teams working for large video game developers.
