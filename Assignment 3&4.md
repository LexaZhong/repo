Redesigning makeovermonday visualization:
[NCAA D1 Players Demographics](https://scholarshipstats.com/ncaa1basketbal)

# 1. Sketching the Solution with Tableau
## - NCAA D1 Women's Players Height Distribution - Version 1.0
<div class='tableauPlaceholder' id='viz1707181801693' style='position: relative'><noscript><a href='#'><img alt='NCAA D1 Women&#39;s Basketball Players by Height 23-24 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;wb&#47;wbb_sketches&#47;wbbplayersheightv2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='wbb_sketches&#47;wbbplayersheightv2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;wb&#47;wbb_sketches&#47;wbbplayersheightv2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1707181801693');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

**Thoughts**
Although the bars are showing the distribution of players height, they are too far apart and it is hard to refer to the y-axis. I tried making the blocks bigger, but they start to overlap and it does not look good.

## - NCAA D1 Women's Players Height Distribution - Version 2.0
<div class='tableauPlaceholder' id='viz1707182373408' style='position: relative'><noscript><a href='#'><img alt='NCAA Women&#39;s Basketball Players by Height Distribution 2023-24by primary position: Guard, Forward &amp; Center ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;wb&#47;wbb_sketches&#47;wbbplayersheightbydivision&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='wbb_sketches&#47;wbbplayersheightbydivision' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;wb&#47;wbb_sketches&#47;wbbplayersheightbydivision&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1707182373408');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

**Thoughts**
The polygons are working well to show the distribution. And it is easier to compare the difference in the three positions. I chose blues first according to the original visualization.



# 2. Interviews
## Qing Lin (Mid 20s, student)
1. Can you tell me what you think this is?
- This is the height distribution of women basketball players. 
2. Can you describe to me what this is telling you?
- This tells me that these three positions have different heights, guards are shorter, centers are taller. Also, there are fewer centers compared to forwards and guards.
3. Is there anything you find surprising or confusing?
- Do the polygons overlap or pile upon each other? 
- Why there are fewer centers?
4. Who do you think is the intended audience for this?
- Student athletes who want to play in NCAA D1. And people who are interested in basketball players data?
5. Is there anything you would change or do differently?
- I would change the opacity of the polygons so that you can tell they are overlapping each other.
- Adding college women's basketball players image into the graph as a reference.

## Xiaohan Liu (Mid 20s, student)
1. Can you tell me what you think this is?
- This is the height distribution of women basketball players. (but she does not know about NCAA and the divisions of NCAA)
2. Can you describe to me what this is telling you?
- The graph tells me that "guards" are shorter, and there are more people playing guards. There are fewer centers.
3. Is there anything you find surprising or confusing?
- What does 23-24 mean, is it age? 
- I can't really match the color to the corresponding positions.
4. Who do you think is the intended audience for this?
- Maybe students who are playing in high school to see if they want to play in a college team, which range do they fall in and what position they can play?
5. Is there anything you would change or do differently?
- The colors are too similar, it is hard to match the colors. I would choose more contrasting colors.
- The title needs to be clearer.



# Building Solutions
<img width="835" alt="NCAA_D1_WBB_height" src="https://github.com/LexaZhong/repo/assets/156933041/8835ac15-b2c2-4555-98d1-68f3254d3fc6">

## Why I chose this visualization
- The height data of NCAA D1 women's basketball players is a data-driven and delaring visualization. The purpose of the graph is to present the existing situation to the audience, so that they could get an overall idea of how tall you needs to be to play in D1. Therefore, I used the combination of Tableau and powerpoint to create the final visualization.
- I chose the polygons to show the height distribution because it clearly display the volume and range at the same time. By putting the height in the y-axis, it is quite straightforward: taller players fall in the upper part of the graph. 
- After interviewing my friends, I made changes to the colors, title, and added image into the graph.
    - First, I change the opacity to 80% to show that the polygons are overlapping each other. Then I change the blues into red and grey, which are the colors related to the US national team in order to match the images of the national players.
    - For the title, I moved "Height Distribution" to the front. I found it took people some time to comprehend the graph the title does not say it is a distribution graph at the very beginning.
    - By adding the U19 national players' images into the graph make it more vivid. They are all about the average of their corresponding positions instead of being extremely tall, conveying the message that as long as you fall in the average range of the height, it is possible to play in NCAA D1 or even better.
