| [home page](https://lexazhong.github.io/repo)| [Assignment 1](/Assignment 1.md)  | [visualizing debt](/Week3_inclass.md) | [Assignment 3&4](/Assignment 3&4.md) | [final project I](/final_project_part1.md) | [final project II](final-project-part-two) |


# Wireframes / storyboards
## 1. Overview:
   - The U.S. hyper-commercialized system of college sports, which does not exist anywhere else in the world, has generated billions of revenue over the years.  Division I athletics generated $15.8 billion in revenues in 2019, according to the National Collegiate Athletic Association (NCAA), which regulates student athletics among 1,100 colleges and universities. Power Five conferences combined for more than $3.3 billion in total revenue during the 2022 fiscal year. The Big Ten led the pack at $845.6 million. The Big Ten's reported revenue eclipsed the SEC by more than $40 million, the latter reporting in February that it generated $802 million in revenue for 2022.
       - Charts(2 hrs): 1) Total revenue increase; 2) Conferences breakdown of revenue 3) gender gap between men and women expense
       - Data Preprocessing (3 hr): EADA does not provide combined dataset. It also labels the year of dataset differently which is very confusing. In addition to that, there are two links for each year's data. The total numbers supposed to be the same but they are not. It took me a lot time to figure out which is the right one. I used python to combine the EADA data from 2016 to 2022 in order to show revenue and expense has changed over years by genders and by divisions.
    
### NCAA Revenue and Expenses trend
<div class='tableauPlaceholder' id='viz1708319436127' style='position: relative'><noscript><a href='#'><img alt='NCAA Revenues and Expenses 2016-2021Recovering rapidly from COVID and still increasing ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpenses2016-2021&#47;TotalRevnueandExpenseTrend&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1708319436127');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

### NCAA Revenue and Expenses Trend: Men vs Women
<div class='tableauPlaceholder' id='viz1708319485607' style='position: relative'><noscript><a href='#'><img alt='NCAA Revenues and Expenses Trend: Men VS WomenMen&#39;s sports take up more expenses and generate more revenuesWomen&#39;s sports are not profitable ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NC&#47;NCAARevenuesandExpensesTrendMenvsWomen&#47;NCAARevandExpmenvswomen&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1708319485607');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>



### NCAA Revenue by Division
<div class='tableauPlaceholder' id='viz1708307905250' style='position: relative'><noscript><a href='#'><img alt='NCAA Revenue Breakdown by Divisions (Year 2021)Division One generates $12.1 billion (Total $16.6 billion)  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Totalrevenuebydivision&#47;NCAArevbydivision&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Totalrevenuebydivision&#47;NCAArevbydivision' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;Totalrevenuebydivision&#47;NCAArevbydivision&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div><script type='text/javascript'> var divElement = document.getElementById('viz1708307905250');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
    
## 2. Conflict
With all the revenue generated by student athletes, is it possible to distribute revenue to better compensate the athletes?
1) Athlete expenses surpass revenue
   - Net revenue of sports : Only a select share of Division I college athletes produce billions of dollars of revenue every year for their schools. Almost all of this revenue comes from football and men’s basketball. Expenditures by college athletics departments are such that, with the exception of a small number of schools, athletic expenses surpass revenues at the overwhelming majority of Division I programs. In 2019, only 25 of 130 schools in the high-grossing Football Bowl Subdivision (FBS) whose members are large, mostly public universities (with some exceptions such as Notre Dame, Northwestern, and Stanford) reported positive net revenues.
     - Charts: Percentage of sports that is non-revenue
2) Intensified scrutiny over NCAA: Redistributing expenses
   - The employment status and fair compensation of college athletes are being discussed in state legislatures, U.S. Congress, federal agencies—such as the National Labor Relations Board—and federal courts. As scrutiny intensifies on the NCAA, the Power Five conferences and the Division I schools, there is an ever-increasing need for transparency and accuracy regarding where money is generated, how it is spent and on whom, focusing on non-revenue sports. 
     - Charts: Expense of football and men's basketball take up xx percent of the total expenses; Show the number of the medium salary of Division One Football: > $3.5 million.

## 3. Solution and Problem
   - the timeline of legalizing NIL Deals.
   - The map of the states that has legalized NIL Deals in NCAA.

## 4. Fictional athlete: Football player Bob (60s story)
   - He joined the Sponge state college in 2020 and plays in the NCAA Division one. He is a very talented quarterback and brought victory to his team. He is the rising superstar and made for the box office. He generates billions of dollars for the college.
   - However, none of the revenue he generated goes to his own pocket. Because under the current NCAA regulation, compensation for student athletes is limited to scholarships for their education. He is really annoyed and rushed to the Athlete director's office. But the AD says "Bob, do you know how much your coaching training cost? The revenue is deceiving, there is not much left after deducting all the expenses." "Oh, in addition to that, NCAA wants us to more equally distribute the funds, we probably need to cut the budget for football."
   - Poor Bob. What can he do? Luckily, in his second year in the team. NIL deals are legalized in his state, which is considered one of the most significant changes in NCAA's history.. He signed deals with Nike, Gatorade and Benz, all are very lucrative partnerships.


# User research 

## Target audience
### Anyone who is interested in NCAA
- The US college sports system is very different from that of other parts of the world. The audience can be people who are interested in NCAA regulations, or people who like US college sports. They might have never thought about NIL deals were prohibited for college athletes before, since a number of NCAA rising stars have signed partnerships with famous companies like Nike. These people would be interested in how are college athletes compensated and is it lucrative to be a NCAA student athletes. This story provides the basic information about the regulations related to college athletes compensation and the background of college sports which includes NCAA sports revenue trends and breakdowns, also explaining the logic behind legalizing NIL deals.


## Interview script
> List the goals from your research, and the questions you intend to ask. 

Text here!

| Goal | Questions to Ask |
|------|------------------|
|      |                  |
|      |                  |
|      |                  |


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