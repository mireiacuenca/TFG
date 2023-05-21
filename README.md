# TFG THESIS 👩‍🎓
## Water 🚿 and electricity 🔌 pattern consumption analysis during the Covid-19 pandemic in Barcelona :mask:

### Abstract

Covid-19 pandemic had an impact on our society, changing the way people interact and their habits. Focusing on the city of Barcelona, during 2020, citizens were confined several months, and this had affected to their lifestyles. 🏡 This project aims to analyse how the water and electricity consumption in Barcelona reflect these changes in the daily life of people. <br><br>
For our analysis, we extracted information from Aigües de Barcelona and Open Data from the Ajuntament de Barcelona. This data provided us of knowledge of aggregated water 💧 and electricity consumption, temperature by month and year 🔥, population by district zone and census section, average rent, and Gini index by district zone. With all this information, we processed, cleaned, analysed, and modelled the data, with the goal of extracting highlights about the differences in the consumption during 2019, 2020 and 2021. 🕰️<br><br>
The project is structured in three parts: Processing and Cleaning the data, Data Exploratory and Analysis, and Modelling. For the development of each part, there are some useful tools that we have used, these include Python libraries as seaborn, sklearn and shap.<br><br>
Finally, the research provides a complete view of the effect that Covid-19 had in the consumption. We found that the during and after the pandemic had different behaviour in consumption within industrial, commercial, and domestic sectors. Also, found discrepancies between population and territories within the city. 🙌<br>

### Structure of the project
The structure of the project is divided into three parts: processing and cleaning data, data exploratory and analysis, and modelling.

| Part | Description |
| :---         |     :---:      |
| Part 1: Processing and cleaning data   | Cleaning datasets and processing their data.    |
| Part 2: Data exploratory and analysis     | Analysis of each dataset features.      |
| Part 3: Modelling     | Creating models to predict values.      |

Each part is formed of five blocks depending on the data. Each block has their datasets and from each we want to extract some information and results.
##### - Block 1: Commercial, industrial and domestic datasets
Water consumption analysis in different sectors: commercial, industrial and domestic.
##### - Block 2: Water consumption by activity dataset
Water consumption analysis by activities.
##### - Block 3: Census section datasets
Water consumption and population analysis of each census section.
##### - Block 4: Postal code datasets
Water and electricity consumption analysis.
##### - Block 5: District zone datasets
Water consumption and population analysis by district zone considering the Gini index and the average rent of each district zone.

### Datasets
For the development of the project, we have worked with open data from the Ajuntament de Barcelona and private data from Aigües de Barcelona. Aigües de Barcelona have provided us of water consumption data in Barcelona and surroundings. Thanks to the public open data website of Ajuntament de Barcelona we could cross data of water consumption with population and electricity data of the different areas in Barcelona. 📍 <br>
All the data used is from the city of Barcelona and during the years 2019 (before covid), 2020 (during covid) and 2021 (after covid).<br>

### PART 1: Processing and cleanning datasets 🗂️
The essential part for starting analysing data is processing the datasets and cleaning the data. As we have different datasets, we have decided to separate it in five blocks depending on the area of Barcelona and the available data.<br>
[Code Processing and cleanning datasets](PART_1_PROCESSING_DATASETS_AND_CLEANNING_DATA.ipynb)

### PART 2: Dataset exploratory and analysis 📉
Once we have processed and cleaned all the dataset it is the time for explore all the data and analyse the information that we can extract from them. This section is divided into five blocks as in the processing and cleaning section depending on the type of datasets that we are analysing.<br> 
[Code Dataset exploratory and analysis](PART_2_DATASET_EXPLORATORY_DATA_ANALYSIS.ipynb)

### PART 3: Modelling 📌
This section of the project consists of the data treatment for the usage of models and how to use these models to predict different situations about the evolution of water and electricity consumption.<br>
[Code Modelling](PART_3_MODELLING.ipynb)
