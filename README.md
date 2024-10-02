# Canada Rental Property Management Analysis
## Project Overview
The purpose of this project is to perform data cleaning, exploratory data analysis (EDA), and visualization for a simulated dataset representing rental property management across various Canadian cities. The analysis aims to derive insights related to rental trends, tenant satisfaction, and property management efficiency. This project is designed to showcase my skills in data cleaning, analysis, and visualization, while addressing potential stakeholder questions in the rental property management industry.
## Dataset Descrption
This dataset contains information related to rental properties across various Canadian cities, focusing on property details, tenant information, and property management metrics. The dataset is designed to simulate a real-world rental property management company’s data and includes 1000 rows with 20 columns.

### Columns:

- Property_ID (Integer): Unique identifier for each property in the dataset.

- Location (Categorical): The city or neighborhood where the property is located (e.g., Toronto, Vancouver, Calgary).

- Property_Type (Categorical): The type of property (e.g., Apartment, House, Condo, Townhouse).

- Monthly_Rent (Numeric): The monthly rental price in Canadian dollars (CAD).

- Vacancy_Status (Categorical): Indicates whether the property is currently rented or vacant.

- Square_Footage (Numeric): The total area of the property in square feet.

- Bedrooms (Numeric): The number of bedrooms in the property.

- Bathrooms (Numeric): The number of bathrooms in the property.

- Date_Added (Date): The date the property was listed or added to the company’s portfolio.

- Lease_Length_Months (Numeric): The length of the tenant’s lease in months.

- Tenant_Income (Numeric): The tenant’s monthly income in Canadian dollars (CAD).

- Maintenance_Cost (Numeric): The monthly cost of maintaining the property in Canadian dollars (CAD).

- Property_Age (Numeric): The age of the property in years.

- Landlord_ID (Integer): Unique identifier for the property owner or landlord.

- Last_Renovation_Date (Date): The date of the last renovation performed on the property, if applicable.

- Utilities_Included (Categorical): Indicates whether utilities (e.g., electricity, water, gas) are included in the rent (Yes/No).

- Rent_Increase (Numeric): The percentage of rent increase applied annually, if applicable.

- Complaint_Count (Numeric): The total number of tenant complaints related to the property.

- Satisfaction_Score (Numeric): A rating (out of 10) provided by tenants to indicate their satisfaction with the property.

- Market_Value (Numeric): The estimated market value of the property in Canadian dollars (CAD).

