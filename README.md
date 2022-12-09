# Impact of Student and Staff Diversity on Student 6-year Graduation Rates 
Contributors: David Abney, Hrishikesh Deepak Dhole, Chang He, Michael Palacioz

## Problem Statement
In recent years colleges and universities have been admitting and retaining a more diverse student body However, many universities have changed practices that allow for the diverse student body to feel welcome on campus while being supported in a thriving environment. Studies have shown that when students see themselves represented in faculty and staff on a college campus, they are more likely to graduate. Given that many universities have a commitment to recruiting and retaining a more diverse student body, faculty, and staff our group wanted to look at the following questions related to Student 6-year graduation rates at Public 4-year degree-granting institutions. For our analysis, we included information regarding enrollment data, graduate data, financial aid data, and endowment information that was available publicly through IPEDS dataset for 2013-2020. 
- Can a change in the percentage in the diversity of a student body predict changes in graduation rates? 
- Can a change in the percentage in the diversity of faculty predict changes in graduation rates?	  
- What is the relationship between student body diversity rates and faculty diversity rates to the total graduation rate and the graduation rate of different races and ethnicity groups?

## Repository Information
- Testing-Archive
  -	Old test runs of the data set
- LoadEducationData.ipynb
  - This is the Python notebook use to combine all the separate IPEDS csv files into one file based on the variables we need
- VisualsAndModeling.ipynb
  - This is the Python notebook used for analysis and modeling related to the questions above
- university_data.csv
  - Data set used in the VisualsAndModeling.ipynb notebook and output from the LoadEducationData.ipynb
  
## Instructions
1. Download the VisualAndModeling.ipynb Colab notebook file to Google Drive
2. Run the Colab notebook with it pointed to the raw university_data.csv file link in this GitHub site
3. View the results

Optional: the LoadEducationData.ipynb file is a Jupyter Notebook file used to combine the contents of the university, enrollment, graduation, staff, finance, and student financial aid files from the IPEDS site: https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx. It was used to create the university_data.csv file used in this project.
  
### Sources/Links
Date Source: https://nces.ed.gov/ipeds/use-the-data, https://nces.ed.gov/ipeds/datacenter/InstitutionByName.aspx?goToReportId=5, https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx?gotoReportId=7&fromIpeds=true 

### References:
Flaherty, C. (2022, December 2). Faculties So White. Report finds faculty diversity isn't meeting student needs . Retrieved December 2, 2022, from https://www.insidehighered.com/news/2022/12/02/report-finds-faculty-diversity-isnt-meeting-student-needs#.Y4oCl_sZDTs.linkedin 

Interfolio Team. (2022, August 18). The benefits of diversity in higher education. Interfolio. Retrieved October 9, 2022, from https://www.interfolio.com/resources/blog/the-benefits-of-diversity-in-higher-education/#:~:text=Improved%20Student%20Engagement%20and%20Retention,of%20students%20from%20underrepresented%20groups.

Smith, D. G., Turner, C. S., Osei-Kofi, N., & Richards, S. (2004). Interrupting the Usual: Successful Strategies for Hiring Diverse Faculty. The Journal of Higher Education, 75(2), 133–160. http://www.jstor.org/stable/3838827 

Tam, M. Y., & Bassett, G. W. (2004). Does diversity matter? measuring the impact of high school diversity on freshman GPA. Policy Studies Journal, 32(1), 129–143.  https://doi.org/10.1111/j.0190-292x.2004.00056.x  
