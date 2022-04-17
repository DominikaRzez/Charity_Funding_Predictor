<h1>Charity Funding Predictor</h1>
<p>The binary classifier has been created in order to analyse the dataset of over 34,000 organisations and predict whether or not applicants will be successful to receive funding from the non-profit foundation - Alphabet Soup. The CSV file contains several columns with organisations metadata (e.g. name, classification, use_case, income_amt). The designed neural network model based on the input data evaluates which organisations classify for donation and which are considered too risky.
  <br>
  The dataset used for the project was a charity.csv file with details for over 34,000 organisations. Using libraries like Pandas, Scikit-Learn and TensorFlow the dataset has been pre-processed, compiled, trained, evaluated and then optimised to achieve the highest possible accuracy.
<br> Before feeding the data into the model, following transformations have been performed to ensure the quality of the data. The identification columns (EIN, NAME) not contributing to the analysis have been discarded. The columns containing more than 10 unique values have been inspected and the rare categorical variables have been binned together into a new value (Other). The categorical variables have been converted into the numerical ones using pd.get_dummies().
 <br> 
  The cleaned dataset has been split into target variable and features. The binary values of the ‘IS_SUCCESSFUL’ column became the y (target) variable and the remaining values were considered features.
Following that the pre-processed data has been split into training and testing data and scaled using StandardScaler().
<br>
  Using the TensorFlow library the deep learning model has been designed to create a binary classification model to predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset.  
  <br>
  The model has been optimised to achieve the highest possible accuracy. However, despite the optimisation the model still didn’t achieve the desired performance. The accuracy slightly improved, but still remained below the target of 75%. The model accomplished accuracy of 73,57%.
  <br>
  The full report and recommendations can be found <a href="https://github.com/DominikaRzez/Charity_Funding_Predictor/blob/main/Model%20Analysis.pdf">here.</a>
  </p>
