This repository contains a machine learning project designed to predict 5G user behavior. It leverages advanced algorithms like Logistic Regression and LightGBM to analyze network data, alongside a web backend infrastructure for potential deployment.

1.Key Features
Data Analysis: Comprehensive preprocessing and visualization using pandas, numpy, and matplotlib.
Machine Learning Models: Implementation of predictive models using scikit-learn (Logistic Regression) and    lightgbm.
Backend Integration: Built upon a Django framework with asynchronous support (aiohttp) for handling API requests.
Utility Tools: Includes QR code generation (qrcode) and environment management (python-dotenv).

2. Tech Stack & Dependencies
The project relies on the following core libraries (see requirements.txt for full list):

Category          |	Libraries
Core Data Science |	pandas, numpy, matplotlib, scikit-learn, lightgbm
Web Framework     |	Django (v2.2.4), dashscope
Async & Network   |	aiohttp, websocket-client, requests
Utilities         |	qrcode, pillow, python-dotenv, rich

3. Installation & Setup
Follow these steps to set up the project environment locally:
3.1 Clone the repository
git clone https://github.com/chu166/5G-User-Prediction.git
cd 5G-User-Prediction

3.2 Create a virtual environment (Recommended)
python -m venv venv

3.3 Activate the Virtual Environment
# Activate on Windows
venv\Scripts\activate
# Activate on macOS/Linux
source venv/bin/activate

3.4 Install dependencies
Install all required packages listed in requirements.txt:
pip install -r requirements.txt

4.Project Structure
5G_User_Pred.ipynb: The main Jupyter Notebook containing data exploration, model training, and evaluation logic.
requirements.txt: A complete list of Python package dependencies.
README.md: Project documentation.

5.Usage
Open 5G_User_Pred.ipynb in Jupyter Notebook or VS Code.
Run the cells sequentially to preprocess data and train the model.
The model outputs prediction probabilities and saves results to a CSV file.

6.Note
This project uses specific versions of libraries (e.g., Django 2.2.4). Please ensure you use the provided requirements.txt to avoid compatibility issues during deployment.
