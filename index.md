# About Me
2+ Years of experience in the gaming industry, as Product & Marketing Manager and Consultant. Academical background in engineering, research, entrepreneurship and innovation. Fell in love with the more data-related aspects of Product Management after having my first experience with dashboarding and reporting to senior leadership, so decided to pursue further education.
<br><br>
Currently looking for job as Data Analyst/Product Manager, ideally in the gaming industry, but open to other areas of knowledge. Mainly interested in bringing business value through enacting strategic business/product changes grounded in a deeper understanding of what affects critical KPIs. 
<br><br>
Currently situated in Munich, Germany. Open to relocation or remote work.

# Portfolio
### [Short summary of smaller projects](https://drive.google.com/file/d/17geiwNp7N6u-_QfoQPS9MhVLHKrM8mF2/view)
### [Database Modelling project](https://github.com/nunomdmarques/Database-Modelling-Project/tree/main) - SQL, data modelling, database architecture
### [Influenza Season Staffing Plan Development](/pdf/Task 4 - Case Study.pdf) - Excel, Tableau
### [AirBnB Amsterdam Listings Analysis](/pdf/AirBnB%20project%20presentation.pdf) - Python(sklearn, pandas, matplotlib), Excel, Tableau
### [Rockbuster Stealth Customer Base Analysis](https://nunomdmarques.github.io/Rockbuster-Stealth-Data-Analysis_Project/) - SQL
---

## Highlighted Project - [Influenza Season Staffing Plan Development](/pdf/Task 4 - Case Study.pdf)
<img src="images/US%20States%20by%20Priority%20Level.png?raw=true"/>
- **Problem**: The US has an influenza season where more people than usual
suffer from the flu. Vulnerable populations develop serious complications
and end up in the hospital. Hospitals and clinics need additional staff to
adequately treat these extra patients. It is hard to understand which states
and hospitals should be prioritized when designing staff plans.
- **Objective**: Determine the priority states to staff, based on historical data
from 2009-2017.
- **Client**: A medical staffing agency covering all hospitals in the 50 US states
wants help to build a staffing plan for next year’s influenza season.
- **Context**: This project was completed in the context of Career Foundry’s
Data Analytics Program. The data is real, but the scenario and agency are
fictitious.
- **Skills**: Data cleaning, wrangling and analysis in Excel. Visualizations in
Tableau
<br><br>

### Success Definition and Initial Brainstorming:
Before starting to even analyze the data, I needed to understand how to define success, as well as do some research on which variables could be the more interesting.
<br><br>
So, how do we define "adequate" staffing? According to the agency's requirements and my own research we aimed to minimize understaffing (staff-to-patient ratio < 0.23) and overstaffing (staff-to-patient ratio > 0.27).
<br>
At the onset of the project we assumed critical parameters for influenza severity included the number of vulnerable populations, influenza death counts, and vaccination rates.
<br><br>
### Staffing Adequacy:
Understanding which states were critical in past years would have been ideal, but we didn't have data on staffing adequacy for those years. So, I advised the agency to start collecting data on staff-to-patient ratios and staff and patient satisfaction surveys for future planning and assessing next year's influenza season staffing plan.
<br><br>
### Data Collection:
I gathered data from multiple sources:
- Population data from the U.S. Census Bureau.
- Influenza death counts, hospital visits, lab tests, and children’s flu vaccination data from the CDC.

### Data Cleaning:
I needed to ensure the data was accurate, complete, consistent, unique, timely, and valid. Unfortunately, some datasets, like children’s vaccination rates and influenza-related hospital visits, were too incomplete to analyze further due to suppression of data for anonymization. Similarly, a lot of data for age groups below 45 years was missing from the influenza deaths dataset, as you can see from the frequency table below.

<br><br>
<img src="images/missing%20data.png?raw=true"/>
### Data Wrangling:
I focused on populations aged 45 and older, since no alternative complementary datasets were found. I joined and grouped the influenza death counts and the state population data by the following common denominators: US state and month of the year (from 2009-2017). Then, I normalized influenza death counts for each state by the state populations for the respective month to prepare for the analysis.
<br><br>
### Data Analysis – Key Questions:
I sought to answer:
- Are there any trends in the influenza season’s behavior?
- Is there a relationship between vulnerable populations and death counts?
- How do we prioritize which states to send staff to?

