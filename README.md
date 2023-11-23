## EDA Of Flight Ratings Using Python 

The project aims to analyze customer satisfaction in the airline industry by leveraging a dataset containing various attributes related to passengers' experiences. This analysis will provide insights into factors that influence passenger satisfaction, identify areas for improvement, and help airlines make data-driven decisions to enhance customer service.

### Dataset Description
* **ID** : Unique identifier for each passenger.
* **Gender** : Passenger's gender.
* **Customer Type** : Indicates if the passenger is a loyal or disloyal customer.
* **Age** : Passenger's age.
* **Type of Travel** : Specifies whether the travel is for business or personal reasons.
* **Class** : Travel class (e.g., Business, Economy).
* **Flight Distance** : The distance of the flight in miles.
* **Various Service Ratings** : Ratings for in-flight services like inflight wifi, departure/arrival time convenience, online booking, etc.
* **Departure Delay in Minutes** : Delay in departure time (in minutes).
* **Arrival Delay in Minutes** : Delay in arrival time (in minutes).
* **Satisfaction** : Indicates passenger satisfaction with the overall experience (e.g., "satisfied" or "neutral").

### Objective
* **Data Exploration**: Explore the dataset to understand its structure, missing values, and basic statistics.
* **Data Cleaning**: Preprocess the data by handling missing values, outliers, and formatting issues.
* **Descriptive Analysis**: Conduct exploratory data analysis to uncover patterns and relationships in the data.
* **Visualizations**: Create visualizations (e.g., bar charts, histograms) to present findings effectively.

### Insights:
* The data set contains 103,904 rows and 24 columns representing passenger survey responses. Key variables include demographics, flight details, service ratings, and satisfaction.
* Loyal customers are slightly more neutral or dissatisfied than disloyal customers, especially in the economy. Business class has higher satisfaction overall.
* The majority of passengers are middle-aged adults or young adults. <p align="center"> <img src="https://github.com/Utkarsh11-git/EDA_Python_Flight_Rating/assets/92782014/0d50a68a-5559-47ce-9172-f9d45119a656.png" width="450" height="350"> </p>
* Business-class passengers travel nearly twice the average flight distance compared to economy-class passengers. The distribution between eco and eco+ is similar. <p align="center"> <img src="https://github.com/Utkarsh11-git/EDA_Python_Flight_Rating/assets/92782014/dc0f98b9-181d-4902-b81b-5a83cb72b3ba.png" width="340" height="350"> </p>
* Business class has slightly lower average departure and arrival delays compared to economy plus.
* Loyal customers fly farther distances on average across age groups compared to disloyal customers. More loyal customers in young or middle-aged age groups.
* Passengers rate overall service around 3-3.8 out of 5 on average based on aggregated service scores.
<p align="center">
<img src="https://github.com/Utkarsh11-git/EDA_Python_Flight_Rating/assets/92782014/b9913198-8068-4dd4-987a-743b4c2ae2a9.png" width="450" height="350">
</p>

### Tools and Libraries
* **Python** programming language.
* Libraries such as **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** for data manipulation and visualization.
* **Jupyter Notebook** in Visual Studio for documentation and analysis.
  
### Conclusion
This data analytics project will provide valuable insights into customer satisfaction in the airline industry, helping airlines make informed decisions to enhance the passenger experience and improve overall satisfaction. The findings can be used to optimize services, marketing strategies, and customer retention efforts.
