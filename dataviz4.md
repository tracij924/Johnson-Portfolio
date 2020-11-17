# **Assignment 4 - Grant Distribution Data**

I selected data that could be found on the Foundation Center website. This chart was created as a visual for some data mapping
done at the Foundation Center now known as Candid.  Foundations are able to voluntarily submit data on their grantmaking and Candid maps the data.
The data is freely accessible along with the charts. But you can not download it.  The chart that I set out to recreate is grant distribution
data for Early Childhood Education in the United States.

Here is a link to the data:
[Data Visualization](https://maps.foundationcenter.org/#/charts/?subjects=all&popgroups=all&years=all&location=6252001&excludeLocation=0&geoScale=ADM1&layer=recip&boundingBox=-157.060546875,18.729501999072138,-47.02148437499999,58.12431960569374&gmOrgs=all&recipOrgs=all&tags=all&keywords=&pathwaysOrg=&pathwaysType=&acct=earlychildren&typesOfSupport=all&transactionTypes=all&amtRanges=all&minGrantAmt=0&maxGrantAmt=0&gmTypes=all&minAssetsAmt=0&maxAssetsAmt=0&minGivingAmt=0&maxGivingAmt=0&andOr=0&includeGov=1&custom=all&customArea=all&indicator=&dataSource=oecd&chartType=bars&multiSubject=1&listType=gm&windRoseAnd=undefined&zoom=4)


I found the visualization to be basic but not intuitive at first glance.  This tool is used by grant seekers and grantmakers.
It was not clear what story Candid was trying to tell with this data.  The title also didn't bring clarity to the story as well.
I found myself questioning if Candid was making a comparison between states and if so how. I also wondered about the significance
of the Total Number Of Grants.  I also began to question that with an invesment of $9.6 billion why did that amoun to less than
200,000 grants given.  So I decided to use a portion of this data and this visualization to tell a story about investment not keeping pace with grants given by state.


I first started by wanting to make changes to the visualiation and the amount of data used.  I liked the use of black and gray as colors.  I also liked that the data was labeled. I liked the use of the bar chart but I don't like how the bars are going in the same direction. I would opt to pair them if possible going in the same direction or I would have them going in opposite directions and give color to the bars that I wanted to use as the center of my story. I would also change the title for clarity.

So I started with this basic wire frame:

![Wireframe](https://github.com/tracij924/Johnson-Portfolio/blob/main/Data%20Project%20Assg%204.png)

This was my rough sketch and basic idea. I kept the bar chart and I started with all of the bars going in the same direction.

I then moved to some detailed draft sketches for to get feedback from peers.


## **Sketch 1**
![Sketch1](https://github.com/tracij924/Johnson-Portfolio/blob/main/IMG_0997.jpg)


## **Sketch 2**
![Sketch2](https://github.com/tracij924/Johnson-Portfolio/blob/main/IMG_0998.jpg)


I got feedbback from a classmate and a co-worker.  They liked both charts but the they liked the second one more.  My classmate remarked that sketch 2 had a cleaner look. She also liked the choice of colors and felt the titles was strong and informative.  My co-worker thought that by separating the bars as in sketch 2 would do a better job of conveying the message that the investment amount and the grants given are not quite in sync.  She also thought the chart could lead the viewer to ask questions about impact and the dispproportionate funding of organizations that are lead by and serve Black, Indigenous people of color.

So, I decided to go with sketch 2.  I decided to work in Tableau.  As I was trying to create this new visualization, I was unable to do what I have sketched. So, I decided on a butterfly bar chart.  This enabled me to break up the bars and give the chart that clean look.  I kept the color scheme and highlighted with color the disparity in the grants given as compared to the philanthropic investment.

So here is my recreated chart:

<divclass='tableauPlaceholder'id='viz1605640171186'style='position:relative'><noscript><ahref='#'><imgalt=''src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ea&#47;EarlyChildhoodGrantInvestmentver_2&#47;Sheet1&#47;1_rss.png'style='border:none'/></a></noscript><objectclass='tableauViz'style='display:none;'><paramname='host_url'value='https%3A%2F%2Fpublic.tableau.com%2F'/><paramname='embed_code_version'value='3'/><paramname='site_root'value=''/><paramname='name'value='EarlyChildhoodGrantInvestmentver_2&#47;Sheet1'/><paramname='tabs'value='no'/><paramname='toolbar'value='yes'/><paramname='static_image'value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ea&#47;EarlyChildhoodGrantInvestmentver_2&#47;Sheet1&#47;1.png'/><paramname='animate_transition'value='yes'/><paramname='display_static_image'value='yes'/><paramname='display_spinner'value='yes'/><paramname='display_overlay'value='yes'/><paramname='display_count'value='yes'/><paramname='language'value='en'/><paramname='filter'value='publish=yes'/></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1605640171186'); var vizElement=divElement.getElementsByTagName('object')[0]; vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';varscriptElement=document.createElement('script');scriptElement.src='https://public.tableau.com/javascripts/api/viz_v1.js'; vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>
