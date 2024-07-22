# Quantium-Data-Analysis-Project


# Task 1: Data preparation and customer analytics

You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.
We need to present a strategic recommendation to Julia that is supported by data which she can then use for the upcoming category review. However, to do so, we need to analyse the data to understand the current purchasing trends and behaviours. The client is particularly interested in customer segments and their chip purchasing behaviour. Consider what metrics would help describe the customers’ purchasing behaviour.  

We have chosen to complete this task in R, however you will also find Python to be a useful tool in this piece of analytics. If you aren’t familiar with R or Python we would recommend searching a few online courses to help get you started. We have also provided an R solution template if you want some assistance in getting through this Task. Whilst its possible to complete the task in Excel you may find the size of the data and the nature of the tasks is such that it is more difficult to complete in Excel.  

To get started, download the resource csv data files below and begin performing high-level data checks such as:

* Creating and interpreting high-level summaries of the data
* Finding outliers and removing these (if applicable)
* Checking data formats and correcting (if applicable)

You will also want to derive extra features such as pack size and brand name from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember, our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

1. LIFESTAGE: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

2. PREMIUM_CUSTOMER: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.

3. Pro analytics Tip: While the data set would not normally be considered large some operations may still take some time to run. 

This is normal and to be expected when dealing with data sets at Quantium. Whilst your analysis is based on the whole data set you may want to try some strategies to try running sample solutions on a smaller subset of data I.e. create a sample solution using some of the data while it uploads.



# Task 2: Experimentation and uplift testing

Julia has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.

We have chosen to complete this task in R, however, you will also find Python to be a useful tool in this piece of analytics. We have also provided an R solution template if you want some assistance in getting through this Task.

To get started, use the QVI_data dataset below or your output from task 1 and consider the monthly sales experience of each store. 

This can be broken down by:

* total sales revenue
* total number of customers
* average number of transactions per customer

Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.

Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.

As we are in the early stages of this analysis Zilinka has asked us to submit our initial findings, so please save your code as a .pdf file and upload it to unlock the example answer.  



# Task 3:Analytics and commercial application

It is targeted specifically at building your ability to recognise commercial, actionable insights from your analysis and displaying it in a clear and concise way for your client, with minimal jargon. At Quantium, our analyst graduates sometimes work as what we like to call “hybrids” (a mix of analyst and consultant duties) so developing your presentation skills early is a huge win!

As both technical tasks 1 and 2 were open ended in terms of insights, this model answer will focus on the layout and the order of your inclusions, including where to include graphs, taglines, written insights and recommendations.

As part of Quantium’s retail analytics team, you have been conducting a range of analysis on transaction and purchase behaviour data to provide key recommendations to your client, the Category Manager of chips, who is putting together their strategic plan. 


With our project coming to an end its time for us to send a report to Julia, based on our analytics from the previous tasks. We want to provide her with insights and recommendations that she can use when developing the strategic plan for the next half year.

As best practice at Quantium, we like to use the “Pyramid Principles” framework when putting together a report for our clients. If you are not already familiar with this framework you can find quick introductions on by searching form them on the internet.

For this report, we need to include data visualisations, key callouts, insights as well as recommendations and/or next steps.

We recommend you use a tool like PowerPoint (or similar) to create your report, we have also provided you a template to help get you started.

One way to create your visualisations (graphs, charts etc) is to save your output files from task 1 & 2 and create generate your charts in Excel. You may find it helpful to create chart templates however that is not essential. We are looking for consistency here – if a series is blue in one chart it needs to remain blue throughout the presentation. Once you have created the charts in your Excel file, paste them into your PowerPoint in the order that suits best.
