# Final Project - IA376M: Visual Data Analysis (Visual Analytics)

This repository contains the final project for the **Visual Data Analysis** course (IA376M). The project investigates exercise patterns and their relationship with demographic and physiological variables of gym members. Using exploratory data analysis and visualizations, we aim to answer key research questions regarding workout effectiveness, BMI influence, and weekly workout frequency.

## 📋 Objectives

The research questions addressed in this project are:

1. [**Which type of exercise is more effective in burning calories: aerobic or anaerobic?**](./notebooks/calories_burned_by_exercise_type.ipynb)

2. [**Does BMI influence the choice of workout type?**](./notebooks/BMI_influence_workout_type.ipynb)
3. [**Is weekly workout frequency associated with a higher number of calories burned per session?**](./notebooks/frequency_burns_more_calories.ipynb) 

If you click on each question you will be redirected to the notebook that answers the question.

We created a notebook only for the  Exploratory Data Analysis task, check it out [**EDA Notebook**](./notebooks/eda.ipynb)

## 📂 Dataset

We are using the *Gym Members Exercise Dataset*, available on [Kaggle](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset), which provides detailed insights into workout routines, physical attributes, and performance metrics of gym members.

**Key features of the dataset**:
- **Demographics**: Age, gender, weight, height
- **Physiology**: Maximum, average, and resting heart rate (BPM)
- **Workout details**: Session duration, calories burned, workout type (e.g., Cardio, Strength, Yoga, HIIT)
- **Additional attributes**: Body fat percentage, water intake, weekly workout frequency, experience level, and BMI

This dataset was generated using realistic profiles based on simulated data of gym-goers.

## 🔍 Methodology

To address each research question, we will follow these steps:

1. **Data Preprocessing**:
   - Data cleaning, handling missing values, and standardizing columns.
   
2. **Exploratory Data Analysis (EDA)**:
   - Initial visualizations and descriptive analysis to understand distributions, correlations, and trends.

3. **Specific Analysis for Each Question**:
   - **Workout effectiveness**: Comparing calories burned in aerobic and anaerobic exercises using descriptive statistics and visualizations, hypothesis test.
   - **BMI Influence**: Assessing the relationship between BMI and workout type choice.
   - **Workout frequency and calorie burn association**: Correlation or regression analysis to evaluate the relationship between weekly frequency and average calories burned per session.

4. **Documentation and Visualization**:
   - Creating graphs and tables for data interpretation and preparing a final report with conclusions.

## 🗂 Project Structure

- **`data/`**: Contains the dataset used in the project.
- **`notebooks/`**: Jupyter notebooks with data analysis, visualizations, and experiments.
- **`docs/`**: Additional documentation and the final project presentation.
- **`README.md`**: This document.

## 🚀 How to Run the Project

### Prerequisites

- **Python 3.9+** and libraries listed in `requirements.txt`.

### Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/username/final-project-IA376M.git
   cd final-project-IA376M
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analyses:
   - Navigate to the `notebooks/` folder and open the Jupyter notebooks to explore the EDA and specific analyses for each research question.

## 📈 Expected Outcomes

- **Answers to Research Questions**: Conclusions on the effectiveness of different exercise types, the impact of BMI on workout choice, and the relationship between workout frequency and calories burned.
- **Visualizations**: Graphs and tables illustrating the main insights of the project.
- **Final Report**: A detailed document containing the methodology, analysis, and conclusions, to be presented in class.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📞 Contact

For questions or suggestions, please reach out:

- **Raisson Leal Silva**
    - **Email**: raissonls@hotmail.com
    - **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/raisson-leal-silva-9208a8167/)

- **Pedro Luís Azevedo Costa**
    - **Email**: pdcost@icloud.com
    - **LinkedIn**: [LinkedIn](https://www.linkedin.com/in/pedro-lu%C3%ADs-azevedo-costa-2a8b22147/)
