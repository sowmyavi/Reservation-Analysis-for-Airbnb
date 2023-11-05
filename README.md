# Reservation-Analysis-for-Airbnb
Airbnb is the largest platform to find and rent homestays and apartments for vacations and holidays. We are provided with data from the year 2008, to perform EDA. EDA helps us to identify important features for the better improvement of the service. It helps us to understand the data in different aspects. Airbnb is one of the largest used companies for lodging primarily homestays for vacation rentals and tourism activities. Today Airbnb is one of the most used brands to give hosts and guests a good experience. The data is used to increase the understanding of every detail to make traveling easy and convenient. The data is utilized to show the required conclusions. The conclusions are also shown in the visualizations to make understanding easier. A minor mistake in the price dataset exists, with approximately 10% of the properties having a price of 0$, which has no correlation. Therefore, we employed the median to reflect real data rather than utilizing the mean to fill in the incorrect prices.
## Problem Statement
1. AIRBNB's main function is to offer homestays for vacation rentals and tourism-related activities; the company does not own any of the houses on its list. Simply put, it's an internet marketplace with all the properties posted.
2. The Reviews are the aspect that influences this business. If guests leave positive evaluations, there's a good probability that it will be booked multiple times depending on availability; conversely, if there are bad reviews, guests probably wouldn't want to stay there.
3. Based on the available information, about 25% of the properties on the list are either home-apts. If shared or private rooms lack reviews, it might be detrimental to preserving a positive rapport with the hosts of the properties on the list.
4. There is a little mistake in the price dataset; around 10% of the properties have a price of 0$, which has no bearing on anything. Therefore, we use the median rather than the mean to reflect real data.
## Column Features
1. host_name: The Name of hosts who give services to guests
2. Neighbourhood_group: Represents the city
3. Neighborhood: Represents areas of the city
4. Latitude and longitude: Represents the location of the house
5. room_type: Represents the type of room(shared/private/apt)
6. price: Represents price of the houses
7. minimum_nights: Nights spent by customers
8. number_of_reviews: Number of reviews
9. last_review: Date represents the last review by customers
10. reviews_per_month: Reviews per month
11. calculated_host_listings_count: Host count listing
12. availability_365: The availability of hosts per year
The box plot represents the Price Column showing too many outliers present in the data.
So, we will use the median in place of zero values and NA values.
<img width="763" alt="Screenshot 2023-11-04 at 5 51 05 PM" src="https://github.com/sowmyavi/Reservation-Analysis-for-Airbnb/assets/143238723/f391ae83-6d7b-459a-9f6e-920438d632b8">

The list represents the average value of the room types corresponding to the Neighborhood group. The list can give us the estimate of price listing in different areas.
<img width="1332" alt="Screenshot 2023-11-04 at 5 53 02 PM" src="https://github.com/sowmyavi/Reservation-Analysis-for-Airbnb/assets/143238723/8df623b2-1a2d-4c03-ad04-11d7137c4781">

## EDA
Using a variety of visualization tools and statistical graphs, EDA is a method for analyzing data sets. What data can reveal beyond formal modeling or hypothesis testing tasks is demonstrated by EDA. It offers a deeper comprehension of the data and the interdependence of its properties. It aids in the detection and management of outliers and missing values. It facilitates our ability to work with data sources and get the information we require from them. Our comprehension of the problem statement improves. To help us grasp the data in this problem, we have created some visuals.

Outlier Data:
Outliers are the data points that affect the data at the model building which gives wrong predictions. The accuracy of the model is affected.
Here in our data, we are taking price and availability_365 for checking outliers.
<img width="601" alt="Screenshot 2023-11-04 at 5 54 57 PM" src="https://github.com/sowmyavi/Reservation-Analysis-for-Airbnb/assets/143238723/30aa61ec-75b2-42aa-83a9-906ab9c8a34e">
## Visualizations 
We have graphically displayed the average cost of the various rooms for the various Neighborhood Groups in this bar plot.
We discovered a whole apartment in Manhattan with the highest
In Staten Island, the average cost of a shared room is cheaper than that of an individual, at $21.
<img width="1138" alt="Screenshot 2023-11-04 at 5 56 46 PM" src="https://github.com/sowmyavi/Reservation-Analysis-for-Airbnb/assets/143238723/3fa35906-30d8-49b0-b136-36445735c0e6">
In the above bar plots, we found the top expensive hotels and less expensive hotels. The top expensive hotel in Fort Wadsworth at $800 and the less expensive hotel is Bull’s Head at $47.

## References
1. Medium
2. GeeksforGeeks

