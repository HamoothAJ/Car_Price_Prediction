# Car Price Prediction Machine Learning Model

This project is a *Linear Regression* machine learning model built using *Python* to predict car prices based on various features such as make, model, year, mileage, and more. The model was trained using a dataset containing car details and deployed as a web application, allowing users to input car specifications and get real-time price predictions.

## Project Overview

### Steps Involved:

1.  *Data Extraction & Preprocessing*:
    -   Extracted and cleaned the dataset by handling missing values and removing duplicate entries.
    -   Preprocessed the data for analysis and model building.

2.  *Exploratory Data Analysis (EDA)*:
    -   Conducted analysis to understand the relationships between car features (e.g., make, year, mileage) and price.

3.  *Model Creation & Training*:
    -   Built and trained a *Linear Regression* model using *Scikit-learn*.
    -   Split the data into training and testing sets to ensure the model's accuracy.

4.  *Model Evaluation*:
    -   Evaluated the model's performance using the *Mean Absolute Error* (MAE) and *R-squared* ($R^2$) value to assess its accuracy.

5.  *Deployment*:
    -   Deployed the trained machine learning model as a web application using *Flask* (or *Streamlit*).
    -   The web app allows users to input car features and get price predictions in real time.

## Features

-   Predict car prices based on various features such as make, model, year, mileage, etc.
-   Cleaned and preprocessed data to ensure model accuracy.
-   Deployed the model as a web application for easy access and interaction.

## Technologies Used

-   *Python* (Pandas, Numpy, Scikit-learn)
-   *Machine Learning* (Linear Regression)
-   *Web Deployment* (Flask / Streamlit)
-   *Data Preprocessing* (Handling Null Values, Data Cleaning)

## How to Run the Project Locally

### Prerequisites:

-   Python 3.x
-   Git

### Steps to Set Up:

1.  *Clone the Repository*:
    bash
    git clone [https://github.com/HamoothAJ/Car_Price_Prediction.git](https://github.com/HamoothAJ/Car_Price_Prediction.git)
    cd Car_Price_Prediction
    

2.  *Set Up Virtual Environment*:
    Create a virtual environment:
    bash
    python -m venv .venv
    
    Activate the virtual environment:
    -   On *Windows*:
        bash
        .\.venv\Scripts\activate
        
    -   On *macOS/Linux*:
        bash
        source .venv/bin/activate
        

3.  *Install Dependencies*:
    bash
    pip install -r requirements.txt
    

4.  *Run the Web Application*:
    -   If using *Flask*:
        bash
        python app.py
        
    -   If using *Streamlit*:
        bash
        streamlit run app.py
        
    This will start the web application. You can access it on http://localhost:5000 for Flask or the URL Streamlit provides.

## How to Contribute

Feel free to fork this repository, create a pull request, and contribute to the project! Whether it's fixing a bug, improving the model, or suggesting features, your contributions are always welcome. 🤝

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

-   Thanks to the contributors and libraries that made this project possible.
-   Special thanks to the data source and online communities for inspiration.
