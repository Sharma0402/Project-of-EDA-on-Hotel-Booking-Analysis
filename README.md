# Project-of-EDA-on-Hotel-Booking-Analysis
This project is related to Hotel Booking having two hotel description i.e. city hotel and resort hotel. In this dataset contain total rows 119390 and 32 columns. In this we divide data manipulation workflow in three category:Data collection,Data cleaning and manipulation and EDA(Exploratory data analysis).As further moved i.e. Data collections first step to find differnt columns which is done by coding Head(),Tail(),info(),describe(),and some other method used for data collections,some of the columns name is updated here i.e.hotel_is_canceled,lead_time,arrival_data,arrival_month,arrival_data_week_number,arrival_date_day_of_months,stay_in_week_end_nights.As we further moved we find unique value of each columns and generate a list in tubular form and also check the dataset type of each columns find some columns not in accurate data which correct it later done in data cleaning part and as well as duplicate items must be removed as we find duplicate items equal to 87396 which is droped from dataset later.

Before visualize any data from the dataset we have to do data wrangling for that,we are checked the null value of all the columns.After checking,when we are getting a column which has more number of null values,droped that column by using the 'drop' method.In this way,we are droped the company column.When we are find minimal number of null values,filling these null value with necessary values as per requirement by using fillna().

Different charts are used for data visualisation so that better insights and bussiness objective is attended.
