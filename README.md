# **Laptop Price Prediction Project**

## **Overview**

This project is a machine learning model for predicting the prices of laptops based on various features and specifications. It provides a simple user interface to input the laptop's specifications and get an estimated price.

## **StreamLit Application Link**

This project is deployed on Streamlit Application, which can be accessed from [here](https://kanishkmunot-laptop-price-app-pwspor.streamlit.app/).

## **Table of Contents**

- [**Installation**](#installation)
- [**Usage**](#usage)
- [**Project Structure**](#project-structure)
- [**Dependencies**](#dependencies)
- [**Contributing**](#contributing)
- [**License**](#license)

## **Installation**

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```shell
   git clone https://github.com/kanishkmunot/Laptop_Price.git
   ```
   ## **Navigate to Project Directory**

Navigate to the project directory:

```shell
cd Laptop_Price
```

## **Installation**

To run this project locally, follow these steps:

 **Install Project Dependencies**:

   ```shell
   pip install -r requirements.txt
   ```
 **Run the Streamlit App**:

   ```shell
   streamlit run app.py
   ```

The app should now be running locally, and you can access it by opening a web browser and navigating to http://localhost:8501.

## **Usage**

1. Open the web browser and go to the app's URL.

2. Input the laptop's specifications, such as processor type, RAM, storage, etc.

3. Click the "Predict" button to get the estimated price.

## **Project Structure**

The project structure is organized as follows:

- **app.py**: The Streamlit application for user interaction.
- **model.py**: The machine learning model for laptop price prediction.
- **data.csv**: Dataset used for training the model.
- **requirements.txt**: List of project dependencies.

## **Dependencies**

This project uses the following major dependencies:

- **Streamlit**: For building and running the web application.
- **Scikit-learn**: For machine learning and data preprocessing.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization.

For a complete list of dependencies, please refer to the `requirements.txt` file.

## **Contributing**

Contributions to this project are welcome. Feel free to open issues, create pull requests, or suggest improvements. Please follow the Contributing Guidelines for details.

## **License**

This project is licensed under the MIT License.
