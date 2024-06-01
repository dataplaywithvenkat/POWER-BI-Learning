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

### Completed example
Compare your work with the finished version of the exercise.

The Products dataset with the finished version of the exercise 

### Conclusion
This exercise explored whether the Microsoft Excel data you were given could meet the given business requirement. In this case, the business requirement was the task set for you by Renee: to analyze the price changes of products from past to present. 

In this context, examining the changes in the Price field based on the Product Name, Date Entered, and Supplier fields in the Excel data met the current business requirement, and you were able to prepare the relevant fields for the next step of the analysis process.


# Exercise: Data storage and management

### Introduction
Previously, you learned about planning for data storage and management. In this exercise, you’ll evaluate storage solutions for different data sources and formats using a case study about Adventure Works. You’ll also learn the differences between structured and unstructured data, as well as on-premises, cloud-based, and hybrid storage. 

### Case study
Adio, the data analyst at Adventure Works, states that the current data storage and management systems are outdated and unable to handle the increasing data volume from sources like sales, manufacturing, and social media. This affects the data analytics team’s ability to analyze and use this information to improve departmental performance. Adio asks you to review the different data sources and select appropriate storage solutions.

### Data types
Adventure Works collects and stores structured and unstructured data. Differentiating between structured and unstructured data is essential for choosing an appropriate storage solution, as some systems are more suitable for specific data types. Let’s begin by defining these terms.

Structured data: Structured data is organized in a specific format making it easily searchable and analyzable. It includes data types that can be neatly arranged in rows and columns, like numbers, dates, and text strings. Examples include sales transactions, customer information, and inventory levels.

Unstructured data: Unstructured data is not organized in a predefined format and is harder to analyze and manage. It includes data types that do not fit neatly into rows and columns, such as images, videos, and audio files. Examples of unstructured data include customer reviews, social media posts and engagements, and multimedia content.

### Storage solutions 
Now that you understand structured and unstructured data, let's explore the available storage solutions for Adventure Works and evaluate their advantages and disadvantages.

On-premises storage: On-premises storage involves storing data on physical hardware, such as storage devices, within the company's premises. It’s suitable for businesses with strict security and compliance needs, requiring full control over their data and infrastructure, or storing sensitive or core operational data. On-premises storage can be more expensive, due to the costs involved in purchasing, managing, and maintaining the hardware and software infrastructure.

Cloud-based storage: With cloud-based storage, you store data on remote servers managed by a third-party provider. It offers convenient access and management from anywhere through the Internet. Cloud-based storage is suitable for businesses that need scalability, to reduce IT infrastructure management or to store less sensitive or more collaborative data.

Hybrid storage: Hybrid storage combines on-premises and cloud-based storage solutions. Companies can store sensitive or mission-critical data on-premises while using cloud storage for less sensitive or more collaborative data. Hybrid storage offers the flexibility and scalability of cloud-based storage, while still allowing for control over sensitive information. It optimizes storage by storing different types of data in the most suitable environment.

### Data sources
Adventure Works’ current Extract, Transform, Load (ETL) process involves extracting data from sources, including sales, manufacturing, financials, human resources, market research, and social media. The data analytics team transforms the data by cleaning, aggregating, and formatting it as required. The processed data is then loaded into Microsoft Power BI for analysis. The data sources used include:

Sales data: Adventure Works collects sales data, including customer information and purchase history. This data is sensitive and structured, crucial for business operations and used to analyze customer behavior, product performance, and sales trends. The storage solution needs to allow for scalability due to growth in sales and collaboration between sales, marketing, and customer service teams. 

Manufacturing data: Adventure Works generates data through manufacturing processes, including production schedules, inventory levels, and quality control metrics. This sensitive, structured data is used to optimize manufacturing operations and supply chain management. Storage needs include scalability to handle production increases, and collaboration among manufacturing teams. 

Financial data: Adventure Works maintains structured financial data, like revenue, expenses, and profit margins for budgeting, forecasting, and monitoring financial health. As this data is highly sensitive, it needs strict access controls. Storage needs also include some scalability for growing financial records. 

