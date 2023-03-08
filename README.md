# EDA_CAPSTONE_PROJECT-1
PROJECT SUMMARY :-
Exploratory Data Analysis(EDA) is an approach to analyze the Data Using Visual Techniques.it is used to discover trends,patterns or check assumptions with the help of Graphical Representations.
In This Project, i am Going to Begin to Explore the Dataset in Which Hotel Booking Comprises between Two Types of Hotels for Example, City Hotels and Resort Hotels.
In This Dataset We Have 119390 Rows, 32 Columns.
This DataSets Have Duplicate And Null Values
In This DataSets have 31994 duplicate values and four Columns have missing Values
In This DataSet Have Float64(4), Int64(16), Object(12) dtype
In this Project I have Divided Data manipulation workflow into three different categories (1)Data Collection, (2)Data Cleaning, (3)Data Manipulation and EDA(EXPLORATORY DATA ANALYSIS).
Moving Further used Various Basic Functions and Attributes Like Data Collections First Step to find Various Columns Which is done by using various method like Head(), Tail(), info(), describe(), Some Other Method Used For Data Collection.
This Dataset Have both Duplicate and Missing Values are available, so need to deal with that and as a result need to replaced the null and missing values to duplicate values also need to dropped.
Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. When combining multiple data sources, there are many opportunities for data to be duplicated or mislabeled. If data is incorrect, outcomes and algorithms are unreliable, even though they may look correct.
The Data Type of Reservation_status_date, column was object so it was changed to date type form to better use.
Before Visulizing any type of data need to do data wrangling so, for that so we have checked the null value of all the columns, so after completing the data wrangling then moved to the data visualisation part.
Then have to started the data visualisation in a structured way while the following 'UBM' rule.
'U' - Univariate Analysis.
'B' - Bivariate Analysis
'M' - Multivariate Analysis
  * In the data visulisation process, have to used various   
    charts and have to deep understanding the graph to catch 
    the proper insight that give thw bussiness outcome
  * Then Have also Used the corelation between the diffrent
    columns that also play avery crucial role in 
    understanding the wholesome relationship the dataset
  * Thus, have Explored and analyzed the data to discover
    import that govern the bookings    
    
    Solution to Business Objective
Suggestion for the client to achieve Bussiness Obejective?
Explain Beiefly

Bussiness Objective attained as follows:

To Attain high growth and more success, hotel bussiness need to flourish and for that few things which we need to consider high revenue generation, customers satisfaction and employee retention.
We are able to achieve the same by showing the client which are the month is high revenue generation by using various charts and graphs distribution.
Enhancing the revenue adopted by bar chart distribution of which type room are most prefered and resevered and which are the months suitable for visitors
we also have founded the various prefernce in different categoris like meal type,optimal stay length,facilities require by customers like car parking spaces,etc. so this all insight need to better planning for growth and revenue.
So preparing well by understanding these all the outcomes, the client can be well prepared in advance so that minimum greivances would be faced by clients in long run and would help in further enhancement of their hospitality and service.
Ask feedback often from the guests visiting the hotels so the quality can be upgraded to the next level to increase more guests.
Periodically trhow offers to attract the old customers so as to increase the no of repeated guests.
Conclusion
City Hotel are most preffered hotel by the guest,So we can say that City Hotel is busiest hotel in comparison of the resort hotel.
The average ADR of city hotels is higher as compared to Resort hotel, so it can easily said that city hotel is generating more revenue than resort hotels.
the total number os stay is directly proportional to adr.so the number of stay is higher then higher will be adr and revenue as well.
The percentage of repeated guest is very low. only 3.9% people revisited the hotels and rest 96.1% were new guests.so the retention rate is much low
Among the different types of meals,BB(bed and breakfast) is the most preferred meals by the guests.so the guests is loved to opt. this type meals.
Direct and TA/TO have equally contribution in adr in both types of hotel , City Hotels and Resorts Hotels.
Optimal stay lenght in both hotels (City hotels and Resort Hotels) is less than 7 days. Usually people stays for a week after 7 days optimal stay length is declined drastically.
most numbers of bookings have taken place in the month of july and august.
The Mostly Used distribution channel for bookings is TA/TO is 79.10% Booking were made through TA&TO(travel agents and Tour Operators)
1/4th of the total booking is cancelled.Approx 27.5% have got cancelled out of all bookings.
Majority of guests have shown interest in the room type 'A'. Room type 'A' is the most prefferd Room type.


