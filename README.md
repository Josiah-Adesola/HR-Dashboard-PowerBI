# HR-Dashboard-PowerBI


-----------------------------------------


# PROBLEM STATEMENT

A popular adage states that if a man or a leader, doesn't know the number of people he is feeding, his empire will crash, this might should funny or ridiculous, but it's true. Many companies have a lot of staff, but can account for the number of staffs, their demographics such as departments, location, gender, marital status, employment status - active, resigned, passive, years of experience, age and so on.

![image](https://user-images.githubusercontent.com/59745353/173717629-eaf183a2-a506-44a0-ba76-c9ebf4c7e41b.png)


A company without this knowledge, can easily make wrong assumptions and crumble, such as losing finances, by paying salaries to resigned or passive workers, not knowing the reason why workers are leaving the company, not having good knowledge of the population of the most active workers and why they are active. All these questions, needs to be answered and insights can be derived to make the right business decisions.

I analyzed the data for an imaginary company named Quizen Company

-----------------------------------------------------


# DATA SOURCING

This data was outsourced from a tutor online and can easily be downloaded in an excel format to see and make analysis.

https://docs.google.com/spreadsheets/d/1byMDKWLFVXrjdqjcp7dFeVUJQXIhfMA8/edit?usp=sharing&ouid=110515991544756509836&rtpof=true&sd=true

----------------------------------------------------------------

# DATA TRANSFORMATION

My data transformation was achieved with Power Query in Power BI. I renamed the file to HRData. I was able to trim some column text, I had to provide an important measure with DAX Called the Employee's Count, this is crucial to almost all the visualizations.

![image](https://user-images.githubusercontent.com/59745353/173717759-cc02e6df-b902-44b9-941d-83045bad74b2.png)

 We need to know the number of employees in different scenarios.
I renamed some text, I did bfill, for missing values in the ResignationReason Column, and a lot of other things
Some columns were renamed and transformed, and many values renamed, I also did conditional formatting on some columns

![image](https://user-images.githubusercontent.com/59745353/173717866-f049ce51-b551-4de6-a6b3-f91094a9d5ed.png)



---------------------------------------------------------------------------------

# DATA ANALYSIS AND VISUALIZATION

Power BI remains a powerful too for visualization. 
I included slicers, to make powerful insights almost immediately.
The visualizations, are also connected and responsive to each other, you could tap and see the insights for that particular visuals.

Check out the beautiful visualization below



![image](https://user-images.githubusercontent.com/59745353/173717097-0f16d68b-703f-4e58-8d40-2fe2dd3e3dcf.png)

-----------------------------------------------------------------------------------
# FINDINGS AND RECOMMENDATIONS

1. We have over 20,0000 employee working in QUIZEN Company.
2. QUizen Company has more female staffs than male staffs, then majority are married.
3. Most of Quizen Staffs have a lot of experience ranging from 0 - 10 years of experience. This is really good for a company for innnovation and excellence, then few people have over 20 years of experience.
4. Most of Quizen employees are young adults ranging from 20 - 40 years. Quizen have few old men, as staffs.
5. The departments with the highest staffs are the sales, finance, marketing, operations and IT, these departments should be looked into, and see how they can maximize cost with few staffs.
6. Most of the QUIZEN Staff left the company because of little salary and carrier change, also there seems to be an unhealthy Work enviroment in Quizen over 5000 staffs are unhappy with the work environment.

![image](https://user-images.githubusercontent.com/59745353/173719434-a76f801b-48bd-41fd-b1d0-1750a2b97e08.png)

-----------------------------------------------------------------------
