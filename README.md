The objective of the project was to predict the nature of the reviews of customers on a particular Amazon product. The aim was to achieve this using Sentiment analysis 
by looking at the dataset of tweets, analysing the nature of the words that occur in a positive review as compared to a negative review and then finally applying 
different models to perform the prediction.

The general overview of the notebook is as follows - 
It starts off by importing the data set of reviews to a pandas dataframe. The dataset contains around 3150 reviews on which I aimed to apply the model. A general 
statistical description of the model was then obtained to find out some parameters related to the data. I then plotted some graphs and plots to obtain a visual representation
of the distribution, such as the bar chart to find the number of people who gave each kind of review. This was followed by plotting a WordCloud to find out the words that most
frequently occur in a positive or a negative review. The words that appear larger in size in the Wordcloud are the ones that appear more frequently. This helps to give
an indication of what words lead to the review being positive as compared to negative. 

The next task was to perform data cleaning in the model. I created a pipeline in order to perform all cleaning tasks at once, such as removing the stopwords, removing 
punctuations and then obtaining the rest of the data. The train test split was then performed with 25 percent of the data taken as the test size. The predictions were 
then performed using three different ML models. These were the Naive-BBayes classifier model, Logistic Regression and Gradient Boosting Classifier. I then printed
out the confusion matrix classification report and the accuracy score. The acccuracy for the data set came out to be around 93 percent. 
