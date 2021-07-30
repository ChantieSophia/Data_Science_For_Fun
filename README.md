# Projects



[Project 1: Santa Clara County Workforce](https://github.com/ChantieSophia/scc-employee)<br>
* Almost 36% of the employees are Asian, 29% Hispanic and then followed by White employees, 24%.
<img src="./Top_3_employee_groups.png">
* Among all the job categories, professionals, administrative support, protective service workers and technicians are the biggest groups. Asian employees dominiate professionals and Technicians job categories while, Hispanic employees dominate in job categories of Administrative Support and Protective Service Workers.
<img src="./Employee_count_in_job_category.png">
* In all the departments, most of the Asian employees work in Santa Clara Valley Med Center, same as Hispanic and White employee. Compared with Asian and White employees, there is a higher percentage of Hispanic employees work in the social services agency.
<img src="./employee_count_in_department.png">
* As the results of Chi-square test, both results are significant, meaning there are associations between ethnicity and job cateogry and department respectively. However since the categories may not be completely independent from each other which violates the assumptions, we can not draw the conclusions that the association is actually there.<br><br>

Language: Python <br>
Tools: Pandas, Numpy, Matplotlib.pyplot, Seaborn, Socrata <br><br>

[Project 2: Santa Clara County Crime Reports](https://github.com/ChantieSophia/scc-crime-reports)<br>
* Overall trend for the number of crime reports is going down since 2020.
<img src="./overall-trend.PNG">
* Different type of crime reports have different distribution over the day. For total cases of all types, the number of crime reports goes up starts from 5-6 in the morning and flutuates a little and starts going down from 8-9 in the evening.
<img src="./count-by-hours.PNG">
<img src="./count-by-hour-type.PNG">
* The regression model I built is 78% acurate in prediction. There is a lot room to improve the accuracy by introducing more variables, for instance, the type of the crime report, etc,, which we will cover in future project.<br><br>

Language: Python <br>
Tools: Pandas, Numpy, Matplotlib.pyplot, Seaborn, Socrata, Skitlearn