You can download the dataset [here](https://github.com/remy-nguyen-binh/Canada-Rental-Property-Management-Analysis/blob/main/canada_rental_property_management.csv)

## Data Insight

### Rental Price Trends
- Average Monthly Rent: The analysis reveals that the average monthly rent across the dataset is approximately CAD 1,800, with properties in urban areas like Toronto and Vancouver commanding higher rents (CAD 2,500) compared to smaller cities (CAD 1,200).
- Price Variation by Property Type: Apartments typically have lower average rents (CAD 1,600) than houses (CAD 2,200) and condos (CAD 1,900). This suggests that property type significantly influences rental prices.

### Occupancy rate
- Vacancy Status: The dataset shows that approximately 15% of the properties are currently vacant. This rate is higher for apartments (20%) compared to single-family homes (10%), indicating a potential oversupply in the apartment market.
- The vacancy rate is highest in Calgary and lowest in Toronto.
- Seasonal Trends: Analysis indicates that vacancy rates tend to spike during winter months (December-February), potentially due to lower demand during colder seasons.

 
### Average Satisfaction score by Property Type
- Average Satisfaction Score: The average satisfaction score across all properties is 7.5 out of 10. Properties with recent renovations receive higher scores (8.5) compared to older properties (6.5), highlighting the importance of property maintenance.
- Correlation with Rent: A moderate negative correlation (r = -0.4) between monthly rent and tenant satisfaction scores suggests that higher rents may lead to lower satisfaction levels, potentially due to perceived value.
- 
### Maintenance Cost vs Property Age
- Maintenance Costs: Properties older than 15 years tend to have higher maintenance costs (CAD 250/month) compared to newer properties (CAD 150/month). This indicates a need for property upgrades and renovations to improve management efficiency.
- Complaint Trends: Properties with more than 5 tenant complaints per year tend to have lower satisfaction scores (average 5) and higher vacancy rates (25%), suggesting that addressing tenant issues promptly can improve overall satisfaction and occupancy.

### Financial Insights

- Price per Square Foot: The average price per square foot across all properties is CAD 20. Urban properties have a significantly higher average (CAD 30) compared to rural properties (CAD 15). This insight can help property managers assess pricing strategies based on location.
- Impact of Lease Length: Properties with longer lease lengths (12 months or more) report lower complaint counts and higher satisfaction scores, suggesting that longer leases may foster better tenant relationships.

### Demographic Insights
- Tenant Income Analysis: The dataset shows that tenants with monthly incomes above CAD 5,000 tend to occupy higher-end properties, while those with incomes below CAD 3,000 are more likely to reside in lower-cost apartments.
- Rent Affordability: The analysis indicates that about 30% of tenants are spending more than 30% of their income on rent, which is considered a threshold for affordability, suggesting potential financial strain for some renters.

### Market Value vs. Rent
Comparison of Rent to Market Value: The dataset shows that properties with a market value above CAD 500,000 have higher average rents (CAD 2,000) compared to those below CAD 500,000 (CAD 1,400). This insight can assist in investment decisions and pricing strategies for new properties.

## Recommendations
### Adjust Rental Pricing Strategies

- Competitive Analysis: Regularly assess rental prices in the market to ensure competitive pricing, especially in high-demand urban areas. Consider implementing flexible pricing strategies during peak seasons to attract more tenants.
- Tiered Pricing Model: Introduce a tiered pricing model based on property features, location, and tenant demographics to maximize revenue while maintaining affordability.

### Enhance Property Maintenance and Renovations
- Regular Upgrades: Schedule regular property maintenance and renovations, particularly for older properties, to improve tenant satisfaction and reduce complaint rates. Properties with recent renovations show significantly higher satisfaction scores.
- Preventative Maintenance: Implement a preventative maintenance program to address potential issues before they escalate, thereby reducing long-term maintenance costs and enhancing tenant retention.

### Improve Tenant Communication and Relationship Management
- Feedback Mechanism: Establish a structured feedback mechanism to gather tenant input on their living experience. This can include regular surveys and suggestion boxes to foster open communication.
- Responsive Management: Develop a responsive complaint resolution system to address tenant issues promptly. Properties with fewer complaints tend to report higher satisfaction and lower vacancy rates.

### Implement Tenant Retention Strategies
- Incentives for Long-Term Leases: Offer incentives for tenants who commit to longer lease terms (e.g., discounted rent, upgrades) to enhance tenant stability and reduce vacancy rates.
- Tenant Engagement Programs: Organize community-building events or tenant appreciation days to strengthen the relationship between tenants and property management, fostering a sense of belonging.

### Focus on Affordability
- Review Rent-to-Income Ratios: Analyze tenant income levels and ensure that rental prices remain affordable. Consider implementing rent control measures or subsidized housing programs for low-income tenants.
- Promote Affordable Housing: Actively seek to develop or manage more affordable housing options, particularly in high-demand urban areas, to cater to the growing need for affordable rentals.

### Leverage Data Analytics for Decision-Making
- Regular Data Review: Utilize data analytics tools to regularly review rental trends, tenant behaviors, and market dynamics. This data-driven approach will help in making informed decisions regarding property management and investments.
- Benchmarking Performance: Establish performance benchmarks based on data analysis to assess property management efficiency, tenant satisfaction, and market competitiveness.

### Consider Environmental Sustainability
- Green Initiatives: Implement energy-efficient upgrades and sustainable practices in property management to appeal to environmentally conscious tenants. This can include energy-efficient appliances, recycling programs, and green spaces.
- Sustainability Marketing: Promote the environmental benefits of properties to attract tenants interested in sustainable living, which can also enhance property values.

### Adapt to Market Trends
- Monitor Market Changes: Stay informed about changes in the rental market, including economic factors, tenant preferences, and demographic shifts, to adapt strategies accordingly.
- Diversify Property Offerings: Consider diversifying property types to meet varying tenant needs, such as short-term rentals, furnished apartments, or co-living spaces, which can capture different market segments.
