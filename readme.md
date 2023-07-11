# Introduction:
The development of a COVID-19 vaccine is already underway, building upon the success of vaccines in preventing diseases such as measles and the flu, which have significantly reduced illness and saved countless lives worldwide. However, the rise of the "anti-vaxxer" movement in some countries has resulted in lower vaccination rates and the reemergence of previously controlled diseases.

While it may take several months for COVID-19 vaccines to be widely available globally, it is crucial to monitor public sentiment towards vaccinations both now and in the future, when COVID-19 vaccines become accessible to the public. The presence of anti-vaccination sentiment poses a significant threat to long-term global efforts in controlling the spread of COVID-19.

## Objective:
The objective of this challenge is to develop a machine learning model that can assess the sentiment of Twitter posts related to vaccinations as positive, neutral, or negative. The model will be deployed using Streamlit on a Docker Container, enabling efficient analysis and visualization of the results.

## Dataset:
The dataset provided consists of tweets that have been classified as pro-vaccine (1), neutral (0), or anti-vaccine (-1). The tweets have undergone preprocessing, with usernames and web addresses removed to ensure privacy and focus solely on the text content.

## Variable Definitions:

- tweet_id: A unique identifier for each tweet in the dataset.
- safe_tweet: The text content of the tweet, excluding sensitive information like usernames and URLs.
- label: The sentiment of the tweet, represented by -1 for negative, 0 for neutral, and 1 for positive.
- agreement: The tweets have been labeled by three reviewers, and the agreement column indicates the percentage of reviewers who agreed on the assigned label. While this column can be utilized during model training, the agreement data will not be provided for the test set.

## Files Available for Download:
- Train.csv: This file contains labeled tweets that can be used to train your machine learning model.
- Test.csv: This file contains tweets that you need to classify using the trained model.
- SampleSubmission.csv: An example submission file is provided to illustrate the expected format. The order of rows is not significant, but the ID names must be accurate. The values in the 'label' column should range between -1 and 1.
- Fine_tuning_Hugging_face_text_classification_model.ipynb: This starter notebook provides guidance for making your initial submission for this challenge, assisting you in getting started with the task.

By analyzing this dataset and building a robust machine learning model, we aim to gain insights into public sentiment towards vaccinations, enabling effective monitoring and understanding of attitudes that may impact global vaccination efforts, particularly in the context of COVID-19.