# Machine_Learning
A comprehensive list of Machine Learning projects

# 6 Step Machine Learning Framework
All the steps below are represented as an iterative process.

## Problem Definition?
The important quesiton to answer: What problem are we trying to solve?

- Supervised Machine Learning
    I know my inputs and outputs
    Have data and Labels

    - Classification
        Is this example one thing or another?
        Ex. Binary (2 options) or Multi-class (More than 2)

    - Regression
        How much will this house sell for?
        How many people will buy this app?

- Unsupervised Machine Learning
    I'm not sure of the outputs but I have inputs
    Have data but no labels

- Transfer Learning
    I think my problem may be similar to something else
    Utilize a trained model and repurpose for another task

- Reinforcement Learning
    Agent learns to interact with its environment in order to maximize a reward
    Reward is good, pushishment is bad

- When shouldn't you use machine learning?
    Will a simple hadn-code instruction based system work?

## Data
The important quesiton to answer: What kind of data do we have?

- Structured
    Consistent formats

- Unstructured
    Images, natural language text, audio

- Static
    Data is fixed and doesn't change over time

- Streaming
    Data is changing over time

## Evaluation
The important quesiton to answer: What defines success for us?

Different types of metrics
    Classification - Accuracy, Precision, Recall
    Regression - Mean absolute Error (MAE), Mean squared error (MSE), Root mean squared error (RMSE)
    Recommendation - Precision at K

Metrics can change as projects go on

## Features
The important quesiton to answer: What do we already know about the data?

- Different forms of data within our structured/unstructured elements
    Numerical, Categorical

- Feature Engineering
    Looking at different features of data and creating new ones/altering existing ones

- Feature Coverage
    How many samples have different featuers? Ideally, every sample has the same features

## Modeling

The important quesiton to answer: Based on our problem and data, what model should we use?

- 3 sets (train, validation, test)
- Generalization
    The ability for a machine learning model to perform well on data it hasn't seen before

1. Choosing and training a model (Training)
    Structured - CatBoost, XGBoost, Random Forest
    Unstructured - Deep learning, Transfer learning

- Goal: Minimise time between experiments
    Use smaller sets for training
    Use less complicated models

Summary Points
- Some models work better than others on different problems
- Add complexity (as needed)

2. Tuning a model (Validation)

Summary Points
- Machine learning models have hyperparameters you can adjust
- A models first results aren't its last
- Tuning can take place on training or validation data sets

3. Model comparison (Test)

All experiments should be conducted on different portions of your data.

Training data set — Use this set for model training, 70–80% of your data is the standard.
Validation/development data set — Use this set for model hyperparameter tuning and experimentation evaluation, 10–15% of your data is the standard.
Test data set — Use this set for model testing and comparison, 10–15% of your data is the standard.
These amounts can fluctuate slightly, depending on your problem and the data you have.

Poor performance on training data means the model hasn’t learned properly and is underfitting. Try a different model, improve the existing one through hyperparameter, reduce the amount of features or train longer.

Great performance on the training data but poor performance on test data means your model doesn’t generalize well. Your model may be overfitting the training data. Try using a simpler model or making sure your the test data is of the same style your model is training on.

Another form of overfitting can come in the form of better performance on test data than training data. This may mean your testing data is leaking into your training data (incorrect data splits) or you've spent too much time optimizing your model for the test set data. Ensure your training and test datasets are kept separate at all times and avoid optimizing a models performance on the test set (use the training and validation sets for model improvement).

Poor performance once deployed (in the real world) means there’s a difference in what you trained and tested your model on and what is actually happening. Ensure the data you're using during experimentation matches up with the data you're using in production.

Summary Points
- Want to avoid overfitting and underfitting (head towards generality)
- Keep the test set separate at all costs
- Compare apples to apples
- One best performance metric does not equal best model

## Experimentation
The most import question to ask is How could we improve/what can we try next? Can we use other models? Experiment, Experiment, Experiment..

# Resources
Elemnts of AI

