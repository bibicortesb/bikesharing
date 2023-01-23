# bikesharing
## Project Overview
Analize CitiBike information to uncover customer behaviour, usertype, service consumption by weekdays and weekends. 
To build a robust back up for CityBike Program in Des Moins' pitch. 

### Purpose

Through this project, citibike information is analized to draw insights of the behaviour of the consumers. This information intends to support the endeavour of a bike-sharing venture in Des Moins.Month of August was selected to conduct this analisis because of the warm weather for a starting point. 

Three main questions were addressed:
  - The time bikes are used for all riders and genders. 
  - The bike trips for all riders and genders for each hour and day of the week.
  - The bike trips 
Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.

## Resources

- Data Source: citibikedata.csv 
- Software: Tableau & Python 3.9.12, 

## Results

The results were published in Tableau public in the following link: [link to dashboard](https://public.tableau.com/views/bikesharing_16744307292060/bikesharing?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)

In the first slide, the purpose of the project is described. Followed by the visualizations that will deepen the analysis.

### Number of rides
<img width="179" alt="Screen Shot 2023-01-23 at 8 23 54" src="https://user-images.githubusercontent.com/114015620/214063414-0c90ff0a-0359-4deb-87f9-cc6cfd2f163e.png">
It is important to define the universe we will focuse the analysis. In August 2019 in NYC, the total numbers of rides is presented in the dashboard as a text box, 2,344,224. 

### Checkout Times for Users

<img width="790" alt="Screen Shot 2023-01-18 at 22 17 24" src="https://user-images.githubusercontent.com/114015620/213354059-3ba751f1-bd15-4ab2-a9d1-3c2a213cdee9.png">

In the line graph, th number of bikes is plotted against the tripduration in minutes. By observing the graph, we can begin to draw conclusions. Trips that are 5-6 minutes long are the most recurrent trips. The peek is observed in the plot around 146k rides. Another interesting insights is that few trips last longer than 1 hour.  

### Checkout Times by Gender

<img width="969" alt="Screen Shot 2023-01-18 at 22 17 58" src="https://user-images.githubusercontent.com/114015620/213354116-09c7c47f-3f82-4a47-b476-b2d733129931.png">
In the graph the checkouts are displayed by gender. Here, we have more resolution on data which enables us to drill down the information to find that males use significantly more the bikesharing service than females. Both have their peek tripduration around 5 minutes. The peek of males is around 100k rides. On their side, females peek at 34k, this mean a difference in utilization of 66% more for males. This can also lead to further questions. Is there anything that can be done to even these numbers? Shall the initial campaing give more focus to males since their adoption is higher? Just a few observations that could support customer profiling.

### Gender Breakdown


<img width="326" alt="Screen Shot 2023-01-23 at 8 51 08" src="https://user-images.githubusercontent.com/114015620/214069926-77caa7f0-9fd3-4cb4-b64e-0224b1124524.png">

In the pie chart the porpotion of males can be observed, there were 1.5 M males, 588k females and 225k unknown. This means:
- 65% of the costumers are males.
- 25% are females.
- 10% unknown.

Now that we know the distribution of customers by gender. Let's explore their behaviour by age.

### User type

<img width="180" alt="Screen Shot 2023-01-23 at 9 46 10" src="https://user-images.githubusercontent.com/114015620/214083457-01b84439-e6a3-416a-96ae-76658265d512.png">

In the table, User Type is shown. By having the suscriber and customer count we ensure that everyone is can check easily how much each represent out of the total. In case they need to make inferences with the rest of the visualizations that will use user type as a dimension for analysis.


### User type by gender

<img width="886" alt="Screen Shot 2023-01-23 at 9 00 45" src="https://user-images.githubusercontent.com/114015620/214072378-9eb7569e-532d-444e-ab3f-f14c8785a488.png">

In the bar plot we can see that there are two types of users: Customer and Suscriber. Also, the plot allows us to observe the breakdown by gender. For both user types, males represent the biggest proportion. In Customers, unkown gender is more frequent than in Suscribers. In this visualization, Birth Years is used as a variable. The range can be used to analyse certain groups, this can also be useful for costumer perfiling.  

### Trips by weekday per hour

<img width="517" alt="Screen Shot 2023-01-23 at 9 37 03" src="https://user-images.githubusercontent.com/114015620/214081320-999ebfc2-1032-4b41-ba05-67eea040a448.png">


The heat map shows that the behaviour changes from weekdays to weekends. On Sundays and Saturdays, the range of service utilization is more frequent from 10 am to 6 pm. On weekdays it is different, most trips are concentrated in defined periods on the moring and aternoon. One interesting day is friday,it has a sort of merge between the behaviour of the weekends and weeekdays. Furthermore, this information could give a good clue for mantainance routines. 

### Trips by gender 

<img width="1078" alt="Screen Shot 2023-01-23 at 9 36 15" src="https://user-images.githubusercontent.com/114015620/214081149-df4ab106-fdaa-4d2e-9818-4f0312c4e5a9.png">
The heat map is now displayed with gender differentiation. With this information, we can see the patterns of behaviour of by gender. No mattter the gender, the behaviour mantains with defined hours on weekdays in the morning and afternoon and a broader distribution on weekends. The heat map is useful because visually we can have a lot of information on the concentration of rides by hour and weekday.

The heat map shows that the 
- Th bussiest hours of the day are in the morning fro 6.00am to 9.00pm
- The bussiest hour of the day are in the afternoon are from 4.00pm tp 8.00 pm.
- The bussiest day is Thursday.
- Weekdays also have more demand than weekends. 

### Bkk
<img width="552" alt="Screen Shot 2023-01-23 at 9 49 27" src="https://user-images.githubusercontent.com/114015620/214084396-2fd26f40-f176-4b0d-b707-e63199c1a944.png">

In the heat map, the contrast between user types is well defined. Suscriber use significally more the bike sharing service. Gender diemnsion enables to have valuable information on gender, weekday and usertype behaviour. Some insights that are preseted in the heat map are the following: 
- Suscribers represent have significantly more activity than regular costumers.
- The busiets days are Thursday and Friday.
- Customers use the service on weekends more frequently than they do on weekdays.


## Summary & Further Analysis

Some insights are summarized in the following bullet points: 

- There were 2.3 M users in August 2019 for CitiBike NYC.
- There are two types of users Costumers and Suscriber. 
- Males represent 65% of users. 
- Females 25%, the rest 10% unknown. 
- Users' behaviour shifts from weekdays to weekends. 
- Weekday, have well difined hours in the morning and afternoon. 
- Weekends have a wider spread of rides along the day.
- The bussiest day of the week is Thursday. 
- Customers use the service more on weekends than on weekdays.

Further analysis: 
- Customer profiling can be a great tool for early stages in Des Moins Program for marketing strategy. 
- Female beahaviour can be followed closely to level up the numbers.

## Conclusion

No doubt, Citibike NYC data is great for benchmarking and supporting new endeavours. Thanks to tableau information can be displayed in a clean, organized and interactive way to make insights on customer behaviour, market size and potential campaings for launching. Hopefully this analyisis can be an aid for Des Moins' future investors. 



