# Flight Price Analysis — Exploratory Data Analysis (EDA)

## Project Overview
This project focuses on performing an Exploratory Data Analysis (EDA) on a flight price dataset collected from online sources. The airline industry is highly dynamic, with ticket prices influenced by multiple operational and demand-based factors such as airline, route, duration, number of stops, and travel time.

The objective of this project is to understand the key factors affecting flight prices, identify meaningful patterns and relationships within the data, and extract actionable insights using data-driven analysis.

---

## Dataset Description
The dataset consists of the following attributes:

- **Airline**: Name of the airline operating the flight  
- **Date_of_Journey**: Date on which the journey is scheduled  
- **Source**: City from where the flight departs  
- **Destination**: City where the flight arrives  
- **Route**: Path followed by the flight from source to destination  
- **Dep_Time**: Scheduled departure time of the flight  
- **Arrival_Time**: Scheduled arrival time of the flight  
- **Duration**: Total travel duration of the flight  
- **Total_Stops**: Number of stops between source and destination  
- **Additional_Info**: Additional flight-related information  
- **Price**: Ticket price (target variable)  

---

## 🔍 Methodology

### Data Cleaning
- Removed missing and inconsistent values  
- Standardized date and time formats  
- Converted categorical variables into analysis-ready formats  

### Feature Engineering
- Extracted **Month** and **Day of Week** from `Date_of_Journey`  
- Converted flight duration into **Total Duration (minutes)**  
- Created **Departure Time Buckets**:
  - Early Morning, Morning, Afternoon, Evening, Night  
- Created **Arrival Time Buckets**  
- Converted `Total_Stops` into numerical values  

### 📈 Exploratory Data Analysis 
- Studied the relationship between total stops and flight prices  
- Examined the impact of departure time on pricing  
- Compared weekday and weekend pricing trends  
- Visualized patterns using statistical plots  

---

## Key Insights
- Non-stop flights have the lowest average prices, while prices increase significantly as the number of stops increases.
- Morning and evening flights generally show higher average prices.
- Weekend flights tend to have slightly higher prices compared to weekdays, indicating higher demand.
- Journey duration and scheduling patterns play a significant role in flight pricing.

---

## Tools & Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook / Google Colab  

---

## Conclusion
This exploratory data analysis demonstrates how multiple operational and temporal factors influence flight pricing. The insights derived from this project can help travelers make informed booking decisions and assist airlines in understanding pricing dynamics driven by demand and scheduling patterns.
