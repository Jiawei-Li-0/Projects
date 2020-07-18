# Projects
## Project Collection and Discription
   The first two projects are deployed and running upon a Linux instance on Google Cloud Platform.<br> 

### 1. Tmall shopping site: <br> 
   The application simulates real shopping site and implements most of functions of actual online shopping site, including sign up, login, product searching, shopping cart, purchase process, products rating, background products management (modify products, add images, deal with orders, etc).<br> 
   
   Features:<br> 
   >Developed on Spring Boot framework and Vue.js, Ajax, etc.<br> 
   >Apply Hibernate JPA + MySQL for data asscess and persistence.<br> 
   >Apply Redis as caching component.<br> 
   >Apply ElasticSearch engine for products searching.<br> 
   >Use Shrio for private information encryption.<br> 
   
   Shopping Page: http://35.203.107.20:8080/tmall_springboot/home <br> 
   Background Products Management:  http://35.203.107.20:8080/tmall_springboot/admin_category_list<br> 

### 2. Trend Investment: <br>
   Gathering third-party index data and simulate the available trend investment profits based on different parameters setting, and visualizing the simulation results.<br> 
   
   Features:<br> 
   > Developed on Spring Cloud framework and Vue.js, chart.js, etc.<br> 
   > Automatically gathering and refreshing third-party index data and store in Redis caching component.<br> 
   > Apply Histrix for errors tolorance and monitoring.<br> 
   > Apply Zipkin for request tracking.<br> 
   > Apply Zuul for gateway.<br> 
   > Apply Feign for Restful service invocation.<br> 
   > Apply Ribbon for load balancing.<br> 
   
   Project address: http://35.203.107.20:9888/trend <br> 


### 3. Currency Exchange System
   A simple currency exchange system. Calculating the converted money based on the exchange rate from one currency to the other. Returning data encapsulated in Json format to broswer.<br> 
   
   Features:<br> 
   > Developed on Spring Cloud framework.<br> 
   > Apply JPA + H5 database for for data asscess and persistence.<br> 
   > Apply Eureka, Histrix, Zipkin, Zuul, Feign, Ribbon, etc.<br> 
   > Apply Git + RabbitMQ for distributed message bus configuration.<br> 
   

