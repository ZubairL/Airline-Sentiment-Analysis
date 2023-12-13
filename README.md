# Twitter Sentiment Analysis for Airlines
 Our team project consisted of analyzing the sentiment of airline tweets. This was accomplished by creating models that were trained on tweets, which were then used to predict the sentiment of a tweet. We employed several models, including SVM, Random Forest, Naive Bayes, and logistic regression. The model with the highest k-fold accuracy was chosen for the final analysis. 

## Data
The data set used for analysis (training/testing models) can be found on kaggle: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

Further analaysis was done on scraped tweets using the Tweepy python module. We were unable to use the twiiter API since it is no longer free to pull tweets. The scraped tweets can be found here: https://drive.google.com/drive/folders/1CP5BmU4aE2AqBbjWHmq9F_qiUELfmN57?usp=drive_link
https://drive.google.com/drive/folders/1OF6etir7h3W8b72t6wSqW5gt_0wYBMma?usp=drive_link

## Running notebooks
Clone repo to get code:
```
 git clone https://github.com/MGT-6203-Fall-2023-Edx/Team-8.git
```
Install requirements:
```
pip install -r requirements.txt
```
### Option A - Jupyter Notebook/Lab
Open Jupyter lab:
```
jupyter lab
```
The final step would be to open the notebook and change the filepath for the tweets.csv file since the path will more than likely be different. The notebook can now be ran!

### Option B - Google Colaboratory
* Install google collab using the following guide: https://developers.google.com/earth-engine/guides/python_install-colab
* Open notebook and change tweet csv filepath
* The notebook can now be ran!

## Directory Structure
* Code - Contains notebooks for models and data cleaning 
* Visualizations - Contains notebook with visualizations for the exploratory data analysis
* Deliverables - Contains the deliverables for our team project (Proposal, Final Report, etc)
  
