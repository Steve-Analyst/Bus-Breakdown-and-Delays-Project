# Bus-Breakdown-and-Delays-Project

The project focuses on analyzing the Bus Breakdown and Delays in New York Counties

## Scenario

I've been hired by the New York Division of Transportation as a Data Analyst with the primary goal of improving the efficiency and reliability of the city's bus transportation system. The city has been experiencing a significant number of bus breakdowns and delays, which has been causing inconvenience to commuters and straining the city's public transportation resources.

My task is to analyze the provided data to identify patterns and factors that contribute to these breakdowns and delays. 

## Data Sources

Bus Breakdown and Delays Data: The primary dataset used for this analysis is the "Bus_Breakdown_and_Delays_20240506" file, containing detailed information about issues the school buses encountered from September 2015 until May 2024. You can access the data from [data.cityofnewyork](https://data.cityofnewyork.us/Transportation/Bus-Breakdown-and-Delays/ez4e-fazm/about_data)

## Tools

Excel

## Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Downloading Data and inspection.
2. Handling missing values and blanks.
3. Data cleaning and formatting.
  - Adding Week numbers, then after added Weekdays
  - Corrected Bus company names as many were repeated but not matching the previous name
  - Correct time for delay and use only minutes instead of mixing minutes and hours
  - Removed extreme values such as Bus delays of more than 12 hours or days
  - Used 5 hours (300 minutes) as the maximum delay for our data to give us accurate results for our analysis

## Exploratory Data Analysis

EDA involved exploring the Bus Breakdown and Delays Data to answer key questions, such as:

- What are the most common reasons for delays and breakdowns?
- How do delay times vary by bus company and borough?
- Is there a correlation between specific days of the week and the frequency of breakdowns or delays?

# Answers to the above questions:

## The most common reasons for delays and breakdowns

### Breakdown

<img width="328" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/0838d10c-177d-46a5-aad1-8c8a09344d42">


<img width="458" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/8b0c20ed-2170-46a0-ac4e-77e44378e352">


## Outcomes:

The most common reason for the Breakdown is caused by Mechanical Problems followed by Won't Start which is also part of a Mechanical Problem. Flat Tire is another issue that cannot be ignored. 

## Suggestions:

I recommend the following to be done to minimize these issues: Regular Maintenance and the Address of Warning Signs immediately. 
Buses should be serviced every month or quarterly. Drivers should report any strange noises, warning lights on the dashboard, or changes in vehicle performance immediately and the bus should be looked into immediately. Keep Tires in Good Condition: Checking tire pressure regularly and ensuring they are properly inflated is vital. The inspection of tires for signs of wear and replacing them when necessary to prevent blowouts and other tire-related issues should be done regularly. 


### Running Late

<img width="330" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/1ebae7b3-569a-43e1-88fc-2a533dc6a862">


<img width="464" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/f7d9e0ac-e082-4cb7-99f1-7f4be6552dea">


## Outcomes:

The most common reason for Running Late is caused by Heavy Traffic, Other and Mechanical Problems. The Other could include Heavy Traffic, Mechanical Problems, or other issues not stated.   

## Suggestions:

To ensure school buses run on time and avoid delays caused by heavy traffic, mechanical problems, and other issues, here are some solutions:
Early Departures: Consider adjusting bus departure times to allow for potential delays. Buses can leave earlier than scheduled to account for heavy traffic or unforeseen circumstances, ensuring they arrive at their destinations on time. 
Traffic Management Solutions: Work with local authorities to implement traffic management solutions such as dedicated bus lanes, traffic signal prioritization for buses, and school zone speed limits to reduce congestion and improve bus flow.Mechanical Maintenance: Implement a rigorous maintenance schedule for school buses to prevent mechanical problems. Conduct regular inspections, service checks, and preventive maintenance to identify and address issues before they cause delays. 
Regular Feedback and Evaluation: Gather feedback from drivers, parents, and school staff on bus performance and service quality. Use this feedback to identify areas for improvement and implement changes to enhance efficiency and reliability. 
By implementing these solutions, schools can minimize delays and ensure that school buses run on time, even in the face of heavy traffic, mechanical problems, and other challenges.


## Delay times by bus company and borough

### Delay Times as per Bus Company

<img width="617" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/18af6bd1-1b3f-4d52-856c-a0156518fa8f">


<img width="515" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/460067ed-e67d-4329-be80-0ca854bd0d65">



## Outcomes:

I selected the top 10 Bus Companies with the highest number of delays. Delay times for school buses can vary significantly depending on several factors, including the bus company's policies, operational efficiency, geographical location, traffic conditions, and weather conditions. For example, LEESEL TRANSP CORP (B2192) has 91126 Heavy Traffic delays and less than 600 Mechanical Problems. Though they are the highest, it could be that they operate in the cities that have too much traffic. When looking at PIONEER TRANSPORTATION CORP, you will notice that most of their delays are due to Heavy Traffic. Only less than 3 delays were caused by Mechanical issues. Compared with NEW DAWN TRANSIT, LLC (B2321), the buses in this company have many issues that cause delays.

## Suggestions:

Every bus company needs to be investigated using the provided data to see what causes delays. If the bus company has poor performance issues, it should be replaced by another company that has a proven record of offering a better service. Bus Companies should work with local authorities to implement traffic management strategies if the cause of the delays is due to Heavy Traffic.


### The Delay times as per Boro


<img width="629" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/43b2ee65-5aa0-403f-89ec-57865219b0c7">


<img width="599" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/fc32c8fe-e03b-4a6f-800f-8103b0cb581c">


## Outcomes:

While each borough of New York City has its traffic challenges and characteristics, Manhattan stands out for its severe congestion, particularly in its central districts, while the Bronx and Brooklyn have more varied traffic patterns influenced by factors such as neighborhood density, transportation infrastructure, and industrial activity. Manhattan, being the most densely populated borough, typically experiences heavy traffic congestion, especially during peak commuting hours. Manhattan's narrow streets, numerous intersections, and high volume of vehicular and pedestrian traffic contribute to significant congestion, particularly in areas with major attractions or business districts. The Bronx has a mix of urban and residential neighborhoods, which can result in varying traffic patterns. The Bronx is intersected by several major highways, including the Cross Bronx Expressway and the Bronx River Parkway, which can experience heavy traffic congestion, especially during rush hours. Brooklyn is the most populous borough of New York City and is known for its diverse neighborhoods, each with its own traffic patterns. Some areas, like Downtown Brooklyn and Williamsburg, experience heavy traffic due to commercial and residential density, while others have quieter streets.


## Suggestions:

Local authorities and bus companies should work together to find solutions to these unwanted delays. 


## The correlation between specific days of the week and the frequency of breakdowns or delays

### Breakdown

<img width="322" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/ed80ca8f-1adf-4c1c-bba3-b20885903582">


<img width="440" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/143d240e-94e3-426b-b66c-994e1b6be044">


## Outcomes:

There is a huge spike in bus breakdowns on Monday and this decreases on Tuesday and increases slightly on Wednesday. On Fridays, fewer breakdowns are recorded compared to the rest of the days in the week.  A combination of factors such as weekend maintenance, driver awareness, reduced traffic, driver fatigue, weather conditions, vehicle wear and tear, and maintenance scheduling may contribute to fewer school bus breakdowns on Fridays compared to Mondays in the boroughs. School buses typically undergo maintenance and servicing during the weekend when they are not in use. Buses that have been serviced over the weekend are less likely to experience breakdowns on Mondays compared to buses that have not received maintenance for a longer period. Mondays often see increased demand for transportation services as students return to school after the weekend. This increased demand may put additional strain on school buses, leading to a higher likelihood of mechanical issues or breakdowns.


## Suggestions:

School districts or bus companies should schedule routine maintenance tasks, such as oil changes or inspections, for Fridays or weekends to minimize disruption to daily operations during the week. Regular maintenance can help prevent breakdowns by identifying and addressing potential issues before they become more serious. 


### Running Late

<img width="324" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/48fb9448-cefe-4c27-9949-683c38aca2f7">


<img width="418" alt="image" src="https://github.com/stemla/Bus-Breakdown-and-Delays-Project/assets/170471393/c457275e-9740-4092-b1ad-e44a0d684d18">


## Outcomes:

There is a huge spike in buses running late on Monday and this decreases on Tuesday and increases again on Wednesday. On Fridays, there are fewer delays recorded compared to the rest of the days in the week.  Student attendance may be lower on Mondays due to factors such as illness or extended weekends, leading to fewer students waiting at bus stops. However, on Fridays, student attendance tends to be higher as students are less likely to miss school at the end of the week, which may result in quicker boarding and fewer delays. Overall, a combination of factors such as weekend maintenance, driver familiarity, increased traffic, student attendance, weather conditions, vehicle maintenance issues, and schedule adjustments may contribute to school buses running late on Mondays compared to Fridays in the boroughs.


## Suggestions:

Better planning is needed over the weekend on how things will run on Monday. Parents, schools, and bus companies should communicate on time about any changes that might affect the normal schedule. 


# Conclusion

I have attached the Summarized data (Excel Sheet) with the final product where you will be able to access the process used to arrive to the above results. You will find the data useful as it also shows the type of Pivot Table used. 























