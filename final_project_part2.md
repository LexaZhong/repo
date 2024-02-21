| [home page](https://lexazhong.github.io/repo)| [Assignment 1](/Assignment 1.md)  | [visualizing debt](/Week3_inclass.md) | [Assignment 3&4](/Assignment 3&4.md) | [final project I](/final_project_part1.md) | [final project II](final-project-part-two) |

## What I did to the dataset (3-4h)
- the actual processing does not take long, but figuring out the right form of data that fits the visualization tools is very time-consuming
1. combining data from 2016-2021
2. filter out the NCAA from all classifications
3. select out the features I want (revenue, expense, count)
4. aggregation, calculation, modifying the data to fit the visualization tools

# Wireframes / storyboards
## 1. Fictional athlete: Football player Bob (60s story) **text in the middle, figures on both sides**
   - He joined the Sponge state college in 2020 and plays in the NCAA Division one. He is a very talented quarterback and brought victory to his team. He is the rising superstar and made for the box office. He generates billions of dollars for the college.
   - However, none of the revenue he generated goes to his own pocket. People would say, no way, he must have earned huge amount of money from commercials. But he did not. Because under the NCAA regulation, compensation for student athletes is limited to scholarships for their education. He is really annoyed and rushed to the Athlete director's office. But the AD says "Bob, do you know how much your coaching training cost? The revenue is deceiving, there is not much left after deducting all the expenses." "Oh, in addition to that, NCAA wants us to more equally distribute the funds, we probably need to cut the budget for football."
   - Poor Bob. What can he do? Luckily, in his second year in the team, in 2021, NIL deals are legalized in his state, which is considered one of the most significant changes in NCAA's history.. He signed deals with Nike, Gatorade and Benz, all are very lucrative partnerships.

## 2. Overview:
   - The U.S. hyper-commercialized system of college sports, which does not exist anywhere else in the world, has generated billions of revenue over the years.  Division I athletics generated $15.8 billion in revenues in 2019, according to the National Collegiate Athletic Association (NCAA), which regulates student athletics among 1,100 colleges and universities. Power Five conferences combined for more than $3.3 billion in total revenue during the 2022 fiscal year. The Big Ten led the pack at $845.6 million. The Big Ten's reported revenue eclipsed the SEC by more than $40 million, the latter reporting in February that it generated $802 million in revenue for 2022.
       - Charts(2 hrs): 1) Total revenue increase
       - Data Preprocessing (3 hr): EADA does not provide combined dataset. It also labels the year of dataset differently which is very confusing. In addition to that, there are two links for each year's data. The total numbers supposed to be the same but they are not. It took me a lot time to figure out which is the right one. I used python to combine the EADA data from 2016 to 2022 in order to show revenue and expense has changed over years by genders and by divisions.
    
### NCAA Revenue and Expenses trend 
<div class='tableauPlaceholder' id='viz1708319436127' style='position: relative'><noscript><a href='#'><img alt='NCAA Revenues and Expenses 2016-2021Recovering rapidly from COVID and still increasing ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1708319436127');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### NCAA Revenue and Expenses Trend: Men vs Women
<div class='tableauPlaceholder' id='viz1708319485607' style='position: relative'><noscript><a href='#'><img alt='NCAA Revenues and Expenses Trend: Men VS WomenMen&#39;s sports take up more expenses and generate more revenuesWomen&#39;s sports are not profitable ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1708319485607');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>


    
## 3. Conflict
With all the revenue generated by student athletes, is it possible to distribute revenue to better compensate the athletes?

1) Athlete expenses surpass revenue

> Chart: stream chart showing the revenue generated by divisions
> Chart: Table showing the net revenue
> Chart: FBS football net revenue by school

   - Net revenue of sports : Only a select share of Division I college athletes produce billions of dollars of revenue every year for their schools. Almost all of this revenue comes from football and men’s basketball. Expenditures by college athletics departments are such that, with the exception of a small number of schools, athletic expenses surpass revenues at the overwhelming majority of Division I programs. In 2019, only 25 of 130 schools in the high-grossing Football Bowl Subdivision (FBS) whose members are large, mostly public universities (with some exceptions such as Notre Dame, Northwestern, and Stanford) reported positive net revenues.

3) Intensified scrutiny over NCAA: Redistributing expenses
   - The employment status and fair compensation of college athletes are being discussed in state legislatures, U.S. Congress, federal agencies—such as the National Labor Relations Board—and federal courts. As scrutiny intensifies on the NCAA, the Power Five conferences and the Division I schools, there is an ever-increasing need for transparency and accuracy regarding where money is generated, how it is spent and on whom, focusing on non-revenue sports. 
     - Charts: Expense of football and men's basketball take up xx percent of the total expenses; Show the number of the medium salary of Division One Football: > $3.5 million. (rawgraph: stream graph to show football and men's basketball)

## 4. Solution and Problem
   - the timeline of legalizing NIL Deals.
   - The map of the states that has legalized NIL Deals in NCAA.


# User research 

## Target audience
### Anyone who is interested in NCAA
- The US college sports system is very different from that of other parts of the world. The audience can be people who are interested in NCAA regulations, or people who like US college sports. They might have never thought about NIL deals were prohibited for college athletes before, since a number of NCAA rising stars have signed partnerships with famous companies like Nike. These people would be interested in how are college athletes compensated and is it lucrative to be a NCAA student athletes. This story provides the basic information about the regulations related to college athletes compensation and the background of college sports which includes NCAA sports revenue trends and breakdowns, also explaining the logic behind legalizing NIL deals.


## Interview script


Text here!

| Goal | Questions to Ask |
|------|------------------|
| To improve the story of bob, and make it more engagin and informative.  | How well does the fictional athlete's story help you understand how the logic and benefits of legalizing NIL Deals for college Athletes?  |
| to make some modification to the scrolling effects and the images. |   Do you like the style of the icons/ cartoons of the story?               |
| I want to know how the story works for different audiennces. |  Do you feel it is hard for you to comprehend the content if you do not have knowledge in college sports? |
| Due to the scrolling effects, I want my visualizations to be very straight forward. | What do you think of the visualizations? Can you tell what each is trying to convey in less than 10 seconds?|
| I want to find out if the story is engaging and if there is a point it does not flow | Do you find the story interesting? Is there a point when you dont want to read about it anymore? What is it and Why?|


Text here!

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

Text here!

| Questions               | Interview 1 (briefly describe) | Interview 2 | Interview 3 |
|-------------------------|--------------------------------|-------------|-------------|
| Question you asked here | Insightful feedback            |             |             |
|                         |                                |             |             |
|                         |                                |             |             |


# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

Text here!

| Research synthesis                       | Anticipated changes for Part III                                                |
|------------------------------------------|---------------------------------------------------------------------------------|
| Findings or observations from interviews | Describe what, if any changes you anticipate making to address the observation. |
|                                          |                                                                                 |
|                                          |                                                                                 |
|                                          |                                                                                 |
| ...add more rows as necessary            |                                                                                 |

> ...include any final thoughts you have here. 

Text here!

# Moodboards / personas
> If you did this optional part, include details here.  Otherwise remove this section

Text here!
