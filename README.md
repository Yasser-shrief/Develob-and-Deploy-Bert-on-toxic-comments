# Developing and Deploying Fine-Tuned BERT-Transformers Model on Streamlit Cloud | FASTAPI
### Overview

This repository contains code for deploying a fine-tuned BERT-Transformers model on Streamlit Cloud and FASTAPI. The model is used to classify toxic and non-toxic comments using the Hugging Face platform. The Streamlit application allows users to input text and get a prediction on whether the input is toxic or not. 

### Installation:  

To run this application locally on Streamlit Cloud, follow these steps:  


1-Clone this repository to your local machine.<br>
2-Navigate to the project directory in the terminal.<br>
3-Install the required dependencies by running **pip install -r requirements.txt**.<br>
4-Run the application by running **streamlit run app.py**.<br>
5-Open a web browser and go to **http://localhost:8501** to see the Streamlit app.<br>

Note: Before running the application, make sure you have a valid Hugging Face API key. The API key should be set as an environment variable with the name HF_API_KEY.  


## Deploying to Streamlit Cloud

This application has already been deployed to Streamlit Cloud, and can be accessed using the following link:<br>
https://yasser-shrief-develob-and-deploy-bert-on-toxic-comme-app-6nomqv.streamlit.app/  

To deploy the application to Streamlit Cloud, follow these steps:<br>

1-Fork this repository.<br>
2-Create a new account on Streamlit Cloud if you haven't already.<br>
3-Connect your GitHub account to Streamlit Cloud.<br>
4-Create a new app on Streamlit Cloud, and link it to your forked repository.<br>
5-Set the environment variable HF_API_KEY in the Streamlit Cloud dashboard.<br>
6-Deploy the app.<br> 

### Files

The main files in this repository are:

**app.py:** The Streamlit app that runs the classification model.<br>
**model.py:** Defines the classification model using the Hugging Face Transformers library.<br>
**utils.py:** Contains utility functions for loading the model and preprocessing input text.<br>
**requirements.txt:** Lists the Python dependencies required to run the app.<br>

## Conclusion

This repository provides a simple example of how to deploy a fine-tuned BERT-Transformers model on Streamlit Cloud using the Hugging Face platform. With some modifications, this approach can be applied to other NLP classification tasks.