Market research data: Adventure Works conducts market research to understand customer needs, preferences, and market trends. This data, from sources like surveys, focus groups, and competitor analysis, is structured and unstructured. Marketing, sales and product development teams share and use this data collaboratively. Scalability is required to accommodate growing market research efforts.

Social media and online reviews data: Adventure Works monitors social media platforms and online review sites to gather customer and public feedback and opinions. This generates high volumes of unstructured data with high scalability needs. This data provides insights into brand and customer perceptions and areas for growth and improvement. 

### Instructions
Create a new Word document called Data storage and management. In this document, answer the questions below to complete the exercise.

For each data source, list the data type (structured and/or unstructured) and storage needs, for example, security, access and storage capacity in relation to data volume and storage duration (short- and or long-term).

Based on the data sources at Adventure Works, which storage solution(s) (on-premises, cloud-based, or hybrid) are most suitable for storing data from each source? Explain your reasoning.

Discuss four key factors to consider when selecting a data storage solution for Adventure Works.

What are the main advantages of hybrid storage for Adventure Works, and how can it help the company optimize its data storage solutions?

Given Adventure Works' rapid growth and expanding data volumes, which aspects of data management should the company prioritize?

### Conclusion
In this exercise, you analyzed the data sources Adventure Works uses and their storage requirements to determine the appropriate storage solution for the company. You learned about different data types and storage solutions and gained insight into data storage planning. 


# Exemplar: Data Storage and Management

### Introduction

In the exercise **Data Storage and Management**, you evaluated the data sources and types the data analytics team uses in the Extract, Transform, Load (ETL) process at Adventure Works and data storage solutions. You then answered questions addressing key aspects related to data storage at Adventure Works, including the suitability of a specific storage solution, factors to consider in data storage planning, the advantages of hybrid storage, and the importance of data governance.

You can use the example answers in this reading as a guide to assess your answers to the questions in the exercise. Your answers may differ from the ones in this reading and still be correct.

### Data Sources and Storage Needs

**Sales Data**

- **Data Type:** Structured
- **Data Storage Needs:** 
  - Moderate to high scalability to handle increasing volume over time.
  - Secure access for sensitive data.
  - Collaboration and sharing for less sensitive data.
  - Short-term storage for recent transactions and customer service.
  - Long-term storage for historical data and sales performance analysis.

**Manufacturing Data**

- **Data Type:** Structured
- **Data Storage Needs:**
  - Moderate to high scalability to accommodate changing levels.
  - Secure access and high security for sensitive data (e.g., intellectual property).
  - Controlled collaboration within the department.
  - Short-term storage for immediate operational needs.
  - Long-term storage for analyzing historical trends and improving production.

**Financial Data**

- **Data Type:** Structured
- **Data Storage Needs:**
  - Secure access with high security due to sensitivity.
  - Compliance with legal regulations.
  - Low to moderate scalability.
  - Short-term storage for current financial management.
  - Long-term storage for financial trend analysis and audits.

**Market Research Data**

- **Data Type:** Structured and Unstructured
- **Data Storage Needs:**
  - Moderate to high scalability.
  - Collaboration and sharing.
  - Short-term storage for ongoing research and campaigns.
  - Long-term storage for historical data and trend analyses.

**Social Media and Online Reviews Data**

- **Data Type:** Mostly Unstructured
- **Data Storage Needs:**
  - High scalability for large volumes of data.
  - Collaboration and sharing.
  - Short-term storage for real-time monitoring and customer response.
  - Long-term storage for tracking trends.

### Suitable Storage Solutions

**Sales Data**

A hybrid storage solution is ideal. Structured data is suited for on-premises storage for better security and control over sensitive information. Cloud-based storage can be used for less sensitive data, enabling easier access and collaboration.

**Manufacturing Data**

On-premises storage is suitable due to the structured nature and sensitivity of the data, such as intellectual property and production processes, ensuring high security and control.

**Financial Data**

On-premises storage is recommended due to the structured and sensitive nature of financial data, which requires strict security and compliance.

**Market Research Data**

