### Repository Contents

The files in this repository are in support of the report submitted for Assignment 2 for classifying two binary classes based on the ANU Poll data from 2019 relating to the role of the university and gambling.

The original dataset can be requested from: https://dataverse.ada.edu.au/dataset.xhtml?persistentId=doi:10.26193/GOVGBB 
1) **baseline_prep.ipynb**: this is a Jupyter notebook to apply additional data cleaning steps to the output of the data cleaning applied in Excel
2) **association.ipynb**: this is a Jupyter notebook with a loop to create the 4 association rule csv files (which are also located in the repository):
   * association_rules_is_gambler_0_lift.csv
   * association_rules_is_gambler_1_lift.csv
   * association_rules_pgsi_binary_0_lift.csv
   * association_rules_pgsi_binary_1_lift.csv
3) **is_gambler_model.ipynb**: this is a Jupyter notebook that shows all the steps undertaken to explore, model and visualise the dataset to classify the is_gambler class.  Note: not all cells and output has been included in the report.
4) **prob_gambler_model.ipynb**: this is a Jupyter notebook that shows all the steps undertaken to explore, model and visualise the dataset to classify the pgsi_binary class.  Note: not all cells and output has been included in the report.