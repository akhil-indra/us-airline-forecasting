# ✈️ U.S. Airline Passenger Miles Forecasting (2001–2017)

In this project I wanted to understand the travel patterns airlines passengers in the U.S. Has it changed over time? and to see if we can use that past data to predict future values. I worked with monthly airline passenger miles from **2001 to 2016**, then forecasted what 2017 might look like using Excel.

---

### Dataset

The dataset contains **monthly passenger miles flown by U.S. airlines** from 2001 through 2017.

I split the data:
- 2001–2016: Used for building the forecast
- 2017: Used to test how accurate that forecast actually was

---

### Approach

I used **Excel's Forecast Sheet** to build a time series model. It handled the trend and seasonality automatically and gave me monthly predictions for 2017. After that, I compared those predictions to the actual 2017 data and calculated error metrics to evaluate the model’s accuracy.

Additonally I also created line graphs, bar charts, and tables to better understand the data and explain the results.

#### Seasonality (monthly trends over time)

<img width="665" alt="image" src="https://github.com/user-attachments/assets/e20ad382-b6c8-449c-a651-a4da6fe0db19" />

_Peak travel season appear to be mid-year as July and August consistently show the highest passenger miles._


#### Long-term growth patterns

<img width="647" alt="image" src="https://github.com/user-attachments/assets/37d6cdd4-b7d2-4d0c-9694-c64a62df62fa" />

_Despite a dip around 2009, passenger miles steadily increased over the years - strong recovery trend._


#### Model accuracy using **MAE**, **MAPE**, and **MASE**

<img width="652" alt="image" src="https://github.com/user-attachments/assets/ca832448-717f-42c6-b608-ccc618d385d0" />

_Predictions closely follow actual values so strong short-term model performance._


#### Forecast with confidence bounds

<img width="665" alt="image" src="https://github.com/user-attachments/assets/e011a658-0aa8-44ea-8e59-4b6ed0ea752d" />

_Confidence intervals widen over time which may lead to increased uncertainty in long term predictions._

---

### 📊 Key Takeaways

- **Air travel in the U.S. has grown steadily** over the years, despite major disruptions like 9/11 and the 2008 recession.
- There’s a clear **seasonal trend** — travel peaks in **summer (especially July–August)** and drops sharply in **February**.
- The Excel forecast did a good job:
  - **MAE**: ~1.2 million miles
  - **MAPE**: 1.55%
  - **MASE**: 0.475 (which means it did better than a naïve model)

The predictions stayed close to the actual values in most months, especially during peak travel times.

---

#### Tools and Skills Applied: 

- **Microsoft Excel Forecast Sheet**
- Time series modeling and evaluation
- Data visualization (line plots, bar charts)
- MAE / MAPE / MASE calculation
- Interpreting seasonal and trend components
- Explaining results in a simple, clear way

---

### 📁 Files in This Repo

- `us_airline_forecasting_2001_2017.xlsx` – Dataset, forecast, charts, and error metrics all in one file  
  (If you're curious about how it works under the hood, the workbook shows the formulas, outputs, and visuals.)

---

### 💬 Final Thoughts

This project helped me get better at thinking through a data problem from start to finish — not just making predictions, but checking how well those predictions hold up. It was also good practice in using real-world data, dealing with trends and seasonality, and explaining results in a way that makes sense without needing to open up every formula.

