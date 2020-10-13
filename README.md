# Job-Mail-Classification
# Steps to predict whether new incoming mail would be job mail or not
1. Import data using libraries such as numpy, pandas etc.
2. Read the data and store them in an object.
3. Seperate the features and targets. Let 'X' indicate features and 'y' indicate target.
4. Split the data into train and test data.
5. Use count vectorizer library to create 'bag of words' which will convert words into vectors and removes stop words such as the,is,are etc.
6. Convert our train and test data into vector form.
7. Use Naive Bayes algorithm to train and test the data
8. Use performance metrics to evaluate the model.
