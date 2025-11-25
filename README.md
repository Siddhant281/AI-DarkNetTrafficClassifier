# Darknet Traffic Classification using AI

## Project Description
This project utilizes a **Random Forest Classifier** (and XGBoost) to detect and categorize darknet traffic (VPN and Tor) using the **CIC-Darknet2020** dataset. The model analyzes network flow statistics to distinguish between benign and darknet traffic with high accuracy.

## Key Features
* **Accuracy:** Achieved ~97% accuracy on test data.
* **Preprocessing:** Includes robust handling of Infinity/NaN values in network flows.
* **Model:** Uses Random Forest / XGBoost with balanced class weights.

## How to Run This Project
You can view the code and results directly in GitHub. To run the code yourself, click the button below:

<a href="https://colab.research.google.com/github/Siddhant-281/AI-DarkNetWebsiteDetector/blob/main/TA_2_250103002022.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### Prerequisites
1. Click the "Open in Colab" button above.
2. Upload the `Darknet.csv` file (found in this repository) to the Colab session files.
3. Run all cells.

## Dataset
* **Source:** CIC-Darknet2020
* **File:** `Darknet.csv`
