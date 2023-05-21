![electric vehicle](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/e964ad9c-7f6b-42cb-a386-5adb4d6d9a3a)

# Electric Vehicle Title and Registration Activity


### Author
-[@zsoltka](https://github.com/Zsoltka)

## Tool technologies used
- Excel
- Navicat
- Power BI

## Data Cleansing

The original raw dataset comprised 35 columns and 681,315 rows. I performed data cleaning and restructuring in Excel, following these steps:

- I identified and removed duplicates across all 35 columns. A total of 26 duplicate rows were found and eliminated after ensuring their absence wouldn't interfere with subsequent analysis. Inconsistencies in data, including typos, blank spaces, and punctuation errors, were addressed. The handling of NULL values in crucial columns was thoughtfully considered.
- I divided the data into several tables for more manageable manipulation and analysis. After thorough examination, I created the following tables (the image shows the tables after there were uploading them in Navicat): 
 
<img src="https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/7816056d-03a5-48da-bae8-38ecfc2d4e91" width="700">

## Project summary

This project engages in an in-depth data analysis of electric vehicle title and registration activity in Washington state, based on the dataset found at https://catalog.data.gov/dataset/electric-vehicle-title-and-registration-activity.


## Questions to Answer
**1. Electric Vehicle Adoption:** Analyzing the number of electric vehicles registered to identify trends in adoption over time. 

**2. Electric Vehicles by Alternative Fuel:** Showing the proportion of electric vehicle by Clean Alternative Fuel Vehicle Type to determinate the popularity by engine type.

**3. Electric Vehicle Sales by Make and Model:** Showing the distribution of electric vehicle sales by make and model to determine the most popular options among buyers. 

**4. New vs. Used Electric Vehicle Sales:** Comparing the number of new versus used electric vehicle sales.

**5. Electric Vehicle Distribution by County and City:** Creating a heatmap or a geographical representation of electric vehicle registrations by county and city to identify areas with higher adoption rates. 

**6. Electric Vehicle Use:** Breaking down the registered electric vehicles by their primary use (personal, commercial, etc.) to understand how they are being utilized.

**7. Average Electric Range by Make and Model:** Comparing the average electric range of different makes and models to identify which vehicles offer the best range.

**8. Impact of Incentives on Sales:** Investigating the relationship between incentive eligibility (based on the electric range, sale date,) and the number of electric vehicles sold.

**9. Electric Vehicle Sales by Legislative District and Electric Utility:** Analyzing the distribution of electric vehicle sales across legislative districts and electric utility service areas to identify areas with stronger support for clean transportation initiatives.

## Data analysis

1. From our observations, it's evident that the allure of electric vehicles is steadily growing with each passing year. This upward trend can be attributed to an increasing number of automakers venturing into this industry. As more players enter the market, technology continues to evolve, leading to an expanded assortment of electric vehicle options available for consumers. This broader range provides potential buyers with more choices, catering to various preferences and needs.

![image](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/c468e501-46f0-492c-b861-e948ace47fe8)
![image](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/35fbe292-07cc-46b1-b07a-aa2a2a89fb66)


Furthermore, our data indicates a strong preference among buyers for new electric vehicles. This inclination not only demonstrates the general population's enthusiasm for cutting-edge technologies but also suggests that the pace of advancements in this field is sufficient to stimulate and maintain interest. The preference for new vehicles is a promising sign, as it implies a readiness to embrace the ongoing evolution in automotive technology, specifically in the realm of electric vehicles. This, in turn, could contribute to further advancements and increased adoption rates, propelling the electric vehicle industry forward.


2. The data at hand reveals a distinct preference among consumers for battery-operated electric vehicles. These vehicles, which run solely on electricity stored in their batteries, constitute the majority of the sales. In fact, plug-in hybrid vehicles - those capable of using both electricity and conventional fuels - account for a mere 31% of the total vehicles sold. This points to a clear trend towards fully electric vehicles, reflecting consumers' growing consciousness about the environment and possibly the improving range and infrastructure for such vehicles.

![image](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/08035df9-7be8-4dd2-bff1-75671b0f52c3)

An interesting outlier in the data is the minimal adoption of hydrogen-powered vehicles. During the period under analysis, a scant total of two hydrogen-powered vehicles were purchased. This number is negligible when compared to the sales of other types of electric vehicles. Factors contributing to this low uptake could include the lack of refueling infrastructure for hydrogen vehicles, their high cost, or simply a lack of awareness about this technology among consumers. Further analysis would be needed to pinpoint the precise reasons, but the current data underscores a strong preference for battery-operated electric vehicles.

3. The collected data sheds light on consumer preferences in the electric vehicle market, ranking models by popularity. According to this data, the most sought-after electric vehicle, both by make and model, is the Nissan - Leaf, capturing 18.11% of the market share. This is closely followed by several Tesla models. The Tesla - Model 3 takes second place with 16.34%, trailed by the Tesla Model Y at 11.79%, and the Tesla - Model S securing 6.84% of the market. The Tesla - Model X comes in at seventh place, contributing 3.47% to the market share. Thus, excluding the leading Nissan - Leaf, Tesla models appear to dominate the list of most popular electric vehicles.

![image](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/c6fa84a4-11b9-411a-9459-3184ac33705f)

When we shift our focus to consider only the car's make, Tesla takes the lead with a significant 38.44% market share, making it the most popular brand among electric vehicle buyers. The brands that follow in popularity include Chevrolet, Ford, and BMW, among others. This data underscores Tesla's strong brand presence in the electric vehicle industry, backed by a suite of models that cater to diverse customer needs.

4. The data provides a clear snapshot of how electric vehicles are primarily utilized. An overwhelming majority of these vehicles, combining Passenger and Medium-Speed Electric Vehicles, are used for personal purposes, which constitutes 97.68% of the total primary usage. This high percentage underscores the appeal of electric vehicles to individual consumers for their daily commuting needs, leisure travel, or other personal uses.

![image](https://github.com/Zsoltka/Electric-Vehicle-Title-and-Registration-Activity/assets/133663142/0388f53a-74e6-4c67-aa1a-2aa5caa98a52)

The data provides a clear snapshot of how electric vehicles are primarily utilized. An overwhelming majority of these vehicles, combining Passenger and Medium-Speed Electric Vehicles, are used for personal purposes, which constitutes 97.68% of the total primary usage. This high percentage underscores the appeal of electric vehicles to individual consumers for their daily commuting needs, leisure travel, or other personal uses. Similarly, vehicles used primarily for farming or other agricultural purposes might be exempted from certain regulations or licensing requirements in some areas. This would need additional analysis, perhaps involving data from other databases. This further investigation could offer deeper insights into the diversity of electric vehicle applications beyond personal use.
