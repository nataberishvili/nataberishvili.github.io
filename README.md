# Data Science Portfolio by Nata Berishvili

This portfolio is a collection of notebooks which I created for data analysis and machine learning projects.

### Automated & Interactive reporting dashboards (Rmarkdown & Flexdashboard Shiny)

Implementing automated reporting infrastructure has enormous potential and benefits. It can be applied to all parts of a business, from marketing and sales to fulfillment and customer services. Automated reports will significantly decrease the timeline, combine data from different resources and create reports within minutes.

Some advantages association with automated reporting approach:

**Increased productivity  
Easy shareable  
Decreased expenses  
Greater control and consistency  
The Decreased risk associated with human/manual error  
Accurate and reliable results** 

 [Shiny app Group project DS consulting](https://nataberishvili.shinyapps.io/dsconsulting/#section-google-trends).

![Screenshot (365)](https://user-images.githubusercontent.com/50959111/89877474-2755e100-db8e-11ea-8a98-e0315edf21cd.png)![Screenshot (367)](https://user-images.githubusercontent.com/50959111/89877488-2a50d180-db8e-11ea-81d9-40e28913aefb.png)

https://nataberishvili.shinyapps.io/dsconsulting/#section-sentiment-analysis 

### Happiness Around the World - Data Visualization with R


The data was scraped from the [wikipedia](https://en.wikipedia.org/wiki/World_Happiness_Report).
The World Happiness Report is an annual publication of the United Nations Sustainable Development Solutions Network. Happiness is explained by 6 factors. As per the 2019 Happiness Index, Finland is the happiest country in the world. 
The interactive version of map (Plotly) can be found [here](https://plot.ly/~nataberishvili/9/?fbclid=IwAR1_SeAYlIe_Kc2gp-AlTnV7o7blV77eEiXuRSK81Ajs72JDrKVyxuMvLqI#/.embed).

![hap-nat](https://user-images.githubusercontent.com/50959111/73878371-6c3c3c00-4828-11ea-8514-b867b21cad68.png)


![untitled](https://user-images.githubusercontent.com/50959111/76675545-d5823e00-6590-11ea-8dfc-ad4b8e35a98d.png)

For more details code can be found here [GitHub Flavored Markdown](https://github.com/nataberishvili/happiness_data_visualization_r).




### Exploratory Data Analysis - Medicare


For this project I use Medicare Provider Utilization and Payment Data for more than 3,000 U.S. hospitals that receive Medicare paments. I explore and visualize data to make comparisons between the individual hospital-level charges and payments within local markets, and nationwide. 
Questions I want to answer 

- Which Diagnostic Related Groups cost Medicare the most?
- What are the most commong hospital discharges? 
- What is the trend in last 3 years?
- Which States and Hospitals charge the most? etc.


For more details code can be found here [GitHub Flavored Markdown](https://github.com/nataberishvili/Exploratory_data_analysis_medicare).


### Fast transition between dplyr and data.table R  

In this post I compare the syntax of R's two most powerful data manipulation libraries: dplyr and data.table. I am not here to advocate one package or the other. However, while working on a project with unusually large datasets, my preferred package became data.table, for speed and memory efficiency. I took a legacy project in dplyr and recreated it in data.table. I will show the comparison of syntax and how to translate from dplyr to data.table or vice versa.   

Data.table uses shorter syntax than dplyr but is often more nuanced and complex. dplyr use a pipe operator, which is more intuitive for beginners to read and debug. Moreover, many other libraries use pipe operators, such as ggplot2 and tidyr. While data.table and dplyr are both widely used in the R community, dplyr is used more broadly and thus offers more opportunities for collaboration.   
Are memory and speed important? when building complex reports and dashboards, and especially when working with very large datasets, data.table has distinct advantages.
It is up to you which library to use for your analysis!

For more details code can be found here [Github link](https://github.com/nataberishvili/dplyr-datatable).

### Predicting Loan Default - Binary Classification

For this project I specifically focus less on feature engineering and use a small dataset. The main purpose is to build supervised machine learning models with h2o and experiment with hyperparameters.
For more details code can be found here [GitHub Flavored Markdown](https://github.com/nataberishvili/h2o_rf_gbm_stacked_ensambles_loan_default/blob/master/h2o-rf-gbm-stacked.ipynb).

### Interactive Maps with R leaflet

Interactive data visualization enhances exploratory data analysis and is a great way to engage with both technical and non-technical audiences. R's leaflet package is a powerful tool to create visually compelling interactive maps. In this post I will show how to create a choropleth map with leaflet. Choropleth maps show the level of variability within a region, using color.  


I will build a choropleth map using data for the 2019 Novel Coronavirus published by Johns Hopkins University Center for Systems Science and Engineering. To make it easy to follow through the steps, we will work with state-level data.

![Recording-3](https://user-images.githubusercontent.com/50959111/94729665-03ae4c00-0330-11eb-8ace-69ed10a68c04.gif)

### Explain Loan Probability of Default With SHAP Values

Some models are easy to interpret such as linear / logistic regression (weight on each feature, knowing the exact contribution and negative and positive interaction), single decision trees, some models are harder to interpret such as Ensemble models - it is hard to understand the role of each feature, it comes with "feature importance" but does not tell if feature affects decision positively or negatively

![nataaa](https://user-images.githubusercontent.com/50959111/74569704-07c85d80-4f49-11ea-8d6d-4f3c9fb3a999.png)

[GitHub Flavored Markdown](https://github.com/nataberishvili/explain_loan_probabiity_of_default/blob/master/SHAP_VALUES_NATA.ipynb) 