<br><br>
### Trends in Influenza Season:
My analysis showed that the influenza season in the U.S. predominantly runs from November to March, with a peak in deaths starting in November and tapering off after March. This confirmed that influenza has a predictable seasonality
<br><br>
<img src="images/Screenshot 2024-06-03 175900.png?raw=true"/>
### Relation Between Vulnerable Population and Death Counts:
Interestingly, the elderly population (65+) accounted for 91.63% of recorded deaths.
<img src="images/pie chart deaths.png?raw=true"/>
<br><br>
However, states with more elderly populations didn't consistently have higher death counts relative to their population. From the scatterplot, it was evident that the trend lines were mostly flat, indicating no significant correlation. Therefore, I decided to focus on total and normalized death counts for staffing decisions instead of just vulnerable population counts.
<br><br>
<img src="images/trend of deaths with vulnerable pop.png?raw=true"/>
### State Prioritization:
I identified critical states needing additional staff by looking at both total and normalized death counts during the peak influenza months (November-March). The data revealed that the Southern region would likely be the most critical, with higher death counts in both metrics.
<br><br>
<img src="images/state deaths total and normalized.png?raw=true"/>
### Recommendations:
I presented the states that required additional staffing based on my analysis and visualized these states on a map for clarity. The top 17 priority states were identified using a mixed weight between total death counts and normalized death counts.
<br><br>
<img src="images/Priority levels.png?raw=true"/>
### Conclusions & Next Steps:
- I confirmed that the influenza season lasts from November to March.
- There’s no significant relationship between the proportion of elderly populations and death counts.
- By considering higher normalized and total death counts, we identified the most critical states for staffing.
- Moving forward, we need to assess seasonality on a per-state basis, gather data on younger age groups and vaccination statuses, and plan procedures for evaluating the staffing plan's effectiveness.

<br><br>
### Project Retrospective:
The biggest challenges were dealing with missing data and presenting information for 51 states in a meaningful way. I learned the importance of setting up proper data collection processes and using standard data aggregation methods to make information more readable and statistically meaningful.
<br><br>
### Supporting Material:
If you’re interested, you can check out the full analysis on my [Tableau Public Dashboard](https://public.tableau.com/app/profile/nuno.marques1822/viz/PreparingastaffingplanforInfluenzaSeasonManagement/Story1)
 and watch my [Video Walkthrough of the Dashboard](https://www.loom.com/share/2d39685bca6b4e6ba8e741a5e595158e?sid=3dc95285-c039-4d66-ae8e-51a738099120). Feel free to reach out to me on LinkedIn or via email if you have any questions!
 
---

## [AirBnB Amsterdam Listings Analysis](/pdf/AirBnB%20project%20presentation.pdf)
<img src="images/AirBnBlistings.png?raw=true"/>
- **Problem**: Over the past decade, services like AirBnB have grown exponentially, becoming an alternative for those seeking a more local and private stay than a traditional hotel.
Nowadays, people utilize this alternative service to generate additional income by investing in rental properties. However, the rental market is highly region and time-specific<br>
- **Objective**: Understand the Amsterdam AirBnB market to provide insights for prospective AirBnB hosts who have or want to have listings in Amsterdam.<br>
- **Context**: This project was completed in the context of Career Foundry’sData Analytics Program. The data is real.<br>
- **Skills**: Python (sklearn), Clustering Algorithms, Data wrangling & subsetting, Joins, grouping and aggregating, Data Viz(Matplotlib & Seaborn),Tableau Storyboards
<br><br>
[Tableau Public Dashboard](https://public.tableau.com/app/profile/nuno.marques1822/viz/AirBnBAmsterdamlistinganalysisproject/Story1) <br><br>
[Github Repository](https://github.com/nunomdmarques/AirBnB-Amsterdam-Listing-Analysis)


---

## [Rockbuster Stealth Customer Base Analysis](https://nunomdmarques.github.io/Rockbuster-Stealth-Data-Analysis_Project/)
<img src="/images/Screenshot%202024-06-18%20222945.png?raw=true"/>
- **Problem**: Rockbuster Stealth LLC is a movie rental company that used to have stores all around the world. Competition from streaming services such as Netflix and Amazon Prime, has brought them to reconsider their current business model.<br>
- **Objective**: Query Rockbuster’s database to understand current clients and boost launch of new online video rental service<br>
- **Context**: This project was completed in the context of Career Foundry’s Data Analytics Program. The data is fabricated.<br>
- **Skills**: PostgreSQL, Database querying, Filtering data, Summarizing & cleaning data, Joining tables, Performing subqueries, Common table expressions <br><br>
[Rockbuster Data Set](https://www.google.com/url?q=http://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip&sa=D&source=apps-viewer-frontend&ust=1718828740041405&usg=AOvVaw3GD8eLLqRKpkRrQltiM1yf&hl=pt-BR) <br>
[Full analysis presentation](https://drive.google.com/file/d/1WbnU_rA169lxH0iKGI91MF3nqbgQYP5g/view) <br>
[Data Dictionary](https://drive.google.com/file/d/1DDTQgIG8Imrn9GkAonF3a4xCW2tzDTdt/view) <br>

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
