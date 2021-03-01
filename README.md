# Kickstarting with Excel

## Project Overview 
Determine successful characteristics for U.S. plays with a goal of $10,000 in funding. 

## Analysis and Challenges
### Overview
Identify specific factors for a successful crowdfunding campaign. The link to the Excel file and a chart and graph (below) were used to more easily visualize the data. 

#### Theater Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/79054284/109452073-8b4dd300-7a14-11eb-80d2-11b8cd9b0428.png)


#### Outcomes Based on Goal

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/79054284/109451322-ccdd7e80-7a12-11eb-8d4d-de1566d17039.png)

<!--
The original dataset is represented in columns A-N on the "Kickstarter" page. Modifications and additions were made to more easily understand the data. 
* The `outcomes` column was shaded to more easily identify the outcomes as Successful/green, Failed/pink, Canceled/yellow, and Live/blue. 
* The following columns were added after column N for additional data:
  - `Percentage_Funded` was added as column O and shaded to indicate which campaigns met their goals
  - `Average_Donation` was added as column P
  - the original `Category and Subcategory` were split into 2 separate columns, Q & R, respectively
  - `launched_at` and `deadline` date columns were converted to US format and labeled as `Create_Date_Convert` and `End_Date_Convert` in columns S and T, respectively
  - the `Year` column was added in column U and was pulled from the `Create_Date_Convert`
-->

### Analysis of Outcomes Based on Launch Date:
The first step began by creating a pivot table and filtering that table by `Parent_Category` of Theater and the Subcategory of Plays.  



<!--
1.3.1 FINDING: If we filter for only the United States campaigns, we will find that there were 525 successful theater Kickstarters.
1.3.2 FINDING: We have found that while there are only a total of 604 Kickstarter campaigns for plays in Great Britain, the "theater" category is the most successful.
1.3.3 FINDING: The month that launched the most successful Kickstarter campaigns was May. However, January, June, July and October all had roughly the same number of failed campaigns launched. This can be determined by examining the points along the trend lines of the chart. As you hover over each point with your mouse pointer, a tooltip appears with the corresponding information.
-->



### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?



