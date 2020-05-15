# **1.	Introduction**

### **1.	Background**

Growth is crucial to the long term survival of a business. It makes it easier to acquire assets, attract new talent and fund investments. It also drives business performance and profit. Growth helps to respond to market demand, allowing the company to increase its market share and capitalize on its growing brand. It often spurs innovation, helping the company to differentiate in the market and stave off competition. Growth can also boost the business’ credibility, allow the companies to broaden its supply base and increase stability and profits. However to be successful and sustainable, growth has to be strategic and has to happen for the right reasons. One of the most common examples of growth is the expansion of Restaurants in various cities. 

### **2.	Problem**

Whether a person owns one restaurant or 20, expansion takes careful planning and consideration. There has to be a considerable strategy that’ll help set up next location up for success. Any brand of restaurant while expanding in a particular location desires that is particular location has a similar or a more promising market environment than the previous one.

### **3.	Interest**

This project aims any company or business, which might be thinking that it’s time to expand their business into another city for growth. 

# **2.	Data**

### **1.	Data requirements**

To find a solution of the Problem and build a recommender model that outputs the location where a Restaurant can expand its business, we need the following information about the restaurants located in various locations in a city.

1.	Its geographical coordinates (latitude and longitude) to find out where exactly it is located.

To study a restaurants neighborhood, we need to access its location i.e., Latitude and Longitude is to be known so that we can point at its coordinates.

2.	Population of the neighborhood where the restaurant is located. 

Population of a neighborhood is a very important factor in determining a restaurant’s growth and amount of customers who turn up to eat. Logically, the more the population of a neighborhood, the more people will be interested to walk openly into a restaurant and the less the population, the less number of people frequently visit a restaurant. Also, if more people visit, the more successful will be the restaurant. 

3.	Average income of the neighborhood to know how much is the restaurant worth.

Income of a neighborhood is also a very important factor as population was. Income is directly proportional to richness of a neighborhood. If people in a neighborhood ears more than an average income, then it is very much possible that they will spend more however not always true with very less probability. So a restaurants assessment is proportional to income of a neighborhood. 

### **2.	Data sources**

1.	A list of neighborhood is scrapped from Wikipedia.
2.	Used Google Map API to fetch Latitude and Longitude for the scrapped neighborhood.
3.	Population data for some of the cities was collected from here. For the cities not available in the link, the population is assumed and may be inaccurate but since this is a demonstrating project, the main idea is to get the working model.
4.	Income for the main city Bangalore can be found here. Again for the neighborhood income, it is assumed and may be inaccurate but since this is a demonstrating project, the main idea is to get the working model.

### **3.	Foursquare API**
Use of foursquare is focused to fetch the nearest Venue locations so that we can use them to form a cluster. Foursquare API leverages the power of finding nearest venues in a radius and also corresponding coordinates, venue locations and names.
