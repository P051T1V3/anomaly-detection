# anomaly-detection

The given original data had cities of a country and KPIs of a company. These were obstructed for privacy. The original data values were randomized by adding noise. 

This change in input data does not affect the functionalities of the notebook. 

## The data has 5 headers:

1. DATE: Date of the recorded value
2. KIND: The determines how the KPI is NOT supposed to act. 
    * "LOW" means the KPI can have anomalies if the value decreases too much suddenly.
    * "HIGH" means the KPI can have anomalies if the value increases too much suddenly.
  
3. CITY: The city in which the value was measured
4. KPI: The key performance indicator that was evaluated to get the value.
5. VALUE: The result of the KPI evaluation at the city on the specified date.
