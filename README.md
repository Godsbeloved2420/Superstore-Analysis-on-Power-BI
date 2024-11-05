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

#### The following steps were taken in analyzing the dataset:

a) a new column was added to get the Revenue (Revenue = Orders[Sales] - Orders[Discount]).

b) Calendar and Measures Tables were created. For the Calender Table, 

```Power BI
CALENDARAUTO()
```

c) new columns: Week Day (Week Day = WEEKDAY ('Calendaer' [Date], 1)), Month (Month = MONTH ('Calendaer' [Date]), Quarter (Quarter = QUARTER ('Calendaer' [Date]) and Year (Year = YEAR ('Calendaer' [Date]) were created.

d) New measures were created which include: Total Revenue (Total Revenue = Sum (Order[Revenue]), Total Profit (Total Profit = Sum (Order[Profit]) and Total Sales (Total Sales = Sum (Order[Sales]) and were organized into Measures Table.

e) Creating of relationships in data model - the Calender Table was linked to the Orders Table by marking the Calender Table as the date table and dragging the Order Date to Calender table.

f) Creating of dashboard using charts (column and B, KPIs and cards.

g) slicers were introduced to view the analysis by region, Category, Date and State.


### 4.2. Assumptions:

Products sold by Superstore company favours customers from the Western region more than other regions. 


## 5.0. Analysis

### 5.1. Results

#### Visualization of the Superstore DashBoard

![power bi 1](https://github.com/user-attachments/assets/4d17998d-8cf8-472e-99a4-ee9d95c6b3cd)

                        
### 5.2. Interpretation/key findings: 

From the result, it can be seen:

•	Total profit made from the company was $286,4000.

•	Total orders received was 9994 orders.

•	Total Sales made was $2,300,000

•	Total Revenue and total profit by year was $732,700.

• Total Sales amd total profit by Region was $725, 460.

• The Western region had the highest order with a total of 3,200 Orders.

• The Western region had the highest Sales woth a total Sales of $136,720 (31.82%).

• Consumer had a total Sum of Revenue of $1,016, 000.

## 6.0. Conclusion

### 6.1. Summary of finding:

•	The Company made a total profit of $286,400 in three years.

•	The total Orders received by the Company was 9,994 Orders.

•	The male customers earned more than the females and therefore purchased more bike than the females.

•	The Company made a total Sales of $2,300,000.

•	Looking at the KPIs, the company had a target of achieving $93,044,000 in three years and was able to hit their target and over. Their total revenue and profit by year was $732,007,000.

• By the different regions, the total Sales and profit made by the company was $725,460 with a target of $108,042,000.

• Technology is the category with the highest Sum of Profit.

• West region had the highest Sales compared to the other regions 

• Western region had the highest Orders from Customers.

• By Segment, Consumer had the highest sum of Revenue out of the three segments.


## 7.0. Acknowledgement

I acknowledge LITA for this great platform for learning. I want to sincerely our facilitators for providing the dataset that was used for this analysis and for their tireless efforts to ensure we get the best from the training. Microsoft Power BI was employed in this analysis.

