# interactive-salary-prediction-tool
Salary Prediction Model
Author: Linh Dinh
Date: 05/08/24

This project is designed to predict salaries based on demographic and professional information using machine learning techniques.

Overview:
Welcome to Salary Prediction Tool. This project is designed to estimate the salary of an individual based on their demographic information such as age, gender, field of work, and level of education. Additionally, it provides an estimation of how this salary might differ if the individual were of the opposite gender.

As part of the user interaction, the program prompts the user with specific questions regarding their demographic details. Once the user provides this information, the program estimates their salary. Additionally, it provides the user with information on how their salary might differ if they were of the opposite gender.

To enhance the user experience and provide up-to-date information, we utilise an AI language model called Llama. By querying Llama, the tool ensures that the salary estimates and gender-based comparisons are as accurate and relevant as possible. This is seen in Part One: Llama Query.

To compare our data with evidence, Part Two: Pay Gap Dataset Information analyses a dataset containing information about salaries. The dataset includes fields such as gender, age, education level, and salary.

Prerequisites:
- Python 3
- Pip

Project Structure:
'main.py'/'Part 3: Main Function for Comparison': Entry point for the application
'paygap.csv': Dataset containing demographic and salary information
'part_one_probe_task.py'/'Part One: Llama Query': Contains functions for text preprocessing, model training, and salary estimation
'part_two_dataset_info.py'/'Part Two: Pay Gap Dataset Information': Contains functions for analyzing the pay gap dataset and calculating statistics
'README.txt'

Usage:
- For interactive purposes: Interact with Llama Predictions by executing part_one_probe_task.py/Part One: Llama Query and the interact() function
- For dataset analysis purposes: Interact with the dataset information by executing part_two_dataset_info.py/Part Two: Pay Gap Dataset Information and the respective print statements for the category of choice for review
- For model training and evaluating: Interact with main.py/Part 3: Main Function for Comparison and the main() function to train the model, evaluate its performance using Mean Absolute Error (MAE) and R-squared (R^2) scores, and print the results.
