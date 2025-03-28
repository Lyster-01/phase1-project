# PHASE 1 PROJECT

 ## AIRCRAFT RISK EVALUATION

 ## OVERVIEW
Our company is expanding in to new industries to diversify its portfolio. The company is interested in purchasing and operating airplanes for commercial and private enterprise  which will be a key step in our growth strategy. To align this expansion with our strategic goals, we will rely on data-driven insights to inform our decisions. A thorough risk assessment will conducted using aviation accident data spanning from 1993 to 2023. The analysis aims to identify aircraft models and makes with a higher likelihood of severe accidents or operational failures, determine locations that pose higher risks for aircraft operations, assess the optimal number of engines required for stable and safe flights and analyze the Total fatal injuries by the purpose of flight.

## BUSINESS QUESTIONS
  1. Which flight operations have the highest risk of fatal injuries?
  2. What aircraft is safer and less likely to get accidents?
  3. Which are the locations safe for aircraft navigation?
  4. What are the optimal number of engines sufficient for ensuring the stability and safety of aircraft operations?
 
## BUSINESS UNDERSTANDING
Our company is expanding into the aviation industry, seeking to purchase and operate aircraft for both commercial and private enterprises. To ensure this venture is both safe , we need to assess the risks associated with different aircraft models, operational environments, and structural designs. Specifically, the objectives of this analysis are :
1. Analyze the Total fatal injuries by the purpose of flight.

2. Identify aircraft models and makes with a higher likelihood of severe accidents or operational failures.

3. Investigate for the locations that have historically proven risky for aircraft operations, highlighting potential geographic safety concerns.

4. Determine the number of engines sufficient for ensuring the stability and safety of aircraft operations.

 By achieving these objectives, we will be able to select aircraft models and operational strategies that align with the company’s goals of safety and  reliability minimizing potential risks as we enter this new industry.

## DATA UNDERSTANDING.
The NTSB aviation accident database contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters. This dataset drawn from kaggle initially had 31 columns and 88889 rows.The dataset provides insights into trends of accidents and incidents across different aircraft types , locations  among other key attributes. This dataset is important for investigating safety concerns,potential areas for risk mitigation in aviation operations.

## DATA CLEANING:
The Python libaries imported for analysis were matplotlib,pandas and numpy. The data was cleaned using the Visual Studio code editor.Below were the steps followed for data cleaning

 -Importing the relevant python libraries.
 -Loading and reading the CSV file.
 -Inspecting and understanding the data.
 -Data Cleaning.
 -Checked for erroneous values
 -Dropped all the irrelevant columns and those that had alot of missing values 
 -Filled in  the missing values for both the numerical columns  and categorical columns.
 -Then we stripped all the white spaces.
 -Removed the '.' in the column names and replaced with '_'
 -Added a few other columns
 After the above steps the cleaned data was saved to a csv file.
 

## DATA ANALYSIS
The data was analyzed using the VSCode code editor, with essential libraries such as matplotlib and pandas being imported . The analysis focused on columns like Location, Investigation_Type,Number_of_Engines and other columns that were added like Engine_categories, and Accident_Numbers for easier visualization on tableau. Visualizations were created using matplotlib within the ipynb file, while additional visualizations shown below, were developed using Tableau.

##### Graphical representation using a pie chart for the proportions of accidents and incidents.
The following is a graphical representation using a pie chart to show the proportions of accident and incident investigation types. This visualization offers a clear comparison of the two categories that effectively display proportions, making it straightforward to convey that most investigation types are accidents which takes 95.6% of the investigation type and incidents take 4.4% of the investigation type thereby reducing any potential confusion when interpreting the results.
C:\Users\Lyster\Documents\Phase1_Project\images\image.png
![alt text](image.png)

##### Objective 1: To analyze the Total Fatal Injuries by the Purpose of Flight.
The figure below is a graphicel representation of the Total Fatal by the purpose of flight.
![alt text](image4.png)


