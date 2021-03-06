    1. What data have you gathered, and how did you gather it?
    I pulled all loan approval data from LendingClub: https://www.lendingclub.com/info/download-data.action
    
    2. How have you explored the data and what insights have you gained as a result?
    I started a Jupyter notebook and imported all my data handling / predicting and visualization tools. I used pd.read to start looking at my data. There's a lot of data cleaning to be done (mostly formatting and clearning out a lot of NaN values). So I've temporarily jumped back in CSV to help me better understand my data for now. I have unique loan ID's (which can be used as a master key) followed by 110 columns. About 50% of those columns are NaaN values. I have roughly 42,539 Rows of columns, but it looks like there are multiple data sets in a single csv - a set of data for approved loans, and a set of data of loans that did not meet the credit policy - all stored in a single file. I have a total of 5 files.
    
    3. Will you be able to answer your question with this data, or do you need to gather more data (or adjust your question)?
    I believe I have more than enough data. It looks like I'm going to have to do some heavy cleaning of the data, and some feature engineering for the large amount of NaaN values.
    
    4. What modeling approach are you using to answer your question?
    I'm not quite sure. I believe a Random Forest, but I'm going to start with a simple Logistic Regression model and see where that gets me.