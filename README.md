# SEC-101-Assessment-LaptopData

Link to dataset: https://www.kaggle.com/datasets/ehtishamsadiq/uncleaned-laptop-price-dataset

Welcome to the Laptop Price Prediction Program, a project by Ratanapara Choorat (rchoora@cmkl.ac.th). This program uses the "Uncleaned Laptop Price dataset" from Kaggle to predict the market price of laptops based on their hardware specifications. The project features a data processing workflow that preprocesses the raw data, including web-scraped data, for machine learning to predict prices based on price-to-performance. Steps include handling missing values, managing outliers using the winsorization process, parsing down complexity (such as CPU, Memory, and Screen Resolution Column) into numerical features, and converting categorical data into a readable format for an AI Model with methods of one-hot encoding. A **Random Forest Regression** model was selected to accurately capture the complex relationships between a laptop's features/specifications and its price. The model is trained by splitting the dataset, training, and evaluating the model's performance using **R-squared (R2)** and **Mean Absolute Error (MAE)** metrics to ensure its predictions are reliable, precise, and applicable in real-world usage.



Within the file, I have provided both the program in Jupyter Notebook and the .csv file containing the data I use for the project. I also have markdown in the notebook detailing each process to create such a program.
