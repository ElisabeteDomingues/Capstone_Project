# Capstone_Project

The capstone project was the final group project for the data analytics course at Boolean UK Academy. It focused on an E-commerce business/marketing setting. My role involved analyzing the "users" table. I conducted a query, extracted data, performed cleaning and manipulation using Python, and analyzed the user's online behavior, presenting the results in Tableau.

BigQuery was used solely for data download, where I conducted a simple cleaning in Python and visualized the data in Tableau.

Upon reviewing my dataset, I observed NaN values in the user_id and city columns. Additionally, I noticed that the created_at column should be separated, at least to facilitate easier extraction of the date.

![Image](https://github.com/ElisabeteDomingues/ElisabeteDomingues/assets/135114095/52d52b30-e61b-4548-bc3a-1c1cf22b4393)
image: Data in BigQuery


![Image](https://github.com/ElisabeteDomingues/ElisabeteDomingues/assets/135114095/2d4709b1-c121-4036-a089-bcf8ab86e4d5)
image: Number of NaN in dataset

As a result, I replaced NaN values with zeros and split the 'created_at' column into two parts: the 'date' and 'time' columns.

![Image](https://github.com/ElisabeteDomingues/ElisabeteDomingues/assets/135114095/0705cf93-84a2-42c4-b414-df2eb7609526)
image: Code in Python

On the first dashboard, it's evident that the most frequently occurring event is 'product,' and Google Chrome is the most used browser. The majority of traffic originates from email, followed by ads. The state with the highest number of events between 2019 and 2023 is in China, followed by England.

![Image](https://github.com/ElisabeteDomingues/ElisabeteDomingues/assets/135114095/840a4270-df45-4054-b4f3-58546249bbe8)
image: The dashboards are interactive, and it is observed that examining each state individually reveals relatively consistent results.


Here, we can analyze the number of events where different browser types were utilized over time, along with the traffic sources. As evident from the data, we can see that the traffic is increasing over time across all types, mirroring the usage patterns of respective browsers. The forecast predicts a continued upward trajectory in this trend.

![Image](https://github.com/ElisabeteDomingues/ElisabeteDomingues/assets/135114095/287a8ed6-8531-4998-87d4-75aba21e2906)
image: Browser, traffic in time globally and for each state.
