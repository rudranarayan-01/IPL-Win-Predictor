# IPL WINNING PREDICTION USING ML

Welcome to the "IPL Win Predictor" project! This machine learning model, built using logistic regression, predicts the probability of a team winning an IPL match based on the current match situation. Get ready to make data-driven predictions!

## About This Project
The "IPL Win Predictor" leverages logistic regression to provide insights into the probability of a team winning an IPL match. This model analyzes various match features, team performance, and player statistics to offer real-time predictions.

## Project Preview
![Screenshot 2024-11-10 004134](https://github.com/user-attachments/assets/973f98de-a9ac-48bf-826c-a49ab5cd34a0)


## Features
Real-Time Predictions: Get live predictions for IPL match outcomes based on the current match situation.

Interactive Interface: The predictor is deployed on Streamlit, offering a user-friendly interface for exploring match scenarios.

Customizable Inputs: Adjust the match parameters and teams to simulate different match scenarios.

Deployment: Hosted on Streamlit Cloud for easy access and sharing.

## Usage
To make predictions, provide the following parameters when prompted:

- Batting Team: The team currently at bat.
- Bowling Team: The team currently bowling.
- City: The location of the match.
- Current runs: The current score of batting team.
- Overs Completed: The number of overs completed.
- Wickets: The number of wickets lost.
- Target Runs: The total runs scored by a bowling team.
  
The predictor will calculate the probability of the batting team winning based on these parameters and the current match situation.

## Technologies Used
This project leverages the following technologies:

- Python
- Sklearn Logistic Regression
- NumPy
- pandas
- Streamlit


## Installation

To run this project locally, follow these steps:

Clone the repository to your local machine using this command:

``bash
git clone https://github.com/rajatrawal/ipl-win-predictor.git
``
Navigate to the project directory:

``bash
cd IPL-Win-Predictor
``
Install the required Python libraries:

``bash
pip install -r requirements.txt
``

Run the Streamlit app locally:

``bash
streamlit run app.py
``

Open the provided local URL in your web browser to access the IPL Win Predictor.
