# Sentiment_Analysis
This is a repository to learn building a sentiment predication model


# Amazon Review Classification
 - <B>Files:</B>
   - Data_Exploration_and_Modelling.ipynb : Notebook file used for EDA, Data cleaning and Model exploration and building.
   - app.py : Flask App for testing the generated models
   - Models : Pickel files for generated models and other requried pickel files
   - Templates : HTML files for Flask app


# Steps to run this flask app on your local machine:
 
Step 1: Clone the repository
```
git clone https://github.com/Surbhit01/Amazon-Alexa-Reviews.git
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n amazonreview python=3.10
```
```
conda activate amazonreview
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```

Step 4: Run the app
```
flask --app api.py run
```

Step 5: The app will run on port 5000. 
```
localhost:5000
```
