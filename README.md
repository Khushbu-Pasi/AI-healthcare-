# Disease Prediction Flask App

This is a Flask-based web application that predicts diseases based on user-provided symptoms. It uses machine learning to provide suggestions, descriptions, precautions, medications, diets, and workout recommendations for the predicted disease.

## Features

- Predicts diseases based on symptoms input
- Provides a detailed description of the disease
- Recommends precautions, medications, diets, and workouts for the predicted disease

## Technologies Used

- Python (Flask, NumPy, Pandas)
- Scikit-learn for Machine Learning
- HTML templates for the frontend
- Pre-trained model (`svc.pkl`)

## Project Structure

- `app.py`: Main Flask app file
- `templates/`: HTML templates for the web app
- `models/`: Contains the saved machine learning model (`svc.pkl`)
- `datasets/`: CSV files used for disease descriptions, medications, diets, precautions, and workout recommendations
- `constant/`: Contains disease and symptom mappings

## Prerequisites

Make sure you have Python 3.x installed on your system. You can download it from [here](https://www.python.org/downloads/).

## How to Set Up the Project

1. Clone the repository to your local machine or download it:

2. Install the required Python packages using `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

3. Place your model (`svc.pkl`) and dataset files inside the `models/` and `datasets/` directories, respectively.

4. Run the Flask app:

    ```bash
    python main.py
    ```

5. Open your browser and go to:

    ```
    http://127.0.0.1:5000/
    ```

    The web app will be running locally on your machine.

## Usage

1. Enter symptoms (comma-separated) in the input field.
2. Select what you want to know (Disease, Description, Precaution, Medications, Diets, Workouts).
3. Submit the form and get the predictions or recommendations.

## Project Files

- `main.py`: Main Flask app logic
- `templates/`: HTML templates for rendering the web pages
- `datasets/`: Contains the CSV files for symptoms, disease descriptions, precautions, medications, diets, and workouts
- `models/`: Contains the saved machine learning model (`svc.pkl`)
- `constant/`: Dictionaries for symptoms and diseases mappings


<img width="1336" height="611" alt="image" src="https://github.com/user-attachments/assets/84ef9fa6-7008-497b-960a-f01ccf165f3c" />
<img width="1210" height="586" alt="image" src="https://github.com/user-attachments/assets/4848ae47-0629-4bb2-a82a-9884169ca8cf" />
<img width="996" height="590" alt="image" src="https://github.com/user-attachments/assets/7d61fca5-c24f-4e75-94ec-f4624f700f48" />
<img width="1293" height="596" alt="image" src="https://github.com/user-attachments/assets/5487e9a9-9565-4ee8-af6c-9757800a7631" />