From the above figure we can see the personal flight purpose is more prone to fatal accidents.

##### Objective 2:Identify aircraft models and makes with a higher likelihood of  accidents 
This  objective will be addressed using two visualizations for  to identify the number of accidents per make and per model. To be able to achieve this,we grouped and also got the counts the number of accidents based on the Make and Model of the aircraft, then sorted the results in descending order.

   ##### Objective 2.1:Identify aircraft  make with a highest likelihood of  accidents 
The figure below is a graphical representation that shows the aircraft make with the highest number of accidents .
![alt text](image1.png)

From the figure plotted above it can be clearly seen that the Make with the most accident occurences is Cessna  with 26793 number of accidents  followed by Piper with 14684 number of accidents.


   ##### Objective 2.2 :Identify aircraft  models with the highest likelihood of  accidents 
The figure below is a graphical representation that shows the aircraft models with the highest number of accidents .
![alt text](image1.2.png)

From the figure plotted above it can be clearly  that the Model with the most accident occurences is the 152 model with 2348 number of accidents  followed by 172 model with 1744 number of accidents.

##### Objective 3: Investigate the  locations that have historically proven risky for aircraft operations, highlighting potential geographic safety concerns.
The figure below aimed to pinpoint the locations that have historically risky for aircraft operations.This would be visualized by showing the locations with high accident occurrences.
![alt text](image2.png)

The figure above shows Anchorage as the most risky location for aircraft operations and Orlando and Chicago being among the locations safer for aircraft operations.

##### Objective 4: Determine the number of engines sufficient for ensuring the stability and safety of aircraft operations.
The graphical representation aims to show the number of engines that are sufficient for ensuring stability and safety of aircraft operations. This will be achieved by checking for  count of engines in the  aircraft that had accidents.
![alt text](image3.png)

 From the figure we can clearly see that the Aircrafts with more than 4 engines have lesser occurrences of accidents.This could also mean that those aircrafts with less than four engines have a greater probability of accidents.

 ## Findings
1.From the graphical representation above we can see that the accidents takes 95.6% of the investigation done while the incidences take 4.4% of the investigation done.

2.The Model with the most accident occurences is the 152 model with 2348 number of accidents  followed by 172 model with 1744 number of accidents.

3.The Make with the most accident occurences is Cessna  with 26793 number of accidents  followed by Piper with 14684 number of accidents.


4.Anchorage is  the most risky location for aircraft operations while Orlando and Chicago are among the locations safer for aircraft operations.

5.The personal flight purpose is more prone to fatal accidents with a total of 18762 Total Fatal injuries.


6.We can see that the aircrafts with more than 4 engines have lesser occurrences of accidents. This would also mean that the aircrafts with less than four engines have a greater probability of accidents. 

## Conclusions:
 1.The personal flight purpose is more prone to fatal accidents.
 2.The aircraft model with the highest number of accidents is the 152 model, followed by the 172 model. 
 
 3.In terms of aircraft make, Cessna has the most accident occurrences, followed by Piper.  
 4.Geographically, Anchorage is identified as the riskiest location for aircraft operations, while Orlando and Chicago are comparatively safer.
 5.Aircraft with more than four engines show fewer accidents, suggesting that opting for planes with four or more engines may reduce the likelihood of accidents.

## Recommendations
1.Prioritize and focus on the commercial and business flight operations where regulatory oversight and safety protocols must exist.
2.Avoid aircraft makes and models that have high accident rates, including brands like Cessna and Piper.

3.Locations with a high risk of accidents should be avoided.This can help airlines to ensure the stability and safety of their aircraft operations.

4.Opting for aircraft with four or more engines, which is considered the optimal number for stable and safe flights, can help minimize the risk of accidents.


#### Tableau link for story
https://public.tableau.com/views/Book5_17431069873860/Visualizationsaddressingobjectives?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link







