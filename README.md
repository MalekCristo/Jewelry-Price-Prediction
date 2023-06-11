# Jewelry-Price-Prediction

We have developed this model to accurately predict jewelry prices with a remarkable 80% level of accuracy. This model serves as an invaluable tool for website owners, empowering them to establish optimal price points for their potential products. Moreover, it provides customers with valuable insights into the pricing of customized jewelry pieces, allowing them to make informed decisions.

<H1>Project Overview:</H1>
<ol>
  <li>Scraped welry.com for 780 jewelery Products. </li>
  <li>Cleaned and Preprocessed Data. </li>
  <li>EDA. </li>
  <li>Feature Selection. </li>
  <li>Models Building: Decision Tree, Linear Discriminant Analysis, Support Vector Machine, Random Forest. </li>
</ol>

<H1>Data Preprocessing and Cleaning : </H1>
<h3>Handle missing data:</h3>
<p>We identified the presence of missing values in both the price and weight variables. 
  To ensure data integrity, we employed a robust data cleaning approach. Specifically, we replaced these missing values with the mean values of their respective variables.</p>
<h3>Fix structural errors by creating categories:</h3>
<p>The “article_name” column contains some inconsistent words and expressions so we 
organize the data by creating types which are mainly 7: Earrings, necklaces,rings, pendant, bracelet.</p>

<h3>Outliers detection and removal :</h3>
In order to have an idea about the outliers in our data set we chose boxplots and scatter 
plots as visulization tools.
<br>In order to detect the values of outliers we performed z-score analysis. 
<br>We set threshold = 3 ie : we defined outliers as points situated at 3 standard deviations around 
the mean. Prices in range [1700,7000] are considered outliers and were removed.

<h3>Feature Selection : </h3>




