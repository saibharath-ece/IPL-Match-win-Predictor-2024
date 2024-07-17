# IPL-Match-win-Predictor-2024
processes given the data, this ML can provide information on IPL match winner based on data

Step 1 - Import the files
Step 2 - Given the data, identifying the number of deliveries and matches
Step 3 - Capture only the first innings, as we will be predicting for the second innings
Step 4 - Merging the total first innings score df with the matches df, where left side merging is done on 'id' columns for the matches and right side merging is done on 'match_id' column of the totalrun_df
Step 5 - consider only frequently occuring teams, which are mentioned in the team list
Step 6 - Merging match_df with deliveries on match_id (Datas of two files)
Step 7 - Comapre the data with second innings data and fill the Null Values with 0
step 8 - calculate run rate and Required rate
Step 9 - Create a model
