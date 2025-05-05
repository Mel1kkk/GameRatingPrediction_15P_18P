# Git Repository Link
https://github.com/Mel1kkk/GameRatingPrediction_15P_18P

# Metacritic Rating Prediction for games

# Introduction
This project is part of the INF395 course. We built a machine learning system that predicts **Metacritic game ratings (Metascores)** using structured metadata about video games. The system includes scraping real-world review data, training ML models and building a simple interface with Gradio to compare predicted vs actual scores.

# Problem Statement
Predicting game review scores based on metadata is a challenging task that usually requires manual browsing and subjective evaluation. There is no fast or scalable way to estimate how a game might be received based on its features before release. This project aims to automate the prediction of Metacritic ratings using machine learning, allowing users to analyze score trends, make early assessments, and better understand the relationship between game features and critical reception.

# Objectives
The objective of this project is to predict Metacritic game review scores using machine learning models based on game metadata and provide an interactive interface for visualization.

# 🛠️ Technology Stack
- Python
- BeautifulSoup (bs4)
- Scikit-learn
- Pandas / NumPy
- Gradio

# Installation Instructions
You can either clone this repository or download the ZIP file and extract it

Before running any code, make sure the following steps are completed:

1. Have Python Installed
 
2. Use Jupyter Notebook or Visual Studio Code
  You can open the .ipynb file using Jupyter Notebook or open the folder in VS Code and install the Jupyter extension.

3. Install Required Libraries  
You need to install some Python packages. Open a terminal or command prompt and run:
 pip install requests  
 pip install gradio  
 pip install beautifulsoup4  
 pip install pandas  
 pip install numpy  
 pip install scikit-learn 

4. Open the Jupyter Notebook  
Open the notebook file (e.g., main.ipynb) using Jupyter or VS Code.  
Run each cell by pressing Shift + Enter or by clicking the "Run" button.

---

⚠️ Notes Before Running

- If you're running the data scraping part:
  - Please be patient — it may take a long time to scrape data from Metacritic and rawg.io.
  - Do not close the notebook or interrupt the code while it's running.
  - A stable internet connection is required.

- If you're running the ML models:
  - Make sure the .csv file (e.g., the dataset) is in the same folder as the notebook file.
  - Otherwise, the file won’t be found and the code will not work.
  - All ML code depends on scikit-learn, so make sure it is properly installed.


---

# Usage Guide
1. Open the project using Jupyter Notebook or Visual Studio Code with the Jupyter extension.
2. Make sure all required Python packages are already installed on your system.
3. Launch the notebook file included in the project.
4. Go through each code cell by selecting it and pressing Shift + Enter or by clicking the "Run" button.
5. If you're running the data scraping section or ml parts, be patient — it may take a while to collect data from Metacritic and RAWG.io or to start ML machine.
6. If you're using the machine learning part, ensure that the dataset CSV file is placed in the same folder as the notebook so it loads correctly.
7. When running the Gradio section, a web link will appear that opens the prediction interface in your browser or you can keep using the notebook.
8. Use the Gradio interface to select game metadata and compare predicted scores with real scores.

# Testing
There is no formal test script, but you can verify the code correctness by:
- Running all cells without errors
- Checking the predicted vs actual values in output
- Making sure the Gradio app launches and works as expected

# References
* BS4 tutorial video: **\[https://www.youtube.com/watch?v=0ws5tsRBgL8]** 
* Metacritic website – for review score data
* RAWG.io website – for additional game data
* Libraries used:
  * [BeautifulSoup]
  * [Scikit-learn]
  * [Gradio]
  * [Pandas]
  * [NumPy]
  * [Requests]

## Team Members

- **Berikov Miras**, 220103187, 0-P  
- **Bereket Izturganov**, 220103207, 0-P  
- **Davletkali Adilet**, 220103113, 0-P  
- **Amanbekov Farkhat**, 220103134, 0-P  
- **Meirzhan Anarbekuly**, 220103307, 0-P

- **Berikov Miras**, 220103187, 18-P
- **Bereket Izturganov**, 220103207, 15-P
- **Davletkali Adilet**, 220103113, 15-P
- **Amanbekov Farkhat**, 220103134, 15-P
- **Meirzhan Anarbekuly**, 220103307, 15-P

