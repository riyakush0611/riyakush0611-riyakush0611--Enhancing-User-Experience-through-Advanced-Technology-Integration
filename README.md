
#Till now I have Implemented the Collaborative Filtering for the personalized Experience to the user further I will create thehybrid model by invloving content based filtering.I will use the HDFS file system to improve scalability , efficiency and security purpose.
Dataset to be used is as follows:
https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey#survey_results_public.csv

Dataset for job-postings
https://www.kaggle.com/PromptCloudHQ/us-technology-jobs-on-dicecom

To run the files, download the stack overflow dataset from the given link and place into /data/user_preprocessing folder. The feature extraction and preprocessing of the user profiles are being done by feature_extraction_user_a.ipynb and feature_extraction_user_b.ipynb. The extracted features are already in /data/user_preprocessing folder.


## Collaborative Filtering model

To run the files, download the stack overflow dataset and the job-postings dataset from the given link and place into /data/collaborative filtering folder.
Run collaborative filtering.ipynb to check the output of CF recommendations based on Content based recommendations.

