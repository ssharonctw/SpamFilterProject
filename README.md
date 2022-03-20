# Spam Message Classifier 
### built with NLTK and Scikit-learn (acheiving 99% accuracy)
Demo ready at [here](https://ssharonctw.github.io/SpamFilterProject/)

## Data Source Overview
The data set is from the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). It contains 5000 SMS labeled messages that have been collected for mobile phone spam research. 

## Project Overview
1. Load the Dataset
..* Use the pandas dataframe to ensure value are properly loaded

2. Data Preprocessing</summary>
..* Convert the class labels (span/ham) to binray values uesing sklearn LabelEncoder
..* Replace email address, url, phonenumbers with generic representation
..* Remove stop words and keepwing word stems

3. Features Generating</summary>
..* View words as features, choosing the top 500-1500 common words as features
..* Process each sentence and generate the word_feature table for each sentence

4. Model Training and Performance Evaluation</summary>
..* Split data set to 75% training data and 25% testing data. 
..* Train models with different algorithms (including ensemble methods of classifier voting) and compare the performances.

