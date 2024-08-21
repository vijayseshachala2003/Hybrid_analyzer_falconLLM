# Data Analyzer with Falcon LLM integration
This project is of hybrid ntaure, we take data from user which is csv files, the analysis part is done by using pandas and matplotlib libraries and finally LLM makes sure to answer all the questions you might have about the data
<h2>CSV Analyzer with LLM Integration</h2>

This project aims to develop a Python-based application that performs statistical analysis on CSV files, generates visualizations, and provides insights using a Large Language Model (LLM).

Key Features:

    Data Import: Reads CSV files into a Pandas DataFrame.
    Statistical Analysis: Calculates essential statistics like mean, median, mode, and correlation.
    Data Visualization: Creates various plots (histograms, scatter plots) to visualize data trends.
    LLM Integration: Utilizes a pre-trained LLM (e.g., Falcon-7b-instruct) to answer questions about the data based on provided statistics and visualizations.

Technologies:

    Python
    Pandas
    NumPy
    Matplotlib
    Transformers
    Hugging Face Transformers
    Falcon 7B instruct 
    

How it works:

    Data Upload: Users can upload a CSV file.
    Data Processing: The script reads the CSV, performs statistical calculations, and generates plots.
    LLM Interaction: Users can ask questions about the data, and the LLM provides informative answers based on the provided data and statistical insights.
