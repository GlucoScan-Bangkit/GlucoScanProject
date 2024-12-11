# GlucoScanProject
Welcome to our GlucoScan project! This repository houses a powerful machine learning solution designed to analyze nutrition facts on drink labels. Using image recognition and Optical Character Recognition (OCR), we identifies and extracts critical details — specifically the sugar content — making it easier to stay informed about your drink choices.

# 🌟 Key Features
1. Image Recognition: Detect and locate nutrition fact tables on drink labels.
2. OCR Technology: Extract and interpret text from the detected tables with high accuracy.
3. Focus on Health: Automatically capture the sugar amount to help users make healthier choices.

# ⚙️ How It Works
1. Upload an image of a drink's nutrition facts label.
2. The ML model detects the table containing nutritional details.
3. OCR extracts the relevant data, focusing on the sugar content.
4. Output: The sugar amount in grams is displayed or stored for further use.

# 📂 Repository Structure

Here's what you'll find in this repository:
1. Image_Recognition_+_OCR.ipynb: Interactive Jupyter Notebook for testing and experimenting with the model.
2. image_recognition_+_ocr.py: Python script to run the full pipeline outside of the notebook environment.
3. final_nutrition_model_ML.h5: Our machine learning model used for image recognition and OCR tasks.
4. requirements.txt: A list of dependencies to install for running the project.

# 🚀 How to Get Started
Clone the repository:
git clone https://github.com/GlucoScan-Bangkit/GlucoScanProject.git

cd GlucoScanProject

Install dependencies:
pip install -r requirements.txt

Run the pipeline:
Notebook: Open Image_Recognition_+_OCR.ipynb in Jupyter Notebook to interactively test the system.
Script: Run the pipeline using the Python script: python image_recognition_+_ocr.py

# 📷 Dataset
You can access our dataset from: https://drive.google.com/drive/folders/1Casu1_jepy_A4iI1gde8J5Z9Faz5faW8?usp=drive_link
# 📢 Contributing
We welcome contributions! Feel free to open an issue or submit a pull request to enhance the project.
