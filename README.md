# project_1
Anitha, Kent, Misty, Sujatha, Zach

## Homebuyers Guide to the Texas Market!!! Where should you end up? <br>

**-- Project Description: --** As part of this activity, “hotspots” in Texas will be determined based on housing prices, COVID surveillance and public safety.
**-- Main Questions: --**
* Housing Price: Where are housing prices rising the most in the past 6 years? Where have prices fallen? AKA where do you want to stay away from in your home investment? 
* COVID surveillance: Does the place have higher COVID transmission rate?
* Public safety: Is the place safe to live in? What is the crime ranking?

**-- Data Analysis --** Data set for each question was identified, cleaned and a detailed summary analysis was performed. 

**-- Livability Score --** Based on the Data Analysis, Livability score from 1 to 5 with 1 being lowest and 5 being highest(best) is determined for each of these categories and overall livability grade based on the mean value of these scores is determined for each county

**-- A visualization map --** created for Texas by each county with a hover that display overall livability Grade, County Name, Avg housing price and Percent Change, Covid (Percent Change), Temperature (Avg Temp), Safety (precent Change)

### Datasets being used:
  * Zillow data set - for housing price
  * Texas Open Data Portal and dshs data - for Safety and covid measures

Who’s doing what:<br>

Zach & Kent: Housing Price<br>
Sujatha: COVID and Temperature <br>
Anitha: Public safety<br>

---

**-- Content in Main Branch: --**
* Analysis Folder - Contains analysis source files <br>
    - COVID_Analysis.ipynb <br>
    - Safety_Analysis_final.ipynb<br>
    - housing_prices_bycounty.ipynb <br>
* Resources Folder - Contains source datafiles<br>
  * Source Data file for COVID Analysis: <br>
    - Texas_COVID-19_Cumulative_Confirmed_Cases_by_County<br>
  * Source Data file for SAFTEY Analysis: <br>
    - Texas_Department_of_Criminal_Justice_Receives_FY_2019 <br>
    - Texas_Department_of_Criminal_Justice_Releases_FY_2020<br>
  * Source Data file for Housing Analysis :<br>
    - zillow_data.csv <br>
  * List of counties - Texas_Counties.xlsx
  * tufts-txcounties10-shapefile folder contains shape file for Texas map
* Output Folder - Contains livability score csv extract from each of the analysis
  * LIndexForCOVID - Livability score output from Covid Analysis
  * safety_analysis - Livability score output from Safety Analysis
  * housing_price_score - Livability score output from Housing Analysis
  * housing_summary_stats.jpg - Plot Image output from Housing Analysis
  * housing_value_5_change_boxplot.jpg - Plot Image output from Housing Analysis
* HomeBuyersGuide.ipynb - Final Jupyter Source File which contains Merged data, livability grade by county and Texas map visualization
* Project1_Module7_Slide_Deck.pdf Slide deck - Contains detailed presentation about this project

**-- To execute Source Files: --**
* Jupyter source files under Analysis folder should be executed first. 
* Ensure LIndexForCOVID.csv, safety_analysis.csv and housing_price_score.csv is generated from those execution.
* Open HomeBuyersGuide.ipynb and execute the source file to view the Texas map with all counties displayed by its livability grade

**-- Things to ensure before execution: --**
* Ensure correct Kernel is selected and all required python/pandas packages are installed.
* Ensure required dataset is under Resource folder when executing Jupyter source files from Analysis folder.
* Ensure required source files are present under output folder when executing HomeBuyersGuide.ipynb  
* Click Run All or Run individual cell code in sequence it is written. Running the code block in between might throw error as the variables used in that code block might be defined in the prior code block. Hence recommended to Run All to ensure it is run in sequence without any error.