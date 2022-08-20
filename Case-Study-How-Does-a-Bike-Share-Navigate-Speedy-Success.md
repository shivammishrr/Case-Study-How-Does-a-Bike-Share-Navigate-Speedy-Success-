---
title: "Case Study: How Does a Bike-Share Navigate Speedy Success?"
author: "Shivam Mishra"
date: "2022-08-15"
output: html_document
---

## The Ask Phase

### Guiding questions

1.What is the problem you are trying to solve?

*Cyclistic bike-share company in Chicago wants to maximize the number of annual memberships and they want to convert casual riders into annual members.*

2. How can your insights drive business decisions?

*While thinking of how the casual riders and annual riders use bike differently, if majority of Casual riders use it for leisure so if they're using it for almost everyday the company can give a lucrative offer for extended time period for people like them.*


### KeyTasks

* The Cyclistic wants to convert the  Casual riders into Annual Members.

### Key stakeholders

* **Lily Moreno** : The director of marketing and manager.

* **Cyclistic** : Marketing analytics team: A team of data analysts who are responsible for marketing strategy.

* **Cyclistic executive team** : The notoriously detail-oriented executive team will decide whether to approve the recommended marketing program.


## Prepare Phase

### Guiding questions

1.Where is your data located?

*Data located in aws cloud we can download it by clicking on the link.*

2.How is the data organized?

*The data is organized by ride_id which is unique id of the individual person who uses it.* 

3.Are there issues with bias or credibility in this data? Does your data ROCCC?

*No Because the it's First party data i.e. the data is collected by the company itself and the data is credible, and also data is ROCCC, its Reliable because its collected by company itself, Original, Comprehensive cause the data contain all critical information, Current because it is updated as per time, Cited.*  

4.How are you addressing licensing, privacy, security, and accessibility?

* The data has been made available by
Motivate International Inc. under this [license](https://ride.divvybikes.com/data-license-agreement), The Privacy of the data is maintained by displaying ride_id here despite of name of any person, security and accessibility is also maintained by access control.

5. How did you verify the data’s integrity?

*There are mainly three ways data is compromised Replicated, Transferred, Manipulated so this data is stored in AWS so replication is not possible if data is stored in one place only Transferred or manipulation is also not possible if you don't have access control.* 

6.How does it help you answer your question?

*By analyzing the data of casual riders how much they use bike everyday, how often they use it, or what avg cost per ride is by determining this we can offer them annual membership on low price and how much they can save money by purchasing it.*

7.Are there any problems with the data?

*The data is available on quarterly basis so there are multiple csv format of the data instead it can be stored in sql it was easy to analyze or visualize the data.*


### Deliverable

A description of all data sources used

*The data is mainly used from **internal sources**they generate these data directly from the bike which is nothing but their own product, the station from which it started its journey or where its going to end, the id or the members, the avg time they drive the bike these all kinds of data is directly track down by the bike itself.* 


## Process Phase

### Guiding questions

1.What tools are you choosing and why?

*I'm using tools like Format cells to format the cells into the respective form to analyze it and get error free results, also to combine these data i used the query editor in which i transformed the data and then cleaned it by removing duplicate, and errors and also some functions being used in it.*

2.What steps have you taken to ensure that your data is clean?

*By removing duplicates and errors, format the data from numericals to text.*

3.How can you verify that your data is clean and ready to analyze?

*By checking the formats, manually checking the data if there is and empty cells or duplicate data or by check it with the help of filter function.*

4.Have you documented your cleaning process so you can review and share those results?

*yes*


## Analyze Phase

### Guiding questions

1.How should you organize your data to perform analysis on it?

*we should organize data by formatting data in same data type or to say have same variables*

2.Has your data been properly formatted?

*yes*

3.What surprises did you discover in the data?

*One of the key surprise is that the members are the majority user of the cyclistic*

4.What trends or relationships did you find in the data?

* Members use more bike then the casual
* Members use less riding time 

5.How will these insights help answer your business questions?

*This insights helps to build profile for casuals*


## Share Phase

### Guiding questions

1. Were you able to answer the question of how annual members and casual riders use Cyclistic bikes differently?

*Yes

2. What story does your data tell?

*My data tells that the casual riders are less likely to use bike compare to members, they both are more likely to use at 17:00 at evening* 

3. How do your findings relate to your original question?

*One of my findings speaks about the time duration when they both use, the casual rider use it for longer duration where as the member use bike for consistently everyday, we can see that visualization on documentation of this case study.*



4. Who is your audience? What is the best way to communicate with them?

*my audience's are Lilly Moreno, Cyclistic Executive team are my audience to communicate with them i will give them presentation of my findings.* 

5. Can data visualization help you share your findings?

*yes*

6. Is your presentation accessible to your audience

*the visualization in presentation are understandable in a way that audience can understand the story data is focussing on, we can see that in presentation of the case study.*

## Act Phase

### Guiding questions

1.What is your final conclusion based on your analysis?

*AS we can see in last figure in documentation about the day which they use more bike, on average they take more ride on Saturday and Sunday compare to  usual days.*

2.How could your team and business apply your insights?

*Team can advertise our annual membership plan on weekends by offering free ride and explain it to them the benefit about taking the annual member plan.*

3.What next steps would you or your stakeholders take based on your findings?

*They could lower the price of annual member plan for new users for limited time period and they could advertise about it in smaller to medium scale in effective way*

4.Is there additional data you could use to expand on your findings?

*Data like the docked bike vs electric bike we can use that data to take a survey where we can ask them ask questions like what they prefer more docked bike electric bike or any other type of bike*
