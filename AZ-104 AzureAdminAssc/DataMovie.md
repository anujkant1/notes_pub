Link: https://www.youtube.com/watch?v=J2rQTJby8XM&t=918s

Story:
- Managers have business questions that need answered:
  - `Why are profits down?`
  - `Should we invest here?`
  - `Which region is underperforming?`
- Without data, they are left guessing. 
- But in companies, the data is scattered everywhere. From different teams using different databases that are duplicated to customer feedback that is scattered among orgs. These different sources of data is a major issue for managers to tackle.
- That is where **Data Analyst** comes in:
  - gathers (queries/pulls) data from different sources
  - cleans, organises and structures the data
  - and, makes it suitable to answer questions
  - Once ready, it's presented in the form of visuals/reports to managers and other stakeholders
  - Skills include: SQL (query), Excel, Data visualisation skills using tools like PowerBI and Tableau.
  - Must also clearly understand the problem and present the data very clearly.
  - To master the skills, DA should be able to tell the story behind the data.

#### This may work for a small company but not for big companies.
- That is because big companis generate big data and that would be very hard for Data Analyst to keep up with. 
- Needless to say, doing it manually could take time (sometimes weeks!) and stakeholders can't wait that long when making decisions. 
- This is where **Data Architect** comes into the picture
  - The Data Architect converts the data into multiple layers, aka, **Medallion Architecture(Data System)**:
    - `Bronze` : Raw data
    - `Silver` : Clean data
    - `Gold` : Clean, structured and optimised data
- And then you also need **Data Engineers** to build *data pipeline* around it.
  - The pipeline automates the movement of data from sources to Data System,
    - Data moves from different sources to Bronze Layer, aka, `Data Ingestion`
    - from Bronze Layer to Silver Layer, aka, `Clean`
    - from Silver Layer to Gold Layer, aka, `Model`
    - This process runs automatically to improve efficiency.
- Once through, the **Data Analyst** can perform their function.
  - They can straight query the Gold layer and answer questions

#### But what about recurring questions that need reports?
- Not all questions asked to a Data Analyst would be one time reports.
- Sometimes, the report could be so useful that stakeholders may want them repeatedly with updated data
- This is where the role of **Business Intelligence (BI) Developer** 
  - They are responsible for making reports automated and available for all teams that have use for it.
  - They build a secure server where the dashboard will be hosted
  - The server is connected to Gold Layer where it pulls the data from
  - The users get access to the server to view the dashboard.

#### What about when managers want to predict the future demands?
- So far, we are seeing the past and present but what about making future predictions?
- This is where **Data Scientist** comes in:
  - Data Scientists and responsible for building and training the model that predict future demands using the data available. 
- Also, there is **Machine Learning(ML) Developer** who deploy a server to run the models by the Data Scientists and put it in Prod environment to automate the system
- The result of this could be presented in an application or dashboards.


## What is Data Science?
- Story with data always starts with a problem with the business, for instance, are we gaining customers?
- This is solved by **Data Analyst** as covered above. While there are many steps, in the end, the Data Analyst is building a Reporting Dashboard using tools like *Power BI* or *Tableau *
- 
