# Case Study: Yacht and Boat Sales Website Analysis
*This project was completed in partial fulfillment of the Google Data Analysis Professional Certificate*

## Phase 1: Stakeholder Identification and Business Objectives:
The client represents a yacht and boat sales website. They have tasked me with analyzing their data to achieve the following objectives:

* Understand customer preferences and behavior on their website.
* Identify key factors influencing boat and yacht sales.
* Provide insights and recommendations to optimize the website's user experience and sales strategies.

### Key Stakeholders
1. **Customers:** These are potential boat buyers and yacht enthusiasts. Previous customers who may provide testimonials or referrals. Customer service representatives who interact with customers.
2. **Boat Manufacturers and Dealers:** Suppliers of the boats and yachts listed on the website. Dealerships or manufacturers who use the platform for sales.
3. **Website Development Team:** Developers, designers, and IT professionals who are responsible for maintaining and updating the website.
4. **Marketing and Sales Team:** Sales and marketing professionals who are responsible for promoting listings and driving sales. Digital marketing experts and SEO specialists.
5. **Management and Executives:** Senior management and executives who oversee the strategic direction of the business. Decision-makers who allocate resources to the website.

## Phase 2: Preparing the data
  The data used in this project was from the [Boat Sales dataset](https://www.kaggle.com/datasets/karthikbhandary2/boat-sales) (CC0: Public Domain, dataset made available through Kaggle). This Kaggle dataset contains 9888 rows and 10 columns of data. It has details of the boats regarding the year it was built the type of boat, the price, the number of views in the last 7 days, and much more. Upon completion of this project, it was noted that there are no citations mentioned and the dataset was last updated 2 years ago. 

## Phase 3: Data Cleaning and Manipulation
Cleaning and preprocessing the data was done to handle missing values, outliers, and inconsistencies. The location column consisted of a string comprised of the country, city/town, area, and in some cases the area code. I split the contents of this column by country and town/city. 
I proceeded to remove duplicates, and 34 duplicate rows were found. I trimmed white space from 34 cells in total. All blank cells were replaced with null values.

## Phase 4: Exploratory Data Analysis
To understand the distribution of key variables and identify patterns, SQL was used as the primary tool for analysis. This choice was based on the scalability, performance, and data manipulation functions that SQL has to offer. For the analysis, the following questions were asked:

### Customer Behavior Insights
1. Which boat types receive the most views? Are there certain boat types that attract more interest than others?
2. What is the average price range for boats on the website? Are there price trends based on boat type or material used?
3. Which countries are the website's visitors primarily from? Are there geographic trends in boat interest?
4. Is there a correlation between the number of views a boat listing receives and the country of the visitor viewing it?

### Market Trends and Preferences
1. Which manufacturers' boats are most frequently viewed on the website? Are there specific manufacturers that are more popular among buyers?
2. Are there material preferences among buyers, such as fiberglass, wood, or aluminum? Does material affect pricing or popularity?
3. Do larger boats receive more views or have higher price tags? Are there size preferences based on boat type?
4. Is there a correlation between the year a boat was built and its price or popularity? Are older or newer boats more sought after?

### Website Performance:
1. Do visitors from specific countries tend to engage more with the website?
2. Are there factors (e.g., boat type, price, location) that significantly influence the number of views a listing receives?

## Data Visualization
## Key Findings
## Limitations and Conclusion
## Recommendations


