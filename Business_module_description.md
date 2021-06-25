Business_Fundamentals_project_work_description
Gabriella Nemeth


How can I help?


The project's goal is to help optimizing the rota of customer service representatives with data science methods to improve the customer's experience. 

The project investigates the opportunities for quality and quantity improvements.
For quantity improvement the focus on the incoming, answered, abandoned calls and the waiting time. To predict the future number of calls for different time periods we need to know well the current status.
The quality improvement part of the project is about how can the company give a better customer experience by the knowledge of the agents.

At the end of the project I recommend data science methods and models for the different stages of the solution path.


Design

As Customer Service is an important part of every institution, to provide an excellent customer experience is crucial and necessary to reach success on the market.
Studies shows that good customer service have a great impact on almost every important figures of the company, like customer retention score, sales number, growth rate, reduction of cost of new acquisition.

One of the most significant factor of the excellent customer service is to always have the right amount of agents available with the right skill sets. 


Data

Customer service sample datasets were exported from Kaggle. One of the datasets shows information of calls between 2018 and 2021 with details for incoming calls, handled calls, answer rate, waiting time, abandoned calls, talk duration, answer speed, service level.
The other shows received calls for 2019 for every half an hour.


Algorithms

For quantity issues the monthly incoming and abandoned call volumes and the average calls by hours and the rate of queued calls at that time periods. The data show that the call answering rate is around 90% which is not bad, but still there is some space to improve. The other part of the quantity analysis is the waiting time. I set a parameter for 3 mins (180 sec) what the waiting time should not excess. In the data we can see that only Fridays are the time when this value is less than 180 secs. The company losing customers due to their slow customer service. The better predicted call number would let the managers to allocate enough people to each shift which would satisfy customer need better.

The quality improvement focuses on the well trained motivated representatives. The best knowledge set can be set up if the appearing problems during the calls are recorded or the client itself tells us before the call would be transferred. In this case the company would be a better picture which problems occurs the most often and where need more training.


Tools

The exported data was cleaned and EDA was made in Google Sheet.
The results of the finding were visualized in Google Sheet and Tableau.


Communication


![Calls_by_hours_of_day](https://raw.githubusercontent.com/NemeGabi/Metis_Business_Project/main/Calls_by_hours.png)
![Calls_by_months_of_year](https://raw.githubusercontent.com/NemeGabi/Metis_Business_Project/main/Calls_by_months.png)
![Calls_by_waiting_time](https://raw.githubusercontent.com/NemeGabi/Metis_Business_Project/main/Dashboard_of_waiting_time.png)


