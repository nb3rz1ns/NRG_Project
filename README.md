# NRG_Project
The public repository for Introduction to Data science Project - A06 Impact of Covid-19 on energy consumption in Baltic countries
Authors: Normunds Berzins, Anna Rutmane

This project is a part of Introduction to Data science course. The goal of this project is to visualize and analyse the impact of COVID-19 on Energy Consumption. It would be both a great insight on how impactful the pandemic was as well as allow for more preparedness in similar future events. In case of successful model for energy consumption prediction, it could be, in theory, used to predict future energy demands.

The repository contains a PDF containing descriptive data about countermeasure events that were placed during the COVID pandemic in the Baltic countries, 4 datasets (3 energy consumption datasets, one for each Baltic country for time periods 2018 to end of 2022, and a COVID-19 global dataset as to data reported to WHO) in .csv format and a ipynb file that contains most of the code that was done for this project. I say "most" because a lot of failed models were deleted to decrease strain on repetition of the more "succesful" parts.
The repository also contains the report file on what was the planned course of action for this project.

To repeat our results, simply clone the repository and run the code in the ipynb file. It should have no issues running, however it may take time (some code for failed models is entered in markdown format, but is not relevant to our results). Keep in mind that hyperparameter tuning takes time and we did not save the parameters in most cases (except the last SARIMA model, they are already saved in code), therefore it may be a lengthy process. Some errors may be caused by a lack of a library on your device. Follow ChatGPT instructions to install the missing libraries.

The code in ipynb file cleans the COVID data and the consumption data is already preprocessed by the provider MSc Neha Sharma. Some adjustments are made to the names but the original files contain following important columns:
- WHO-COVID-19-global-data.csv: Country, Date and New_cases
- estonia2018_2022.csv, Lithunia2018_2022.csv and latvia2018_2022.csv: Some column containing the date and time (different names in each csv file) and energy consumption in Megawatts
