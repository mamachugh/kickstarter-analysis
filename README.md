# Kickstarting with Excel

## Project Overview 
### Identify specific factors for a successful crowdfunding campaign. Specifically, determine outcomes in relation to their launch dates and funding goals.

## Analysis and Challenges
### The original dataset is represented in columns A-N on the "Kickstarter" page. Modifications and additions were made to understand the data more easily. 
* The `outcomes` column was shaded to more easily identify the outcomes as Successful/green, Failed/pink, Canceled/yellow, and Live/blue. 
* The following columns were added after column N for additional data:
  - `Percentage_Funded` was added as column O and shaded to indicate which campaigns met their goals
  - `Average_Donation` was added as column P
  - the original `Category and Subcategory` were split into 2 separate columns, Q & R, respectively
  - `launched_at` and `deadline` date columns were converted to US format and labeled as `Create_Date_Convert` and `End_Date_Convert` in columns S and T, respectively
  - the `Year` column was added in column U and was pulled from the `Create_Date_Convert`
###  Analysis of data began by creating a pivot table and filtering that table by `Parent_Category`. 

### (Analysis of Outcomes Based on Launch Date)

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?



