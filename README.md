Utilize Data Science to feed the curiosity<br><br>
[Project 1: Water potability prediction](https://www.kaggle.com/chsoph/task-water-potability-prediction-66-accuracy)<br><br>
Language: Python <br>
Tools: Sklearn, Scipy.stats, Seaborn, Matplotlib.pyplot, Seaborn<br>
* Used two sampled t-test to test the mean of all the features, and correlation matrix to make sure all featurs are independent

<img src="./water-pred--corr-mtrix.PNG"> <br>

* Developed a classification model to predict water potability, accuracy 66% <br>

<img src="./water-pred-model-comparison.PNG"> <br>
<img src="./water-pred-classification-results.PNG"> <br><br>

[Project 2: Santa Clara County Workforce](https://github.com/ChantieSophia/scc-employee)<br><br>
Language: Python <br>
Tools: Pandas, Numpy, Matplotlib.pyplot, Seaborn, Socrata <br><br>
* Almost 36% of the employees are Asian, 29% Hispanic and then followed by White employees, 24%.<br>
* Among all the job categories, professionals, administrative support, protective service workers and technicians are the biggest groups. Asian employees dominiate professionals and Technicians job categories while, Hispanic employees dominate in job categories of Administrative Support and Protective Service Workers.<br>
* In all the departments, most of the Asian employees work in Santa Clara Valley Med Center, same as Hispanic and White employee. Compared with Asian and White employees, there is a higher percentage of Hispanic employees work in the social services agency.<br>
* As the results of Chi-square test, both results are significant, meaning there are associations between ethnicity and job cateogry and department respectively. However since the categories may not be completely independent from each other which violates the assumptions, we can not draw the conclusions that the association is actually there.<br><br>
<img src="./Top_3_employee_groups.png"> <br>
<img src="./Employee_count_in_job_category.png" width="600" height="404"> <img src="./employee_count_in_department.png" width="600" height="404">

[Project 3: Santa Clara County Crime Reports](https://github.com/ChantieSophia/scc-crime-reports)<br><br>
Language: Python <br>
Tools: Pandas, Numpy, Matplotlib.pyplot, Seaborn, Socrata, Skitlearn<br><br>
* Overall trend for the number of crime reports is going down since 2020.<br>
* Different type of crime reports have different distribution over the day. For total cases of all types, the number of crime reports goes up starts from 5-6 in the morning and flutuates a little and starts going down from 8-9 in the evening.<br>
* The regression model I built is 78% acurate in prediction. There is a lot room to improve the accuracy by introducing more variables, for instance, the type of the crime report, etc,, which we will cover in future project.<br><br>
<img src="./overall-trend.PNG" width="600" height ="221">
<img src="./count-by-hours.PNG" width="312" height ="231">
<img src="./count-by-hour-type.PNG" width="1088" height ="434">


[Project 4: 2016 presidential candidates spending](https://github.com/ChantieSophia/2016-president-candidates-spending.git)<br><br>
Language: Python, SQL<br>
Tools: pandsql, googlesearch<br><br>
* data wrangling by adding back Party data for each candidate<br>
Before - missing canndidate party data in column Paty, wrong data format in column dist_dt<br>
<img src="./before.PNG" alt = 'before'>
<br>
After - anndidate party data, data format corrected<br>
<img src="./after.PNG" alt = 'after'>
<br>
* table transformation: added rolling total and rank columns<br>
<img src="./windows-functions.PNG">

[Project 5: basic portfolio website](https://chantiesophia.github.io/)<br><br>
Language: HTML, CSS<br>