A hybrid storage solution is appropriate. Structured data can be stored on-premises for security, while unstructured data can be stored in the cloud for easier access and collaboration.

**Social Media and Online Reviews Data**

Cloud-based storage is ideal due to the unstructured nature of the data and the need for extensive processing, scalability, and easy access.

### Key Factors in Selecting a Data Storage Solution

**Accessibility and Collaboration**

The storage solution should facilitate easy access and collaboration, especially for less sensitive data that requires frequent sharing. Cloud-based storage is beneficial for its accessibility from anywhere and efficiency in workflows and decision-making.

**Scalability**

Adventure Works' rapid growth necessitates scalable storage solutions. Cloud-based storage is advantageous as it can be easily scaled without significant hardware investments.

**Data Sensitivity and Security**

Given the variety of sensitive data types, prioritizing security measures is crucial. On-premises storage can be used for highly sensitive data to ensure control and reduce vulnerability to breaches.

**Data Type**

The storage solution must handle both structured and unstructured data efficiently. Structured data can be stored in traditional databases, while unstructured data benefits from cloud-based data lakes.

### Advantages of Hybrid Storage

**Flexibility**

Hybrid storage provides flexibility to store diverse data types in suitable environments based on sensitivity and usage. Structured data can be kept on-premises for security, while unstructured data can be stored in the cloud for access and analysis.

**Scalability**

A hybrid solution allows Adventure Works to scale storage resources quickly and cost-effectively, accommodating growing data volumes, especially in areas like social media data.

**Security and Control**

Hybrid storage balances the security and control of on-premises storage with the scalability and accessibility of cloud storage. Sensitive data can be securely stored on-premises, while less sensitive data benefits from cloud accessibility.

**Improved Data Management**

Hybrid storage allows efficient data management by storing data based on type, sensitivity, and usage. Structured data can be securely analyzed on-premises, while unstructured data can be easily accessed and analyzed in the cloud.

### Considerations for Data Management

**Data Governance**

Establish a comprehensive data governance framework with clear policies for data collection, storage, access, and usage to ensure consistent and efficient data management.

**Data Quality**

Maintain high-quality data through processes for checking, cleaning, and enriching data to ensure accurate and reliable analytics and decision-making.

**Data Integration**

Consolidate diverse data sources into a unified view to facilitate comprehensive analysis and deeper insights into business operations and performance.

**Data Security and Privacy**

Implement strong access controls, monitoring, and compliance with data protection regulations to protect sensitive information and maintain customer trust.

**Data Retention and Archiving**

Develop a data retention policy to manage data storage costs, improve system performance, and ensure access to archived data when needed.

## Conclusion

By completing this exercise, you learned about data storage solutions and the role different data types and sources play in the selection of these solutions. You gained hands-on experience evaluating data sources and types, as well as determining an appropriate storage solution, in a business context. As data continues to play an increasingly important role in businesses like Adventure Works, having the right data storage solutions in place is essential.

# Data Transformed in Power BI

### Introduction

You're working in a data analysis role at Adventure Works, and one day, your manager comes to you with a spreadsheet. It’s filled with raw data about sales, production, and inventory. She asks you to find meaningful insights from this data to help optimize the company's processes and make better decisions. You know that transforming this data in Microsoft Power BI using Microsoft Power Query will make it much easier to analyze and extract valuable insights, so you get to work.

This reading assists you in understanding the importance of data transformation in the data analysis process. It explores data transformation functions in Power Query, such as removing duplicates, filling in missing values, and changing data types. You’ll discover how these functions can be combined to suit your specific data transformation needs.

### Data Transformed in Power BI

Data transformation is the process of converting raw data into a more meaningful and usable format. In the context of Power BI, this means taking your raw data, which may be messy, unstructured, or difficult to interpret, and transforming it into a format that is easy to understand and analyze. Power Query is a powerful tool within Power BI that allows you to perform these transformations with ease. The raw data you have been given by your manager at Adventure Works is a massive spreadsheet with thousands of rows containing information about customers, products, sales, and more. However, the data is not in a format that is easy to analyze – there are missing values, duplicate entries, and inconsistencies in the way the data is presented. Let’s examine three stages of the data transformation process.

