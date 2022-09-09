# team_12_project

## Topic: Stray Animals in Sonoma County
- Gather insights about stray animals found in Sonoma County:
  - Understand how different factors like location, weather, etc. can impact the volume of stray animals found in Sonoma County. 
  - Understand reasons of the outcome decisions made for the stray animals
- Use machine learning to predict outcomes of stray animals found in Sonoma County

Reason 
- We want to understand the factors that lead to the decisions of stray animals found in Sonoma County

## Repo Changes
Changes to repository require pull request and team member review before being pushed to main. Comments will be used to communicate adjustments or clarifications on proposed changes.

## Github Branches
Each team member has at least one branch with multiple commits.

![Branches](https://user-images.githubusercontent.com/66224990/186725561-e3481f2a-fa80-4254-9b20-f83e139b2aab.png)

## Data Sources
- Sonoma County Shelter Intake - https://data.sonomacounty.ca.gov/Government/Animal-Shelter-Intake-and-Outcome/924a-vesw/data
- US Census Sonoma County Median Income - https://censusreporter.org/profiles/05000US06097-sonoma-county-ca/
- Sonoma County Food Facilities - https://data.sonomacounty.ca.gov/Health/Food-Facility-Inspections/8r44-w5qd 
- Sonoma County Weather - https://cesonoma.ucanr.edu/about/weather/ 
- Sonoma Fire Data - https://gis.data.cnra.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all/explore?layer=0&location=37.442493%2C-118.992700%2C6.97&showTable=true

## Database Schema
We propose linking datasets by Zip Code
![QuickDBD_All_Data](https://user-images.githubusercontent.com/66224990/188485447-415d4683-e4a8-4a22-be68-3f1907f1dd54.png)

## Technology Used
- Workspace
  - Github
- Machine Learning
  - Model: tbd
- Visualization Tool
  - Tableau
- Database
  - pgAdmin
- Tools
  - Jupyter Notebook
    - Python; Pandas
  - Google Slides
  - Communication 
    - Slack
    - Zoom
    - Github

## Machine Learning
The aim of the Machine Learning algorithm is to predict outcomes of stray animals found in Sonoma County. The model is to be used to assess the probability of stray dogs and cats to be adopted or returned to owner.  
The model selected is GradientBoostingRegressor which and it is able to predicts animals outcome with a 11% MSE.  
See Google Slides Presentation link below for more details.  

## Google Slides Presentation
https://docs.google.com/presentation/d/17mCjE0kkGxOOtFdaLy7aAWzhwDQJiakgXJcc1TdWPjY/edit#slide=id.g1463f604542_3_1

## Tableau Data Visualiztion
Analysis of Sonoma Shelter Data: https://public.tableau.com/app/profile/katie.garcia/viz/ShelterVisualizations/Story12?publish=yes


# Segment 3 Deliverables
## Presentation (15 points)
Content
The presentation tells a story about the project and includes the following:

- Selected topic
- Reason topic was selected
- Description of the source of data
- Questions the team hopes to answer with the data
- Description of the data exploration phase of the project
- Description of the analysis phase of the project
- Technologies, languages, tools, and algorithms used throughout the project
- Slides
- Presentations are drafted in Google Slides.

## GitHub Repository (10 points)
Main Branch
All code in the main branch is production-ready.
main branch should include:
- All code necessary to perform exploratory analysis
- Most code necessary to complete the machine learning portion of the project
README.md
README.md should include:
- Description of the communication protocols has been removed
- Cohesive, structured outline of the project (this may include images, but they should be easy to follow and digest)
- Link to Google Slides draft presentation
IMPORTANT
The descriptions and explanations required in the project deliverables should also be in your README.md as part of your outline, unless otherwise noted.

## Individual Branches
Requirements for the individual branches follow:
- At least one branch for each team member
- Each team member has at least four commits for the duration of the third segment (12 total commits per person)

## Machine Learning Model (45 points)
Students will be expected to submit the working code for their machine learning model, as well as the following:
- Description of data preprocessing
- Description of feature engineering and the feature selection, including the decision-making process
- Description of how data was split into training and testing sets
- Explanation of model choice, including limitations and benefits
- Explanation of changes in model choice (if changes occurred between the Segment 2 and Segment 3 deliverables)
- Description of how they have trained the model thus far, and any additional training that will take place
- Description of current accuracy score
- Additionally, the model obviously addresses the question or problem the team is solving.

## Database Integration (0 points)
There are no deliverables for the database integration section of the project for this segment.

## Dashboard (30 points)
The dashboard presents a data story that is logical and easy to follow for someone unfamiliar with the topic. It includes the following:
- Images from the initial analysis
- Data (images or report) from the machine learning task
- At least one interactive element
