# FutureTale Hotel Reservation Case Study

![SharedScreenshot](https://user-images.githubusercontent.com/128720674/236288986-62d80bc3-c0db-4356-9810-6b9191642aec.jpg)

#About FutureTale Hotel:

FutureTale Hotel is a modernised hotel with state of the art facilities to give customers undeniable comfort

#Project Problem:

FutureTale Hotel is having reservation challenges due significant reservation cancellation which is causing revenue loss

#Dataset:

The reservation MS Excel dataset contained 36,276 records and 19 columns. 
The features include booking ID, number of adults, number of children, number of weekend nights, number of week nights, type of meal plan, required car parking space, room type reserved, lead time, arrival year, arrival month, arrival date, market segment type, repeated guest, number of previous cancellation, number of previous bookings not cancelled, average price per room, number of special guest and booking status

#Action:
1. Checked for duplicates using the remove duplicate function
2. Filtered columns to check inconsistency in data
3. Used the sum function to find Total Nights
4. Multiplied Total Night by Average Price to find Revenue
5. Used If function to seperate revenue into Revenue received and Revenue lost
6. Used If function to convert months in numbers into string
7. Grouped Lead Time into Normal (<= 30 days), Long (<= 60 days) and Prolong (> 60 days) 
8. Pivot Tables were created to analyze dataset
9. Pivot Charts were generated from the Pivot Tables
10. Dashboard created to visualize analysis
11. Slicers were inserted to filter dashboard charts

#Finding:
- 357% increment inreservation with cancellation increment of 1,037% between 2017 and 2018
- $4.2 loss in revenue due to reservation cancellation
- 64% of reservation is made via online channel contributing to more than half of revenue
- Lead time lenght can predict the likehood of reservation cancellation
- Reservations peak in October with 5,317 bookings
- Room_Type 1 is the choicest room with 78% booking

#Recommedation:
- Penalties should be introduced to curb long lead time hence reducing cancellation and revenue loss
- Re-evalaluate services provided by other room types other than Room_Type 1 to increase their reservation and revenue generation 
- Promote other reservation channels with add-in to boost reservation and revenue
- Effective management between peak and off-peak months to control cost