### Before Transformation

The initial sales data for Adventure Works is a jumbled mess of information. There are columns with missing values, such as customer addresses and product descriptions. Some rows have duplicate entries, while others have inconsistent formatting (e.g., dates in different formats or mixed use of upper and lowercase letters). The data is difficult to understand and analyze in its current state.

### Power Query in Action

To tackle the data issues, you turn to Power Query in Power BI. You use Power Query to clean, organize, and structure the data. You start by removing duplicate entries and filling in missing values using various data transformation functions available in Power Query. You then standardize the formatting of dates, text, and other data elements to ensure consistency across the dataset. You also create new columns to better categorize and classify the data for easier analysis.

### After Transformation

The transformed data now has a more structured and organized format, with no missing values, duplicate entries, or formatting inconsistencies. The new columns created during the transformation process make it easier to understand and analyze the data. With these improvements, you can now perform accurate and efficient data analysis, leading to better insights and more informed decision-making.

### Common Data Transformation Functions in Power Query

Power Query offers numerous transformation functions that cater to various data types and scenarios. Some of the most common transformations include:

- Removing duplicates
- Filling in missing values
- Splitting or merging columns
- Changing data types

These functions can be combined in various ways to suit your specific data transformation needs. To further illustrate the power of data transformation in Power BI, let's take a look at some before and after screenshots.

### Example 1: Data Before Cleaning

![Data before cleaning with a cluttered, unorganized sales data table](images/data-before-cleaning-1.png)

In this initial stage, the sales data table is in disarray. It is difficult to draw any meaningful insights from it due to various issues that hinder its readability and usefulness. Specifically, the table suffers from the following problems:

- **Missing values:** The table contains numerous gaps and incomplete data points. These missing values (depicted as ‘null’) can hinder accurate analysis and interpretation, as they may cause inconsistencies and errors in calculations or aggregations.
  
  ![Data table with missing values](images/missing-values.png)

- **Duplicate entries:** The presence of duplicate entries can lead to incorrect conclusions, as they may artificially inflate or skew the results of an analysis. It is essential to identify and remove duplicates to ensure the accuracy and reliability of any data-driven insights.
  
  ![Data table with duplicate entries](images/duplicate-entries.png)

- **Inconsistent formatting:** Data formatting inconsistencies, such as varying date formats or text capitalization, can make it challenging to understand and compare data points. Proper formatting is crucial for facilitating data analysis and visualization.
  
  ![Data table with inconsistent formatting](images/inconsistent-formatting.png)

### Example 2: Data After Cleaning

![Data after cleaning with a clean, organized sales data table](images/data-after-cleaning-1.png)

### Example 3: Numerical Data Before Cleaning

![Data table before cleaning](images/numerical-data-before-cleaning.png)

This is another example of data before cleaning. A sales table containing numerical data, such as sales price and total amount, formatted as text, making it difficult to perform calculations or create visualizations.

### Example 4: Numerical Data After Cleaning

![Data table after cleaning](images/numerical-data-after-cleaning.png)

The sales table data after cleaning. The numerical data has been converted to the appropriate data types, enabling calculations and visualizations to be created with ease.

These screenshots demonstrate the incredible difference that data transformation can make in your data analysis process. By taking the time to clean, organize, and structure your data using Power Query in Power BI, you can unlock its true potential and gain valuable insights that drive informed decision-making.

### Conclusion

Data transformation is a critical step in the data analysis process, enabling you to convert raw, unstructured data into a more meaningful and usable format. Power Query in Power BI is a powerful tool that allows you to perform these transformations with ease, ultimately leading to more accurate and efficient data analysis. In this example, we've seen how data transformation can drastically improve the quality and usability of your data, using Adventure Works as an example.

So, the next time you're faced with a mountain of messy data, remember the power of data transformation and the magic of Power Query in Power BI. Now that you've seen the transformative power of Power Query in action, it's time to put your newfound knowledge to work. Go forth and conquer your data challenges and may Power Query be your guiding light in the world of data analysis!







