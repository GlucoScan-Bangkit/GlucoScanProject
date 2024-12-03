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
Image_Recognition_+_OCR.ipynb: Interactive Jupyter Notebook for testing and experimenting with the model.
image_recognition_+_ocr.py: Python script to run the full pipeline outside of the notebook environment.
final_nutrition_model_ML.h5: Our machine learning model used for image recognition and OCR tasks.
requirements.txt: A list of dependencies to install for running the project.

# 🚀 How to Get Started
Clone the repository:
git clone https://github.com/your-username/drink-nutrition-scanner.git
cd drink-nutrition-scanner

Install dependencies:
pip install -r requirements.txt

Run the pipeline:
Notebook: Open Image_Recognition_+_OCR.ipynb in Jupyter Notebook to interactively test the system.
Script: Run the pipeline using the Python script: python image_recognition_+_ocr.py

# 📢 Contributing
We welcome contributions! Feel free to open an issue or submit a pull request to enhance the project.
