# The Dangers of Journalism: Death on Assignment
## Analyzing the killings of journalists around the world
### By Amanda Ramirez

Journalism can be a dangerous job. Some see a free press as intimidating and journalists as targets of violence. Even if the violence is not direct, pursing an assignment can also pose safety risks.  For this project, I was wondering about the circumstances of fallen journalists around the world. Some of the questions I asked were: Where and how did their deaths happen? To whom? Is it common?

![map](https://media.journalism.berkeley.edu/upload/2020/08/1597195418cf4e5b0.png)



I found this data from the Committee to Protect Journalists (CPJ). It had several categories. There were other data sets too about missing and kidnapped journalists. 


### To get the data in a usable format, I...
1. Uplodaded the data to Google Sheets
2. Organized the headings in a clear formatt (spacing, caps/lower case, bold font)
3. Looked at the different categories. Some categories had different names but the same information, so I deleted some columns with redundant information.
4. Verified the data. I wanted to make sure the data was accurate, so I looked up several journalists who had been killed to see if the information from news articles was consistent with the data presented in the spreadsheet.


### Data analysis

There were several categories of data to analyze.

The categories are as follows:
* Name
* Year
* Location
* Gender
* Type of death
* Confirmed status
* Role as a journalist
* Staff or freelance
* Organization
* Medium
* Local or foreign deaths
* Source of fire
* Tortured
* Captive
* Threatened
* Photo URL and photo credit

With this information, I was able to draw many conclusions using pivot tables. Each visual that follows will describe the process I used. 


![year](https://media.journalism.berkeley.edu/upload/2020/08/1597195028916d37b.png)
With this category, I asked: What years in the last three decades have the most killings of journalists? 

Turns out that 2009 had the most killings - 68 in a single year. I thought this would be an interesting question to ask to see if there were any trends. Turns out, there does not appear to be a trend. The years with more deaths of journalists seem to correlate with years of unrest in the area, whether that be due to wars or economic crashes. In my pivot table, I selected on 'Year' as the row and 'COUNTA' as the value. Then I clicked 'descending' order sorted by 'COUNTA.' I copied and pasted the table into Data Wrapper and chose the appropriate chart tyle.




![topcountries](https://media.journalism.berkeley.edu/upload/2020/08/159719551806d944e.png)
For this category, I asked: What are the top countries that journalists killed in on assignment? 

This was interesting to analyze because more deaths of journalists in a county seem to align with the unrest that country has faced in the last ~three decades. I was surprised that Iraq had vastly more than any other country. I thought it would be more spread out. I was also surprised that deaths of journalists on assignment happened in almost ever country at some point in the last 28 years. In my pivot table, I selected on 'Location' as the row and 'COUNTA' as the value. Then I clicked 'descending' order sorted by 'COUNTA.' I copied and pasted the first 10 values of the table into Data Wrapper and chose the appropriate chart tyle.




![deathtype](https://media.journalism.berkeley.edu/upload/2020/08/1597195304e45b50d.png)

For this category, I asked: What is the most common cause of death for journalists on the job? 

The most common cause is murder. Analyzing this data made me realize how much of a threat journalists are in some countries. They can be targetted by the government or community groups. But it also made me realize that there is also a significant amount of deaths by dangerous assignment. For one data point in the USA (which does not have too many deaths of journalists), I researched that the woman in my data set was actually killed when an attacker broke into her newsroom. This was shocking because I had never realized that happened in this country or could even be a threat here. But of course it can. In my pivot table, I selected on 'Death Type' as the row and 'COUNTA' as the value. Then I clicked 'descending' order sorted by 'COUNTA.' I copied and pasted the table into Data Wrapper and chose the appropriate chart tyle.




![medium](https://media.journalism.berkeley.edu/upload/2020/08/159719536241a1308.png)
For this category, I asked: What type of journalist is most commonly to be killed on assignment? 
I asked this question because I wanted to know who was doing the journalistic work in different countries across the world. Before looking at this data, I thought that more TV and broadcast journalists would be a target since they have a camera. Turns out, most journalists did print. In my pivot table, I selected on 'Medium' as the row and 'COUNTA' as the value. Then I clicked 'descending' order sorted by 'COUNTA.' I copied and pasted the table into Data Wrapper and chose the appropriate chart tyle.




