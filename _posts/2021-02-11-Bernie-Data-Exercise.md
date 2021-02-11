---
layout: post
title: "Quick Bernie Data Exercise: March 2020 Contributions"
date: 2021-02-11
---

<div class='tableauPlaceholder' id='viz1613061172709' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;Bernie-March2020&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Bernie-March2020&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Be&#47;Bernie-March2020&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1613061172709');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1227px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

# Bernie - March 2020

This was a quick data exploration challenge looking at the March 2020 individual contributor data from the FEC for Bernie Sanders' 2020 Presidential Campaign [[data here]](https://www.fec.gov/data/receipts/individual-contributions/?committee_id=C00696948&two_year_transaction_period=2020&min_date=03%2F01%2F2020&max_date=03%2F31%2F2020).  The intended time limit for this analysis was 20-25 minutes so my visualizations are basic/unoptimized and the insights below are just what I could glean quickly.

**Occupation**

The high cardinality of this data made it hard to work with; often the case with user input fields.  With more time, I'd try to build subcategories by industry.  The most readily apparent takeaway here is ~20% of Bernie's donations during this period came from those who identified themselves as 'Not Employed'.  You could interpret this as Bernie's message and platform appealing more to those not currently working but 'Not Employed' is likely just the largest category of people above the voting age.  My assumption is that while those Unemployed not by their own choice are counted here, Retirees are also likely to fall into this category.

**Employer**

Once again the data here shows a significant portion of contributions came from those not currently working.  It'd be interesting to do further analysis on average contribution amounts and see how that unemployment affects how much people are willing to give.  The category of 'Self-Employed' is also significant here; I see this as a reminder that although the US economy may be dominated by large firms, many Americans also work for themselves or in small businesses.

**State**

My initial expectation with the state level data was that it would track quite closely with the population.  I tried to show absolute contributions tempered with the average $ value of those contributions in my visualization.

**Rate Over Time**

I started with a quick visualization with just contributions over time and was able to detect major political milestones (Super Tuesday, the March 15th debate) just based on the changes in donation volume.  I built this second graph in hopes that I'd maybe be able to see those events on a state by state level (primaries/campaign stops).  Definitely some work to be done here to make that hope viable.

