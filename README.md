
# Predicting Match Outcomes in Age of Empires II
**Course:** AAI201 Machine Learning  
**Student:** Ben Seifert  

## Project Overview
This project applies a Random Forest Classifier to a dataset of 100,000+ Age of Empires II matches. The goal is to determine if pre-game variables like **Civilization choice** and **Map type** can accurately predict a winner.

## Key Results
* **Final Model Accuracy:** 52.15%
* **Primary Insight:** The "Franks" civilization remains the most significant predictor of victory in the current meta.
* **Technical Achievement:** Successfully identified and resolved "Target Leakage" (which initially caused 100% false accuracy) by balancing the dataset and removing post-match metadata.

## Tech Stack
* **Language:** Python 3.12
* **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Model:** Random Forest Classifier (Pruned with `max_depth=5`)

## Project Structure
* `AAI201_Capstone_Seifert.ipynb`: The full data science pipeline (Cleaning, Training, Evaluation).
* `aoe_data.csv`: The processed match history dataset.
* `aoe2_capstone_presentation.html`: Final presentation slides.

## Reflections
The most challenging part of this project was data cleaning. Learning to recognize that 100% accuracy was a "failure" of data leakage rather than a success was a pivotal moment in my understanding of Machine Learning ethics and bias.
