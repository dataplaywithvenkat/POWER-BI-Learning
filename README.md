# POWER-BI-Learning
[Microsoft Power BI Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/microsoft-power-bi-data-analyst)

# Exercise: Dataset

### Introduction

In previous lessons, you explored the importance of data for businesses and organizations, and in this context, you evaluated topics such as defining data, extracting meaningful information from data, deriving insights from this information, and using those insights in business decision-making. You also learned about the components of Microsoft Power BI and started to familiarize yourself with the software and its workflow.

In this exercise, by examining a case study dataset in detail, you will become more familiar with the data, and evaluate whether the data you have is sufficient to achieve a specific defined business objective. 

At the end of this exercise, you should feel more confident in understanding, interpreting, and aligning data with business needs.

### Case study
Adventure Works is a large, multinational manufacturing company that produces and distributes bicycles and accessories to global markets. Renee, an Adventure Works executive, has tasked you with tracking the price increase on a supplier basis from the past to the present for each product the company purchases from suppliers and detecting any unusual price situations, if any.

She shared a file with you, a Microsoft Excel workbook called Adventure Works Inventory.xlsx. Your task is to examine the Products worksheet of the workbook and decide whether the Excel data is compatible with the required business needs.

### Instructions

**Step 1**: Download and review the data to understand the context
1. Download and open the Microsoft Excel workbook Adventure Works Inventory.xlsx. The workbook consists of a single worksheet named Products.
2. Review the data and familiarize yourself with the contents.

**Step 2: Evaluate the adequacy of the data**
First, you need to evaluate if the data you have is adequate for your assigned task. 

The request from Renee can be summarized as monitoring prices by product and supplier from the past to the present. 

You will start by examining the data you have been supplied with for this task. Since your assigned task is to analyze the price changes of products from past to present, you must identify the relevant fields accordingly. The existing dataset includes fields such as **Category, Date Entered, Product Name, Supplier, Unit Price, Units In Stock, Units On Order, Reorder Level, and Discontinued.**

1. In this dataset, locate the required fields for this business need: **DateEntered, ProductName, Supplier, and UnitPrice.**

2. Sort the data based on the **Date Entered** field for each **Product Name**. Examine the **Unit Price** values and take note of the rows that are significantly above or below the average, if any, to be reported in the analysis.

3. Take into account the **Supplier** field in sorting or comparisons. As different suppliers may have different pricing policies for the same product, it would be more accurate to examine any anomalies on a supplier basis, if any. 

Tip: When you examine the list sorted by products, you may notice that the same supplier is generally used for each product. However, always consider the possibility of examining the data by supplier for this and other similar datasets.

4. Recognize that other fields, namely **Category, Units In Stock, Units On Order, Reorder Level, and Discontinued**, are detail fields that are not directly relevant to your current assigned task. They will continue to be included in the list but will not affect our analysis.

In this step, you analyzed in detail how the data supplied to you in the Adventure Works Inventory.xlsx file corresponds to the given business needs.

### Conclusion
By completing this exercise, you should have gained a deeper understanding of the data and learned how to find the relevance between the data and the business need. This exercise has equipped you with the knowledge necessary to effectively match data with business needs and identify the tasks that need to be completed to meet these business requirements.

# Exemplar: Dataset

### Introduction
In the exercise Assessing a data set, you should have gained a deeper understanding of the data and learned how to find the relevance between the data and a business need. 

This reading is a detailed walkthrough of that process and contains screenshots from key parts of the exercise. Use this reading to compare the outcomes of each step with your own work. 

### Excel User Interface
In this course, we use the Microsoft 365 Desktop version of Excel. Microsoft 365 releases updates on a monthly basis, incorporating new features. You might experience changes in the Excel Desktop User Interface (UI) that have taken place after the development of this training content. As a result, the screenshots in the videos, readings, or exercises might not align exactly with how you experience the UI. However, please note that these changes do not impact the functionalities of the UI. Hence, you will still be able to perform all the steps shown in that video, reading, or exercise.

Step 1: Download and review the data to understand the context
1. You downloaded and opened the Microsoft Excel workbook Adventure Works Inventory.xlsx. The workbook consisted of a single worksheet named Products. 

Microsoft Excel workbook Adventure Works Inventory.xlsx with the worksheet named Products
Step 2: Evaluate the adequacy of the data
Renee's task can be summarized as monitoring prices by product and supplier from the past to the present. To start, you examined the data in the Excel workbook given to you by Renee. Since your assigned task is to analyze the price changes of products from past to present, you needed to identify the fields relevant to this task. The existing dataset included fields such as Category, Date Entered, Product Name, Supplier, Unit Price, Units In Stock, Units On Order, Reorder Level, and Discontinued.

1. In this dataset, the required fields for this business need were Date Entered, Product Name, Supplier, and Unit Price. 

You located the column Product Name and examined the rows. The variety of products in the rows affects the sorting and analysis.

The Products column of the Products worksheet 
You examined the Unit Price values by sorting the data based on the Date Entered field for each Product Name. You noted the rows that were significantly above or below the average. For instance, rows 2 to 9 might be reported in your analysis. 

You located the column Date Entered and examined the rows. Date Entered was one of the significant columns in your analysis.

The Date Entered column on the Products worksheet
You located the column Supplier and examined the rows. Supplier was also one of the significant columns in your analysis.

The Supplier column on the Products worksheet
Finally, you located the column Unit Price and examine the rows. In your task, part of the task was to find any unusual values in Unit Price.

The Unit Price column on the Products worksheet
You also considered the Supplier field in sorting or comparisons. As different suppliers may have different pricing policies for the same product, it would be wise to examine any anomalies, if any, on a supplier basis. In this list by products, the same supplier is generally used for each product. However, it is important to consider the possibility of examining the data by supplier, as well as other methods. That data examination by supplier might become important if the data was updated in this dataset or you were tasked with examining another similar dataset.

You opened PowerBI Desktop and navigated to the Home tab.  

In the Data group you selected Excel Data, and loaded the Microsoft Excel workbook Adventure Works Inventory.xlsx, which you downloaded in step 1. You need to click on transform data when opening an Excel file in Power BI to open the Power Query Editor view.

2. You selected the Product Name column and inside the Sort group selected AZ to sort the data by Product Name.

The Sort ascending choice in the Sort group of the Home tab.
You selected the Date Entered column and inside the Sort group selected AZ to sort the data by Product Name and Date Entered.

3. You selected the Supplier column and inside the Sort group selected AZ to sort the data by Product Name, Date Entered, and Supplier.

An A to Z sort of the data by Product Name, Date Entered, and Supplier.
You were then able to examine the price changes of a product by taking the supplier and date entered columns into consideration.

4. The other fields, namely Category, Units In Stock, Units On Order, Reorder Level, and Discontinued, were detail fields that were not directly relevant to our current business needs. They continued to be included in the dataset but did not affect your analysis.

Completed example
Compare your work with the finished version of the exercise.

The Products dataset with the finished version of the exercise 
Conclusion
This exercise explored whether the Microsoft Excel data you were given could meet the given business requirement. In this case, the business requirement was the task set for you by Renee: to analyze the price changes of products from past to present. 

In this context, examining the changes in the Price field based on the Product Name, Date Entered, and Supplier fields in the Excel data met the current business requirement, and you were able to prepare the relevant fields for the next step of the analysis process.








