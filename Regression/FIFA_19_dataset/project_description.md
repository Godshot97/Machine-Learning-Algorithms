<h1>FIFA 19 footballers dataset</h1>
<h2>This is my first machine learning project.<br> The dataset came from https://www.kaggle.com/karangadiya/fifa19. <br>I created a model estimating the value of a player based on their skills,<br> physical characteristics and recognition.</h2>

<b>Business goal:</b> provide information for football agents and managers of football clubs that will allow them to negotiate more adequate amounts of transfers.

<b>In file number 1</b>, I reviewed and processed the data for the machine learning model. Much of the data was in text format, so I had to make some transformations to be able to pass them to the machine learning model. Finally, I standardized the data using StandarScaler.

<b>In file number 2</b>, I trained 4 different regression models (Linear Regression, SVR, Decision Tree and Random Forest). Next I chose Random Forest for further tuning because it performed best. I used a random search method.
