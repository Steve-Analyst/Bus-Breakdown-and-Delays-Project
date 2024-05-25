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



























# Conclusion

I have attached the Summarized data (Excel Sheet) with the final product where you will be able to access the process used to arrive to the above results. You will find the data useful as it also shows the type of Pivot Table used. 























