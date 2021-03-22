# Project 2 - Ames Housing Data and Kaggle Challenge

Welcome to Project 2! Let's model!

**Primary Learning Objectives:**
1. Creating and iteratively refining a regression model.
2. Using [Kaggle](https://www.kaggle.com/t/8c2cb2d4d064417ca44ca5719a488c5d) to practice the modeling process.
3. Providing business insights through reporting and presentation.

You are tasked with creating a machine learning model based on the Ames Housing Dataset. This model will predict the price of a house at sale.

The Ames Housing Dataset is contains over 70 columns of different features relating to houses.

---
## Deliverables 

- We are hosting a competition on Kaggle to give you the opportunity to practice your modeling skills. You must upload at least one of your model's predictions to the competition.
- You will submit a technical report and a presentation in your submission Repo. 
- You will present your findings to your classmates and instructors.

**You may find that the best model for Kaggle is not the best model to address your data science problem.**


## Set up

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click here: [Regression Challenge Sign Up](https://www.kaggle.com/t/8c2cb2d4d064417ca44ca5719a488c5d) to **join** the competition (otherwise you will not be able to make submissions!)
3. Review the material on the Kaggle challenge site.
4. Review the [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).

## The Modeling Process

1. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the target that you are trying to predict in your Regression model.
2. Generate your regression model using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
3. Predict the values for your target column in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.
    - **Note**: Kaggle expects to see your submissions in a specific format. Check the challenge's page to make sure you are formatting your CSVs correctly!
    - **You are limited to models you've learned in class**. In other words, you cannot use XGBoost, Neural Networks or any other more advanced model for this project.
4. Evaluate your models!
    - consider your evaluation metrics
    - consider your baseline score
    - how can your model be used for inference?
    - why do you believe your model will generalize to new data?

## Submission

- Presentation slides must be submitted by 9AM ET on **Friday, Jan. 8**. 
- Your technical report must be submitted in your submission repository by 9PM ET on **Friday, Jan. 8**.
- The Kaggle competition will close at 9PM ET **Friday, Jan. 8**.

Your technical report must include:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis and models (renamed to describe your project)
- Data files
- Presentation slides
- Any other necessary files (images, etc.)


---

## Presentation Structure

- **10 Minutes maximum for your presentation. Then Q&A to follow.**
- Use Google Slides or some other presentation system (Keynote, Powerpoint, etc).
- Consider your audience. 
- Start with the **problem** you are solving.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data science problem.

Be sure to rehearse and time your presentation before class. 😀

### See the grading rubric [here](./rubric.md)
