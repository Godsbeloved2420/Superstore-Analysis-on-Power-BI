# Superstore_Analysis_using_PowerBI

## 1.0. Title
Analysis of superstore dataset using Power BI

## 2.0 Introduction

### 2.1. Objectives: 

The analysis aimed at:

a) answering business questions related to the company using charts to visualize the data. Some of the questions include:

(i) Sum of profit by category

(ii) Total Sales by Region

(iii) Number of Orders by Region

(iv) Sum of Revenue by Segment

b) showing trends and context for key metrics such as Sales, Profit and Revenue.

c) demonstrating the relationship in data models.

d) Organizing Measures into Measure table.


### 2.2. Context:

The dataset is made up of Superstore data from 2014 to 2016. 

### 2.3. Data Sources

The primary source of data used here is Superstore.xlsx which is an open source data which was given as a practice data. The following is the link to the dataset: 

https://drive.google.com/file/d/14sxrhVjy_hoO68bgH0Rkg-L7h6yAU4-https://drive.google.com/file/d/14sxrhVjy_hoO68bgH0Rkg-L7h6yAU4-

## 3.0. Data Understanding

### 3.1. Data description
The dataset was gotten in a structured form and contains 9995 observations. 

### 3.2. Exploratory data analysis (EDA)

Microsoft Power BI was implored in cleaning, analyzing and viewing the dataset. At the end of the analysis, we were able to:

a) visualize the different KPIs that show trends and context for key metrics such as Sales, Profit and Revenue.

b) visualize the Sum of Profit by Category, Total Sales by Region and Sum of Revenue by Segment.


## 4.0. Methodology

### 4.1. Data preprocessing

The dataset was imported and loaded into Power BI. There was no need for cleaning of the dataset because it has been cleaned before importing into Power BI. Though the Sales, profit and Discount columns were formatted to display currency values.

### 4.2. Analysis

a) a new column was added to get the Revenue (Revenue = Orders[Sales] - Orders[Discount]).

b) Calendar and Measures Tables were created. For the Calender Table, 

```Power BI
CALENDARAUTO()
```

c) new columns: Week Day (Week Day = WEEKDAY ('Calendaer' [Date], 1)), Month (Month = MONTH ('Calendaer' [Date]), Quarter (Quarter = QUARTER ('Calendaer' [Date]) and Year (Year = YEAR ('Calendaer' [Date]) were created.

d) New measures were created which include: Total Revenue (Total Revenue = Sum (Order[Revenue]), Total Profit (Total Profit = Sum (Order[Profit]) and Total Sales (Total Sales = Sum (Order[Sales]) and were organized into Measures Table.

e) Creating of relationships in data model - the Calender Table was linked to the Orders Table by marking the Calender Table as the date table and dragging the Order Date to Calender table.

### 4.2. Assumptions:
The males purchased more bike more than the female gender due to the fact they earned more than the females.


## 5.0. Analysis

### 5.1. Results

#### Relationship between average income of each gender and their bike purchase history

![picture 1](https://github.com/user-attachments/assets/e9f0837a-1c99-45c2-a314-d651effb82ff)

#### Relationship between distance travelled by cummuters and bike purchase

![picture 2](https://github.com/user-attachments/assets/f1ca7034-3c1a-40a3-a4ef-2cdcf42e2b35)

#### Relationship between age bracket and bike purchase
	          
![picture 3](https://github.com/user-attachments/assets/82d0f979-dfba-4d93-9911-257640dca2e3)

                        
### 5.2. Interpretation/key findings: 

From the result, it can be seen:

•	The male customers earned more than the females and therefore purchased more bike than the females.

•	the company had more patronise from customers who travel 0-1 miles compared to others. The lowest patronise came from that travelled distances more than 10 miles.

•	the middle-aged customers purchased bike the most compared to the adolescents and the old customers.

•	

## 6.0. Conclusion

### 6.1. Summary of finding:

•	TThe dataset contained data collected by a Bike company that deals on bike. The different fields contain different socio-demographic and bike purchase history of the customers.

•	The dataset had 26 duplicates which was dropped from the dataset.

•	The male customers earned more than the females and therefore purchased more bike than the females.

•	the company had more patronise from customers who travel 0-1 miles compared to others. The lowest patronise came from that travelled distances more than 10 miles.

•	the middle-aged customers purchased bike the most compared to the adolescents and the old customers.


## 7.0. Acknowledgement

I acknowledge PSP Analytics for this great platform for learning. I want to sincerely our facilitators (Mr. Okon Prince, Mr. Joseph Edet, Mr. Joseph Elijah and Mr. Zion) for providing the dataset that was used for this analysis and for their tireless efforts to ensure we get the best from the training. Google Colab was employed in this analysis.

