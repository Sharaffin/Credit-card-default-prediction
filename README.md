# Credit-card-default-prediction
<h><img src="https://media.giphy.com/media/xT5LMXFGXmuKKkoCWs/giphy.gif" align="centre"></h>
<h1 align="center"> Credit Card Default Prediction - ML Classification </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p>The fundamental objective of the project is to analyze credit card data collected from Taiwan-based credit card issuers and predict whether or not a consumer will default on their credit cards, as well as identify the key drivers behind this. This would inform the issuer’s decisions on who to give a credit card.</p>

<h2> :floppy_disk: Data Description</h2>

<p>The dataset contained over 25 variables and they are listed below</p>

**GENDER**            -    1 – Married ,2 – Single, 3 – Others

**EDUCATION**         -  1 – Graduate School,2 – University ,3 – High School, 4 – Others 

**MARRIAGE**          -  1 – Married, 2 – Single ,3 – Others

**REPAYMENT HISTORY** -  PAY_1 – September, PAY_2 – August, PAY_3 –  July, PAY_4 – June, PAY_5 –  May, PAY_6 – April

**DEFAULT**           -  1- YES , 0 - NO 

**LIMIT_BALANCE**     - Amount of Credit given in New Taiwan Dollars

**AGE**               - Age in years 

**BILL AMOUNT**       - BILL_AMT1 – September, BILL_AMT2 –  August, BILL_AMT3 – July, BILL_AMT4 – June, BILL_AMT5 – May, BILL_AMT6 – April

**PAY_AMOUNT**        - PAY_AMT1 – September. PAY_AMT2 –  August, PAY_AMT3 –  July, PAY_AMT4 –  June, PAY_AMT5 – May, PAY_AMT6 –  April


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Data Pipeline</h2>

● Data Processing : We checked for missing values, column type, column name, duplicate records, identified outliers, numerical categorical data and cleaned the dataset

● Exploratory Data Analysis (EDA): Exploratory data analysis using tables and graphs to derive the observations from the data 

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 executable files, 2 text files as well as 1 directories as follows:</p>
<h4>Executable Files:</h4>

<ul>
  <li><b>credit_card_default_prediction.ipynb</b> - Google Colab notebook with all the output visible</li>
  <li><b>Credit Card Default Prediction-Project Summary-Cohort Austin-DataGenix.docx</b> - Contains the summary of the project.</li>
  <li><b>Credit Card Default Technical Document.docx</b> - Contains whole analysis strategy and analysis methodology followed for the project.</li>
</ul>

<h4>Source Directories:</h4>
<ul>
  <li><b>https://www.kaggle.com/code/ainslie/credit-card-default-prediction-analysis/data</b> - Includes all the required data.</li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Algorithms Used </h2>
<li>Logistic Classification</li>
<li>Support Vector Classification</li>
<li>Random Forest classifier</li>
<li>Gradient Boosting Classifier</li>
<li>XGBoost</li>
<li>Bagging Classifier</li>

<p>XGBOOST  has the highest accuracy of 82.5 % with a recall of 67.7 % and KS chart value of 0.447.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :clipboard: Future Work</h2>
<li>Models are not exhaustive. Other models could perform better.</li>
<li>To Get more computational resources to tune XGBoost parameters.</li>
<li>Acquire more customer data and useful features like customer income.</li>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>:floppy_disk: Conclusion</h2>
<p>The dataset was not normally distributed and mostly it was right skewed. There is NO significant difference in the proportion of default payment across different education levels. But clients who have lower than high school level education tend to have default payment more. Married clients have a higher default payment rate than single or other marital status clients. People who have the payment delay for two months have a high ratio of default next month (October). In September, a quarter of customers who repay one month later have default payment next month in October. This situation does not exist in other months as almost no one repay one month later The developed models took into account all possible factors and data. This final chosen model would benefit the bank before they make any decisions against that customers.</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CREDITS -->
<h2 id="credits"> :scroll: Credits</h2>

Sharaffin B | Data Science | Machine Learning | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations and Data Science related job roles</i></p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<h2> :books: References</h2>
<ul>
  <li><p>KS Chart in Youtube </p>
      <p>Available: https://www.youtube.com/watch?v=hNs9o5qiY8U&t=189s</p>
  </li>
 
  <li><p>ML classification Algorithms </p>
      <p>Available: https://towardsdatascience.com/top-machine-learning-algorithms-for-classification-2197870ff501</p>
  </li>
 
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)



