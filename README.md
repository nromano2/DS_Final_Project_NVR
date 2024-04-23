# DS_Final_Project_NVR  
## Project Name  
Predicting NFL Outcomes Using Machine Learning  

## Exploratory Data Analysis  

### Project Dataset  
The dataset used in this project was a dataset downloaded from Kaggle. The dataset used is the `NFL Team Stats 2002 - Feb. 2023 (ESPN)` dataset on Kaggle from user CVIAXMIWNPTR. The link to this dataset is <a href = "https://www.kaggle.com/datasets/cviaxmiwnptr/nfl-team-stats-20022019-espn">Kaggle Dataset Link</a>.  

### Exploratory Data Analysis  
The Exploratory Data Analysis report is the PDF file named `DS_EDA_NVR.pdf`. This report provides a description, summary statistics, visualizations, and a summary of findings for the dataset. The Exploratory Data Analysis Python code is the Jupyter Notebook named `Exploratory_Data_Analysis.ipynb`. The visualizations created in the `Exploratory_Data_Analysis.ipynb` Jupyter Notebook are stored in the EDA_Visualizations folder. Also the `EDA_Expanded_NFL_Dataset.csv` is a .csv file of the dataset after a few cleaning steps were undertaken in the EDA process.   

### Preliminary Preditive Model  
The `Data_Cleaning_and_Modeling_Notebook.ipynb` file is the file where I cleaned, transformed the `EDA_Expanded_NFL_Dataset.csv` dataset to contain the previous team game data for each game. Futhermore it contains a premliminary predictive KNN classifier model. In evalutating the KNN Classifier model, the `AccuracyScoreNumbersofNeigbhors.jpeg` looks over a range of KNN Classifier models with different number of neighbors and displays the accuracy score of that model. Once the optimal number of neighbors was found the `KNN_TestingDataConfusionMatrix.jpeg` and `KNN_ValidationDataConfusionMatrix.jpeg` files are confusion matrices that display the predictions made along with the true value to visually see the accuracy of the model. The `TeamData_and_TeamAvgData` folder contains the individual team and team averages .csv files.  

## Final Modeling Notebook
The `Final_DataCleaning_Modeling Notebook_NVR.ipynb` file is the file with the final data cleaning and modeling. In this notebook, I added on to the K-Nearest Neighbor Model by adding a GaussianNB and Random Forest Model. Furthermore, I considered other moving average windows by looking at various previous games (between 1 and 21 games). The datasets derived from the various moving average windows is stored in the `Final_Team_AVG` folder.

### Presentation Poster
The `PresentationPoster.pdf` and `PresentationPoster.pptx` files are the presentation poster of this project. The poster includes an abstract, introduction, methods and materials, and results information. This poster was used in the Celebration of Student Research.