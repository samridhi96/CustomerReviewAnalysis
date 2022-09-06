                            This is the README file for the project
                            
                            
1. Processing Input Steps

1.1 Start the execution of the project by running ProcessingDocumentFilesIntoDataframes.ipynb which inputs document files and create dataframes. This will save the input datsframes into folder inputCSVs.

1.2 Go to folder "Preprocessing", start executing files type- "Preprocessing_bags_and_cases.ipynb" which cleans the input file and outputs the "bags_and_cases_processed.csv" in the same folder.

1.3 Go to folder "DataExploration", run the files  type- "DataExploration_bags_and_cases.ipynb" which does data exploration on the processed data and removes unwanted data and output "bags_and_cases_after_data_exploration.csv" in the same folder.


2. Merge dataframes

2.1 Run file "MergerDfs.ipynb" which merges the above files and create a single dataframe for the project.


3. Sentiment Analysis 

3.1 Go to folder "SentimentAnalysis", run "Sentiment_Analysis_NLTK_CustomerReviews.ipynb" and "Sentiment_Analysis_BERT_CustomerReviews.ipynb" to predict the sentiments and a new file "mergedDF_after_SentimentAnalysis.csv" will be generated in the same folder.


4. Topic Modelling

4.1 Go to folder "TopicModelling", run "LDA_and_BERT_for_CustomerReviews.ipynb" to create the topics and a new file "mergedDF_after_TopicModelling.csv" will be generated in the same folder.


5. Response Generation

In the main folder, run "ResponseGeneration.ipynb" that used df after topic modelling, to create response for each customer review and outputs "mergedDF_after_ResponseGeneration.csv".

** The results of LDA will be saved in the "results" folder. The architecture of the project is available in "image.png".
