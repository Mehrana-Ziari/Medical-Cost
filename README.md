	Project Description
This project aims to explore, clean, analyze, and visualize medical costs and healthcare expenses using a dataset. By investigating the dynamics within the healthcare industry, this analysis provides insights into factors influencing medical charges. Researchers, healthcare professionals, and analysts can utilize this dataset to better understand medical expenses, helping to inform healthcare policies and pricing strategies.
	Dataset Information
The Medical Cost Dataset consists of the following columns:
•	ID: A unique identifier assigned to each individual record, ensuring efficient data management and analysis.
•	Age: The age of the patient, a crucial demographic factor often correlating with medical expenses.
•	Sex: The gender of the patient, providing insights into potential cost variations based on biological differences.
•	BMI: The Body Mass Index (BMI) of the patient, indicating their weight status and potential impact on healthcare costs.
•	Children: The number of children or dependents covered under the medical insurance, influencing family-related medical expenses.
•	Smoker: A binary indicator for whether the patient is a smoker or not, as smoking habits significantly affect healthcare costs.
•	Region: The geographic region of the patient, helping to understand regional disparities in healthcare expenditure.
•	Charges: The medical charges incurred by the patient, serving as the target variable for analysis and predictions.
	Data Source
This project uses the Medical Cost Dataset sourced from Kaggle. You can access the dataset here:
Kaggle - Medical Cost Dataset
The dataset is provided by Nandita Pore and is invaluable for anyone aiming to analyze medical costs and expenses.
	User Persona
The primary user persona for this project is a **Healthcare Policy Analyst** working for an insurance company or government health agency. This user is responsible for:  
- Identifying high-risk groups that contribute disproportionately to healthcare costs.  
- Developing strategies to reduce healthcare expenses while maintaining quality care.  
- Understanding regional disparities in healthcare expenditure to allocate resources effectively.  

	Goals of the User Persona:
1. Reduce Healthcare Costs: By identifying factors that drive high medical charges, the analyst can design targeted interventions (e.g., smoking cessation programs or weight management initiatives).  
2. Identify High-Risk Groups: Understanding how variables like smoking status, BMI, and age impact medical costs helps the analyst prioritize at-risk populations.  
3. Inform Policy Decisions: Insights from the data can guide the development of policies that promote equitable and cost-effective healthcare.  
	Key Insights from Analysis
The analysis revealed several key insights that are critical for decision-making:  
1. Impact of Smoking: Smokers incur significantly higher medical charges compared to non-smokers. This highlights the need for targeted smoking cessation programs to reduce healthcare costs.  
2. BMI and Medical Charges: Patients with higher BMI values tend to have higher medical charges, emphasizing the importance of weight management initiatives.  
3. Age and Charges: Older patients generally face higher medical expenses, suggesting a need for preventive care programs targeting older demographics.  
4. Regional Disparities: Medical charges vary across regions, with some areas showing consistently higher costs. This could indicate differences in healthcare access, pricing, or population health.  
These insights provide actionable information for healthcare policy analysts to design targeted interventions and allocate resources effectively.  
	Technologies Used
This project leverages the following technologies:
•	R: A language for statistical computing and graphics.
•	Shiny: A framework for building interactive web applications with R.
•	ggplot2: A data visualization package for creating plots and charts.
•	dplyr: A package for data manipulation and cleaning.
	Links 
	to GitHub Repo: https://github.com/Mehrana-Ziari/Medical-Cost
	to Shiny Application: https://fatemehziari.shinyapps.io/med_cost/
	Installation & Setup
1.	Clone the repository:
git clone https://github.com/Mehrana-Ziari/Medical-Costs-Analysis.git
2.	Install the required R packages (if they are not installed yet):
install.packages(c("shiny", "ggplot2", "dplyr"))
3.	Run the Shiny application:
shiny::runApp("path/to/your/app")
4.	Navigate to the UI in your browser to interact with the visualizations.
	Usage
Once the Shiny app is up and running, you can:
•	Select a region from the dropdown menu to filter the data by region.
•	Highlight smokers in the visualizations using the checkbox.
•	Explore various data visualizations such as scatter plots and box plots to analyze the relationships between medical charges and variables like age, BMI, smoking status, and region.
