# Hawaii-Tour-Company
Data Analysis on a Hawaiian Tour Company using Python, SQL, Pandas, and Geopandas

## Background

The subject of this data analysis is a Hawaiian Tour Company in Maui, Hawaii. For the sake of anonymity, the company will be referred to as Hawaiian Tour Company for this data analysis. The data for this project was acquired through a family member who runs and operates the company. Due to the use of sensitive information, the csv files containing the data for this project have not been included. The company operates by managing and directing employees who operate as tour guides for an iconic tour called Road to Hana. This tour takes customers around the isolated eastern side of Maui, Hawaii, where they venture into the lives of native Hawaiians. The other revenue sources for this company consists of reselling tours for other islands/companies and private tours around the island. An important note throughout this data analysis is that ticket prices remain consist for all tours. This means that an increase in revenue directly correlates to an increase in the number of customers.

## Questions Ventured

- Which age group is the largest customer in terms of revenue?
- Which revenue source is the largest?
- What day of the week, month of the year, and season of the year is the most popular/generate the most revenue?
- Where are most of the customers located?
- How has COVID-19 affected the tour company in terms of revenue?

## Age Groups & Revenue Sources

![Age Groups](https://user-images.githubusercontent.com/112305152/190061389-4150b52e-a54b-4980-8ec1-c7e51c43eef7.png)

In regards to the largest revenue source, Road to Hana, the customer basis consisted of 88.68% adults, 3.90% children, and 7.42% senior/military. The age range for the adult group consisted between ages 20-64.

![Revenue Sources](https://user-images.githubusercontent.com/112305152/190061398-e1fe9530-2f41-41e8-8a90-4a97fbc17b63.png)

The largest revenue source was Road to Hana which consisted of 84.02% of the whole revenue. The Oahu Tour and Volcano Adventure Tour are both reseller revenue sources, where the Hawaiian Tour Company acts as a reseller for these tours.

These two conclusions supplement a greater analysis further below.

## Revenue by Weekday, Month, Season

In this section, I wanted to examine which day of the week, month of the year, and season of the year generated the most revenue. This would provide the management of the Hawaiian Tour Company the ability to understand which days they can expect the most amount of customers. By doing so, the Hawaiian Tour Company can allocated more resources during the specific days, months, seasons. The Hawaiian Tour Company can hire more employees in anticipation for busy seasons or months. They can also plan when to purchase long term investments such new tour trucks as high demand can raise the price of these specialized vehicles.

![Revenue by Weekday](https://user-images.githubusercontent.com/112305152/190063502-ee719fee-a293-42bc-b109-855b27a4be94.png)

In this chart, Mondays were found to be the busiest day of the week, followed by Wednesdays and Tuesdays. This can mean that customers prefer to book tours early in the week rather than the expected prediction of Saturdays and Sundays. 


![Revenue by Month](https://user-images.githubusercontent.com/112305152/190064948-1266d2df-03ed-4cd2-b654-304226887e4b.png)
![Revenue by Season](https://user-images.githubusercontent.com/112305152/190065579-e5205ea4-8ba5-4976-9c35-7dbfb8189b8c.png)

Through these two charts, the summer months of June, July, and August were found to be the busiest times of the year with a sudden drop in September. December also generates a peak in revenue during the year but is outshadowed by the summer months.

To summarize, Mondays followed by Wednesday and then Tuesdays during the month of July are the busiest times of the year. As such, the Hawaiian Tour Company can look for seasonal workers during the summer months to provide some relief to the demand of tours during this time. Other factors such as an increase in car washes of tour vans, mechanics, and office workers will be needed during these times.


## Location of Customers

![Locations](https://user-images.githubusercontent.com/112305152/190066442-77ec059c-caed-4681-a94a-b1d45824fc5f.png)

In this section, I found the locations of the largest groups of customers throughout the US. Since the location of the customers were not provided in the database, I used the phone numbers of each customer from the last year in order to approximate their location. The area codes of all customers were first narrowed down and then linked to a database which connected area codes with cities and states. The search was then narrowed down into cities which contained a higher than average number of customers. From here, the search was further limited into the conclusions found before, adults ranging from ages 20-64, and customers who purchased the largest revenue source, Road to Hana. Finally, the search was narrowed to a density of adults per population over 60% and sorted by the largest number of customers. 

The top 10 cities are listed below. This data analysis provides the most beneficial marketing opportunity for the Hawaiian Tour Company. Since the Hawaiian Tour Company have yet to market themselves into other locations, this analysis can serve as a stepping stone. Furthermore, the Hawaiian Tour Company can use this data analysis to find the cities with the least amount of customers and a high density of adults. 

Two things that can make this data unreliable is the use of area codes matching to locations. (1) Customers can move away from the location where they created a phone number. (2) Area codes could match up to more than one city.

![Top 10 Cities](https://user-images.githubusercontent.com/112305152/190066778-62d0a453-f0e9-4de4-935b-d2777c006ef2.png)


## Revenue by Year (Pre-Covid VS. Post-Covid)

![Revenue by Year](https://user-images.githubusercontent.com/112305152/190071342-bf275f35-93c0-42fa-a4ac-834692231245.png)

In this last section, it can be observed that COVID-19 took a significant hit on the revenue for the Hawaiian Tour Company. This is due to the shutdown of air travel, hiring of employees, and overall slowdown of the economy. The revenue hit is noticable during the year of 2019-2020 when COVID-19 first hit. Alongside this data, a comparsion of COVID-19 cases in the US can show the relation between revenue and COVID-19. The vaccination trend can also imply that an increase in the number of vaccinations correlated to an increase in revenue for the Hawaiian Tour Company as customers became more comfortable with traveling overseas.

![us-state-trends](https://user-images.githubusercontent.com/112305152/190073021-c7100697-f816-4e02-8cba-2d168d3ffa36.png)
![vaccination-trends](https://user-images.githubusercontent.com/112305152/190073027-dfb2dde3-a9a6-44ce-a0be-8169b329dcdf.png)
