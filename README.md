# SEC-101-Assessment-LaptopData

Welcome to the Laptop Price Prediction Program, a project by Ratanapara Choorat (rchoora@cmkl.ac.th). This program uses the "Uncleaned Laptop Price dataset" from Kaggle to predict the market price of laptops based on their hardware specifications. The project features a comprehensive data processing workflow that cleans and prepares the raw, web-scraped data for machine learning. Key steps include handling missing values, managing outliers using winsorization, parsing complex columns (such as CPU, Memory, and Screen Resolution) into distinct numerical features, and converting categorical data into a machine-readable format using one-hot encoding. A **Random Forest Regression model was chosen to accurately capture the complex relationships between a laptop's features and its price**. The model is trained on a split dataset, and its performance is rigorously evaluated using **R-squared (R2)** and **Mean Absolute Error (MAE)** to ensure its predictions are both reliable and precise.



Within the file, I have provided both the program in Jupyter Notebook and the .csv file for the project that I use. I also have markdown in the notebook detailing each process to create such a program.
