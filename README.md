# Digital Health Project

## Project Description  
This project aims to explore, clean, analyze, and visualize medical costs and healthcare expenses by using an existing dataset. This analysis provides helpful insight for the healthcare industry by comparing how different variables influence medical charges. Researchers, healthcare professionals, and analysts can utilize this dataset to better understand medical expenses, helping to inform healthcare policies and pricing strategies.  

## Dataset Information  
The **Medical Cost Dataset** consists of the following columns:  

- **ID**: Every individual has a unique identifier as ID, ensuring efficient data management and analysis.  
- **Age**: Patient’s age is an important factor as it correlates with medical expenses.  
- **Sex**: The gender of the patient can affect potential healthcare costs due to biological differences.  
- **BMI**: The Body Mass Index (BMI) is an important factor that impacts healthcare costs.  
- **Children**: The number of children covered by medical insurance, influencing family-related medical expenses.  
- **Smoker**: A binary indicator for whether the patient is a smoker or not, as smoking habits significantly affect healthcare costs.  
- **Region**: The geographic region of the patient, helping to understand regional disparities in healthcare expenditure.  
- **Charges**: The medical charges incurred by the patient, serving as the target variable for analysis and predictions.  

## Data Source  
My data source was the **Medical Cost Dataset**, sourced from Kaggle. The dataset is provided by Nandita Pore and is invaluable for anyone analyzing medical costs and expenses.  

[Kaggle - Medical Cost Dataset](https://www.kaggle.com/)  

## User Persona  
The primary user persona for this project is **Healthcare Policy Analysts**, who work for insurance companies or government health agencies. This analysis can help them:  

- Identify high-risk groups of people who contribute disproportionately to healthcare costs.  
- Develop strategies to reduce healthcare costs while maintaining quality care.  
- Discover regional disparities in healthcare expenditure to allocate resources more effectively.  

### Goals of the User Persona:  
1. **Reduce Healthcare Costs**: By identifying factors driving high medical charges, analysts can design targeted interventions (e.g., smoking cessation programs or weight management initiatives).  
2. **Identify High-Risk Groups**: Understanding how variables like smoking status, BMI, and age impact medical costs helps prioritize at-risk populations.  
3. **Inform Policy Decisions**: Insights from the data can guide the development of policies that promote equitable and cost-effective healthcare.  

## Key Insights from Analysis is   

### Impact of Smoking on Charges 
Across all four regions (**Northeast, Northwest, Southeast, and Southwest**), **smokers consistently have much higher mean and median charges** compared to non-smokers.  
- In the **Southeast**, smokers have a **mean charge of $34,845**, while non-smokers pay an average of **$8,032**—a difference of over **4x**.  

### Impact of BMI on Charges 
- **Patients with higher BMI values are shown to have higher medical charges**. This emphasizes the importance of weight management initiatives.  
- **Underweight patients have the lowest mean charge ($8,852) and median charge ($6,759)**.  
- **Obese individuals experience the highest medical costs**, with a **mean charge of $15,460** and a **median charge of $9,880**.  

### Impact of Age on Charges   
- **Older patients generally face higher medical expenses**, suggesting a need for **preventive care programs targeting older demographics**.  
- **Young Adults (18-34 years old):** Mean charge **$9,673**, median charge **$4,074**.  
- **Middle-Aged (35-49 years old):** Mean charge **$13,744**, median charge **$8,282**.  
- **Seniors (50-64 years old):** Mean charge **$17,902**, median charge **$12,629**.  

### Regional Disparities  
- **Medical charges vary across regions**, indicating differences in **healthcare access, pricing, or population health**.  
- The **Southeast region** has the **highest average charges for smokers ($34,845) and the lowest for non-smokers ($8,032)**.  
- The **Northwest and Southwest regions** have the **lowest non-smoker charges (~$8,000)**.  

These insights provide actionable and valuable information for healthcare policy analysts to design targeted interventions and allocate resources effectively.  

## Technologies Used  
- **R**: Language for statistical computing and graphics.  
- **Shiny**: Framework for building interactive web applications with R.  
- **ggplot2**: A data visualization package for creating plots and charts.  
- **dplyr**: A package for data manipulation and cleaning.  

## Links  
- **GitHub Repository**: [Medical Cost Analysis](https://github.com/Mehrana-Ziari/Medical-Cost)  
- **Live Shiny App**: [Medical Cost Dashboard](https://fatemehziari.shinyapps.io/med_cost/)
  
# Installation & Setup
 Follow these steps to set up and run the application:

### 1. Clone the Repository
```sh
git clone https://github.com/Mehrana-Ziari/Medical-Costs-Analysis.git
cd Medical-Costs-Analysis
```

### 2. Install Required R Packages
Open R or RStudio and run:
```r
install.packages(c("shiny", "ggplot2", "dplyr"))
```

### 3. Run the Shiny Application
```r
shiny::runApp("path/to/your/app")
```

### 4. Open in Browser
Navigate to the displayed URL in your browser to interact with the visualizations.

# Usage
 After opening the shiny app, you can:
- Select a region from the dropdown menu to filter the data by region.
- Filter the smokers in the visualizations by using the checkbox.
- Explore various data visualizations such as scatter plots and box plots which help to analyze the relationships between medical charges and our different variables like age, BMI, smoking status, and region.
