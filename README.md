# Forecasting Taxi Service Data

## 1. Description
Cab booking is generally a process where renting is automated either by call/ app throughout a city. Using the app is simpler as people can book cab from one location to another by choosing the destination. Besides, managing booking is hassle free. For the cab booking app company, understanding the cab supply and demand could increase efficiency of service and enhance user experience by minimizing waiting time.

## 2. Application
Retail / E-commerce, Internet services, Internet shops, Business services [b2b] (outsourcing consulting audit), IT-company, Startups

## 3. Tech stack
- PySpark
- Sklearn
- Pandas
- Numpy
- Matplotlib
- Seaborn

## 4. Results
To preprocess time-series data some methods are applied including time differencing and moving average for feature extraction. This helps avoid auto-correlation between attributes and define relationships between them. Eventually, Gradient Boosted Tree for both PySpark and Sklearn libraries provides RMSE as low as in range 43..45. Thus, predictions on the number of booked cabs are accurate enough.
