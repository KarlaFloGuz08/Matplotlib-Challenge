# Matplotlib-Challenge

## Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

### Prepare the data

![image](https://github.com/user-attachments/assets/37a2e799-3267-480d-bebd-4c250f2f76ec)


### Generate summary statistics

![image](https://github.com/user-attachments/assets/4336f8f0-f40d-435f-9f2f-444a5135348b)


### Create bar charts and pie charts


![image](https://github.com/user-attachments/assets/63d3e6da-fa17-44d7-820b-7eb887ae232e)


![image](https://github.com/user-attachments/assets/8be5579f-c69c-42d3-b08e-369f49af4fbe)


### Calculate quartiles, find outliers, and create a box plot


![image](https://github.com/user-attachments/assets/39652e26-990e-42f4-8744-606d2c22a44a)


![image](https://github.com/user-attachments/assets/610795c6-09ce-4c3b-85aa-662a050e7895)


### Create a line plot and a scatter plot


![image](https://github.com/user-attachments/assets/a7688eef-48e7-4e28-9952-d565c97fe723)



![image](https://github.com/user-attachments/assets/5bfd5e75-8c2e-4fd3-a16a-ee0ba17a4758)


### Calculate correlation and regression

![image](https://github.com/user-attachments/assets/61d3e88b-8bb0-432b-b853-8d2057cfbea9)


## Analysis

-The higher number of rows for Capomulin and Ramicane on the bar graph indicates that more mice were treated with these regimens or had more recorded time points during the study. The pie chart mice by gender showed that the population is almost 50% female and 50% male.

-The line plot shows an overall decrease in the average tumor volume as the days increase with Capomulin treatment of mouse l509. However, there is a slight increase in some days.

-The correlation coefficient is 0.84, which means a strong correlation. This means there is a reliable and consistent pattern in how these two variables relate. This correlation is intuitive since the tumor has more space to develop if the mouse is bigger. However, we should note that correlation does not imply causation; hence, we should further explore the underlying mechanisms of the relationship between mouse weight and tumor volume to draw more conclusions.

-The R-squared is relatively high, indicating that the model explains a large portion of the variability in tumor volume based on mouse weight.

Appropriate statistical tests could be conducted to compare the efficacy of Capomulin against other treatments to improve the analysis.

