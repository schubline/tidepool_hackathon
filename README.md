# Project 5 - Tidepool Hackathon Challenge
Using a limited number of observations taken from the blood glucose meters of insulin dependent diabetics,
build, test and assess the effectiveness of a supervised classification model to predict whether to patient is type
one or type two diabetic.

## The Data
The data is cleaned and groomed, 387 observations of 24 variables, with a class target(column 2) and
deidentified random Id (column 1).

### Exploratory Data Analysis
Do not skip this stage, it is very likely that there are real and meaningful correlations between age, time of
diagnoses and years living with diabetes which are both predictive and inidicative of overall diabetic health.
Failing to properly explore and visualize prior to modeling could be catestrophic. Take the time to look at the
data and make some assumptions based on this prior to building a model.

### Missing Data
You will need to address missing data in your model. Most observations have some, so you cannot just throw
the observation away. How will you handle these missing values?

### Feature Engineering & Train Test Split
It is probable that you will see some relationships in your EDA, so you will need to think through how to
'aggregate' if you do. Remember, even if you leave age as a number in your model unchanged, it is likely that
ages and lenght of diagnoses time are influential on ones type.
So, be sure that you have a range of ages included both training and test sets. With only 387 observations, you
will not have enough observations to just shuffle and split, so you will need to figure out how to group ages and
split with defference to these groupings to be sure that we are training and testing our model on relative all
ages.

## The Model

Each group will build a single classification model, of a randomly assigned type, to try to predict the classes,type 1, type 2. You will work within the contraints and best practices of your model type for the duration of this
hackathon. The goal is build, test and quantify the utility of your given model.
Once a basic model is built, how can you best tune the parameters, tweak the data, engineer variable to
improve the predictive utility?

# Deliverables

## 1:00 PM Today
15 minute team stand-up on challenges each team is facing on preparing to model and what you intend to do/
have done to address it. This is about sharing information that will help other teams overcome issues with
missing data, feature engineering, stratified sampling

## 4:00 PM Today
Each group will give a 5 minute rundown of your model. How you prepared the data, what methods you used to
manage missing data and how you massaged variables to best work in the model, as well as how your model
performed and what you did to tune it.
It is completely acceptable to simply present from your notebook. One or both team-members may present as
long as both members share the work in the evolution of the project today.

## Monday 10:00 AM
Each group will submit one notebook Monday Morning at 10:00 AM sharp with the following:
Properly formatted Markdown that defines the steps you have taken to groom, explore, model, test, refine and
quantify the results of your analysis.

The notebook should be clean, clear and understandable to someone with basic python skills. They should be
able to follow the logic of your process, visualize what your numbers mean and speak meaningfully to the
merits of this approach based on your notebook.

# Follow Up
We may spend a couple of hours next week with the data science manager at Tidepool going over the models
we build. As a result, he may be interested in working with a team or teams to build a blog post around you
discoveries and process. This is a GREAT portfolio piece..so if you are asked, lean into this forcefully and make
something spectacular!





