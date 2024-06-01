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






