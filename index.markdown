---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Exploring San Francisco’s Theft Spike in 2018

---

Welcome to our interactive data story! This page walks you through three visualizations that reveal insights about the rise in thefts in San Francisco, especially in 2018.

San Francisco has struggled with theft for years, but 2018 saw a significant spike. Using crime data from the San Francisco Police Department (SFPD) covering 2003 to 2025, we’ll explore how theft patterns changed over time, the most common types of theft in 2018, and the areas most affected.

<br>

## About the Data  
This data comes from SFPD’s crime reports, which track different types of crimes, including larceny/theft. The dataset includes details like crime category, police district, description, and date and time of occurrence.

<br>
<hr>
<br>

## Theft Trends Over Time

Our [first chart](#vis1) shows reported larceny/theft incidents from 2003 to 2025. The numbers steadily rose after 2012, peaking in 2018 with over 57,000 cases.

One major factor behind this spike was a rise in car break-ins and organized retail theft. At one point, San Francisco had the highest rate of car break-ins compared to cities like Atlanta, Washington D.C., Dallas, and Los Angeles [[1]](#references). 

The data also shows a big drop in thefts in 2020, likely due to the COVID-19 pandemic and lockdowns, which kept people off the streets.

<div id="vis1">
  <img src="/assets/images/Visualization1.png" alt="Crime Data Visualization" />
  <p><em>Bar chart showing the number of reported larceny/theft incidents in San Francisco from 2003 to 2025.</em></p>
</div>

<br>

## What Kind of Thefts Happened in 2018?

Looking deeper into 2018, our [second visualization](#vis2) categorizes the various types of theft reported during this peak year. The most common were auto theft and vehicle stripping, followed closely by property larceny.

There’s also a notable presence of shoplifting, suggesting organized theft groups that targeted retail stores.

<div id="vis2">
  {% include Visualization2.html %}
  <p><em>Stacked bar chart categorizing theft incidents in San Francisco during 2018.</em></p>
</div>

<br>

## Where Did These Crimes Happen?

Our [last visualization](#vis3) maps out where thefts happened in San Francisco, showing that areas like Central, Tenderloin, Northern, and Southern had the most incidents. This pattern stayed the same throughout the year, highlighting consistent problem areas for theft in the city. 

You can press play to see it yourself!


<div id="vis3">
  <iframe src="{{ '/assets/maps/Visualization3.html' | relative_url }}" width="100%" height="600px"></iframe>
  <p><em>Map showing theft incidents across all areas of San Francisco in 2018.</em></p>
</div>

<br>
<hr>
<br>

## Why Was This Happening?

One big issue was organized crime - many of these thefts weren't random but planned by groups that know how to avoid getting caught.

From 2018, SFPD increased patrols in high-crime areas, like the Central district, but according to Assistant Police Chief Michael Redmond, the city is still short about 500 officers [[1]](#references).
 
Laws are also changing to tackle theft. For example, Senator Scott Wiener introduced Senate Bill 905, which aims to close legal loopholes that make it harder to prosecute auto burglars [[2]](#references). 

<br>

## Final Thoughts

San Francisco’s 2018 theft spike was driven by a mix of factors - organized crime, car break-ins, and retail theft. The numbers have changed over the years, especially in response to events like COVID-19. But theft remains a challenge, and tackling it requires better policing, policy changes, and awareness.

Check out the visualizations and see what other trends you notice!

<br>

## References {#references}

[1] Shaban, B., Campos, R., Carroll, J., & Villarreal, M. (2021, November 16). Breaking point: SF suffers highest rate of car break-ins compared to Atlanta, DC, Dallas, LA. NBC Bay Area.  [Link to Reference](https://www.nbcbayarea.com/investigations/breaking-point-sf-suffers-highest-rate-of-car-break-ins-compared-to-atlanta-dc-dallas-la/2731757/)

[2] Senate passes senator wiener bills to crack down on car break-ins. (n.d.). Senator Scott Wiener. [Link to Reference](https://sd11.senate.ca.gov/news/senate-passes-senator-wiener-bills-crack-down-car-break-ins?utm_source=chatgpt.com)