Variable Descripton
hotel : Name of the hotel (Resort Hotel or City Hotel)

is_Canceled : if the booking was Cancelled(1) or not (0)

lead_time : Numbers of days has elapsed between entering data of the booking into PMS and the arrival Date

arrival_date_year : year of arrival date

arrival_date_month : month of arrival date

arrival_date_week_number : weeek number of arrival date

arrival_dat_day : day of arrival date

stays_in_wekend_night : number of weekend nights(saturday or sunday)the guest stayed or booked to stay at the hotel

stays_in_week_nights : Number in week nights(Monday to Friday)the guest stayed or booked to stay at the hotel

adults : Numbers of adults

children : Number of children Among Guest

babies : numbers of babies Among Guest

meal : kind of meal opted By Customer

country : Code of respective Country

make_segment : Which segment the customer belongs to

Destribution_channel : How the customer accessed the stay-corporate booking/direct/TA.TO.(TA : travel agent, TO : Tour Operator)

is_repeated_guest : guest coming for the fist time or not

previous_cancellation : was there a cancellation before

previous_ bookings : count of previous booking

resevered_room_type : code of room type resevered

assigned_room_type : code of room type assigned

booking_changes : count of changes made to booking

deposit_type : Type of deposit made by the guest

agent : booked through agent

days_in_waiting_list : number of days in waiting list

customer_type : Type of customer Arrived.

required_car_parking : if car parking required.

total_of_special_req : Number of special requirement by customers

reservation_status : Reservation Status(cancelled, check-out, no show

reservation_status_date : Date of last reservation status

Bussiness Objective attained as follows:

To Attain high growth and more success, hotel bussiness need to flourish and for that few things which we need to consider high revenue generation, customers satisfaction and employee retention.

We are able to achieve the same by showing the client which are the month is high revenue generation by using various charts and graphs distribution.

Enhancing the revenue adopted by bar chart distribution of which type room are most prefered and resevered and which are the months suitable for visitors

we also have founded the various prefernce in different categoris like meal type,optimal stay length,facilities require by customers like car parking spaces,etc. so this all insight need to better planning for growth and revenue.

So preparing well by understanding these all the outcomes, the client can be well prepared in advance so that minimum greivances would be faced by clients in long run and would help in further enhancement of their hospitality and service.

Ask feedback often from the guests visiting the hotels so the quality can be upgraded to the next level to increase more guests.

Periodically trhow offers to attract the old customers so as to increase the no of repeated guests.

Conclusion


City Hotel are most preffered hotel by the guest,So we can say that City Hotel is busiest hotel in comparison of the resort hotel.

The average ADR of city hotels is higher as compared to Resort hotel, so it can easily said that city hotel is generating more revenue than resort hotels.

the total number os stay is directly proportional to adr.so the number of stay is higher then higher will be adr and revenue as well.

The percentage of repeated guest is very low. only 3.9% people revisited the hotels and rest 96.1% were new guests.so the retention rate is much low

Among the different types of meals,BB(bed and breakfast) is the most preferred meals by the guests.so the guests is loved to opt. this type meals.

Direct and TA/TO have equally contribution in adr in both types of hotel , City Hotels and Resorts Hotels.

Optimal stay lenght in both hotels (City hotels and Resort Hotels) is less than 7 days. Usually people stays for a week after 7 days optimal stay length is declined drastically.

most numbers of bookings have taken place in the month of july and august.

The Mostly Used distribution channel for bookings is TA/TO is 79.10% Booking were made through TA&TO(travel agents and Tour Operators)

1/4th of the total booking is cancelled.Approx 27.5% have got cancelled out of all bookings.

Majority of guests have shown interest in the room type 'A'. Room type 'A' is the most prefferd Room type.
