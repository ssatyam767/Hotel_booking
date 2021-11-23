# Hotel_booking
 Hotel Booking Prediction
 
 
Problem Statement: Leverage Guest Data and Booking Behaviour Patterns to devise a strategy for Hotel Revenue Management, using Data Science and Machine Learning

Data : The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

Type of Given Datapoints :

    1) Market Segments : Offline vs Online sources from where the booking is generated and related variables
    2) Hotel and Revenue: City or Resort Hotel, ADR etc.
    3) Customer Related: Variables describing the type of customer based on stay, whether returning, accompanied by how many etc
    4) Cancellation History: Has their been cancellations made earlier? etc
    
EDA :
    1) Do Cancellations differ by type of hotel? 
    2) Where do the cancellation originate from? How do they differ by different Market Segments?
    3) How does Lead Time and Average Daily Rate differ?
    4) What is relationship between Lead Time and Cancellation Rate Relate to each other?

    
    
    
Data Preprocessing:
    -Try to build separate models for Resort and  City Hotels
    -Build indicator or One-Hot encoded variables that maximizes the discrimination
    -Explore Bi-variate relationships to check if specific pockets can be identified where likelihood capture maximizes
    -For Example – Returning Customers who belong to Transient Party Category
    -Treat the company variable and create some bins out of it. Interact the bins with the Customer Type and check for possibilities as described above
    -Build and engagement index of the booking to assess how deeply is the customer likely to embed in the hotel’s services
    
    
 Algorithms:
    -Bi-directional approach : Both classifier algorithms (Statistical and ML Based) can be tried out and results compared for final deployment
 






