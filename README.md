# Technical case Fairly made

Exploring the idea of using an ML model to predict the environmental impact of clothes during product design.

In this repo we performed:
- exploratory data analysis
  - column types, unique values
  - missing data, duplicated data
  - distribution of label data
  - impact per category (country, product type, material, nb_components)
- model training for climate change values (kg CO2)
  - Prepare the data
  - Select model metric
  - Train baseline models (10 basic models selected)
  - Select best model
  - Analyse predictions


## Instructions

1. Clone the repo
2. Create the conda environment: 
    ```
    conda env create -f environment.yml -n <env_name>
    ```
3. Activate conda environement: 
   ```
   conda activate <env_name>
   ```
4. Run pip install:
   ```
   pip install -r requirements.txt
   ```
5. Add the csv file containing the data to the data folder
6. Run the notebooks
   ```
   jupyter notebook
   ```