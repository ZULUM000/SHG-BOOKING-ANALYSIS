# SHG-BOOKINGS-ANALYSIS
----
### TABLE OF CONTENT
1. Project Brief
2. Data Dictionary
3. Objective of The Analysis
4. Dashboards

## Project Brief
My task involves a thorough analysis of a comprehensive dataset, featuring intricate details of bookings, guest demographics, distribution channels, and financial metrics. By applying your analytical prowess, I aim to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of SHG in delivering unparalleled hospitality.

----

## Data Dictionary:

1. Booking ID: Unique identifier for each booking.
2. Hotel: Type or name of the hotel within the Splendor Hotel Group.
3. Booking Date: Date when the booking was made.
4. Arrival Date: Date when the guests are scheduled to arrive.
5. Lead Time: Number of days between the booking date and arrival date.
6. Nights: Number of nights the guests are booked to stay.
7. Guests: Number of guests included in the booking.
8. Distribution Channel: The channel through which the booking was made (e.g., Direct, Online Travel Agent, Offline Travel Agent).
9. Customer Type: Type of customer making the booking (e.g., Transient, Corporate).
10. Country: Country of origin of the guests.
11. Deposit Type: Whether a deposit was made for the booking (e.g., No Deposit, Deposit).
12. Avg Daily Rate: Average daily rate for the booking.
13. Status: Status of the booking (e.g., Check-Out, Canceled).
14. Status Update: Date of the last status update for the booking.
15. Canceled (0/1): Binary indicator of whether the booking was canceled (1 if canceled, 0 if not canceled).
16. Revenue: Revenue generated from the booking.
17. Revenue Loss: Loss in revenue if the booking was canceled (negative value if the booking wasn't canceled).


## Objective of The Analysis
Objectives of the Analysis:

1. Booking Patterns:
    1. What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity? ![image](https://github.com/user-attachments/assets/721d4758-ff97-4c78-8f85-35be004d260c) ![image](https://github.com/user-attachments/assets/a8b28b7f-0e83-483d-a0b8-c2b7b51472c8)

         Answer: We Can see the trends of the booking patterns over time, seasons  that January 2017 Has The Most Increased Booking Activity with a total of 7869 Bookings and the rest following and Winter the season with most bookings of 39324 Bookings.

    2. How does lead time vary across different booking channels, and is there a correlation between lead time and customer type? ![image](https://github.com/user-attachments/assets/6409ffcb-1ecd-4b78-a2bb-d79b777c7a13)

         Answer: We can see the variation of the lead time across the various bookng channels and also see the relaionship between the lead time and customer type as Transients Customers Have The highest lead time .
       
2. Customer Behavior Analysis:
    1. Which distribution channels contribute the most to bookings, and how does the average daily rate (ADR) differ across these channels? ![image](https://github.com/user-attachments/assets/fb3cd0e3-5083-4b6f-8837-148012c08985)


          Answer: The Online Travel Agent Distribution Channel contributed the most booking with 74072 bookings and its tootal averate rate.
       
    2. Can we identify any patterns in the distribution of guests based on their country of origin, and how does this impact revenue? ![image](https://github.com/user-attachments/assets/02310653-f745-4b77-b1f0-d34dabcc971f)

          Answer: We can see the distribution of guests across the various countries having Portugal untop with 90036 bookings and  A revenue of +$9M
        
3. Cancellation Analysis:
    1. What factors are most strongly correlated with cancellations, and can we predict potential cancellations based on certain variables? ![image](https://github.com/user-attachments/assets/b3aac2ae-faf6-41d3-8d23-b8eebbb0dab0)

          Answer: 
    2. How does the revenue loss from cancellations compare across different customer segments and distribution channels? ![image](https://github.com/user-attachments/assets/24867a15-d7b3-42e4-9ec1-2046833baad2)

          Answer: We can see the effects of cancellation comparism across the various segments, distributions and how they affect the revenue loss
       
4. Revenue Optimization:
   1. What is the overall revenue trend, and are there specific customer segments or countries contributing significantly to revenue?![image](https://github.com/user-attachments/assets/f8ed9f88-61b5-4042-adce-aa44f2c21a0f)

   2. Can we identify optimal pricing strategies based on the Average Daily Rate (ADR) for different customer types and distribution channels? ![image](https://github.com/user-attachments/assets/1439d2e9-25d6-427f-86cd-5e76f31f33cc)

5. Geographical Analysis:
   1. How does the distribution of guests vary across different countries, and are there specific countries that should be targeted for marketing efforts?![image](https://github.com/user-attachments/assets/8152ab2a-8a8f-4636-b682-223cb2ce65d6)

   2. Is there a correlation between the country of origin and the likelihood of cancellations or extended stays?![image](https://github.com/user-attachments/assets/28244819-8174-4f16-8092-8830bd4271b3)


6. Operational Efficiency:
    1. What is the average length of stay for guests, and how does it differ based on booking channels or customer types?![image](https://github.com/user-attachments/assets/6670a281-6225-4a39-aaf5-7328fced6f35)

    2. Are there patterns in check-out dates that can inform staffing and resource allocation strategies?
  Insights for Pricing Strategies:
High ADR Segments: Focus on customer types and distribution channels with higher ADRs. You can analyze whether these segments can sustain higher pricing or offer premium services.

Low ADR Segments: For segments with lower ADRs, you might consider offering discounts or promotions to boost room night sales or explore ways to improve the ADR through value-added services.

Revenue Contribution: Evaluate the total revenue and number of bookings alongside ADR to see if certain customer types or distribution channels are contributing significantly to your bottom line. You may decide to incentivize these channels to drive more bookings.
7. Impact of Deposit Types:
    1. How does the presence or absence of a deposit impact the likelihood of cancellations and revenue generation?![image](https://github.com/user-attachments/assets/2b19c4a6-6d9f-4102-a8bb-567c3b8e0298) 
    2. Can we identify any patterns in the use of deposit types across different customer segments? ![image](https://github.com/user-attachments/assets/1f937ceb-dbbf-4b33-81d0-875d1e0dd793)

8. Analysis of Corporate Bookings:
What is the proportion of corporate bookings, and how does their Average Daily Rate (ADR) compare to other customer types?
Are there specific trends or patterns related to corporate bookings that can inform business strategies?

9. Time-to-Event Analysis:
How does the time between booking and arrival date (lead time) affect revenue and the likelihood of cancellations?
Are there specific lead time ranges that are associated with higher customer satisfaction or revenue?

10. Comparison of Online and Offline Travel Agents:
What is the revenue contribution of online travel agents compared to offline travel agents?
How do cancellation rates and revenue vary between bookings made through online and offline travel agents?

