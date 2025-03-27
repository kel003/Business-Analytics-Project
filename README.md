# Business-Analytics-Project
I have been given raw data by an E-commerce company  and their in need of several tasks being done. We are tracking the online activity of customers visits on the company website and studying the data to see how many page visitors are being converted into actual customers.

First thing that was needed was a pivot table to create a conversion funnel so we can use formulas in our data to get a percentage of activity from our webpage visitors to see how many were converted into being customers. This was done by counting the unique users in our pivot table of the 3 stages our funnel. The 3 stages consists of purchases, shopping cart and views.

Now that we have our data of the conversion rate and averages we must now prepare our cohort analysis. Ive created a new page to filter the purchase activity sheet. Now i can create new pivot table to find our first purchase dates. Using the formula =vlookup  in the cell g2 of my purchase activitity sheet i can now see when first orders were made.I will now label this first_purchase_date. Next i must find the event month, first purchase month and cohort age to help build my cohorts. The formula =text(F2,"YYYY-MM") was used to find the event_month. First_Purchase_Month is next to be discovered using the =text(G2,"yyyy-mm") formula. The finally step of building my cohort is finding the cohort age in my analysis. 

