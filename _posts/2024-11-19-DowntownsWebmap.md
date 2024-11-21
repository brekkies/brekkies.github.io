---
title: Ranking Bay Area Downtowns - Part 1
date: 2024-11-17 18:00:00 -0800
categories: [Data Visualization, Urbanism]
tags: [qgis,postgis,sql,gis]     # TAG names should always be lowercase
---


In Summer 2023, a friend and I went on a quest to rank all of the downtowns in the Bay Area. We visited each downtown and created a tier list ranking them from S-tier to F-tier. Proud as we were of our efforts, we caught a lot of flak for our rankings. We faced accusations of bias (I plead not guilty) and others pointed out several missing downtowns (sorry Sunnyvale). The original list is shown below.

![Tierlist v1.0](/assets/OriginalTierlist.png){: width="100" }


**To prove the haters wrong, I am embarking on a journey to make a data-driven ranking of these downtowns.** 

To kick things off, I tried to find official data that demarcated the boundaries for each downtown. This proved to be complicated. OpenStreetMap did not have such data and zoning codes are remarkably inconsistent between jurisdictions. However, I managed to find one dataset with all the zoning codes in CA. From there, I manually selected the zoning codes corresponding to each jurisdiction's downtown. Of the 101 municipalities in the Bay Area, I found 64 unique downtowns! Below is a map showing their locations and extents. Please feel free to review the map and email me with feedback before I embark on actually ranking them!


### [Check out the map here!](https://brekkies.github.io/Bay-Area-Downtowns-Webmap/)

## Criteria for inclusion
What counts as a downtown? I have yet to find a compelling definition. My working definition of a downtown is an outdoor, retail-oritented space designed to encourage pedestrian activity.
This means a few things. Indoor malls and strip malls are excluded from consideration. If the facade of most shops faces a parking lot, I won't consider it. Additionally, I am choosing to focus on suburban downtowns. 
Thus, I won't rank downtown San Jose, Oakland, or Berkeley. Furthermore, I am excluding all of San Francsico from the rankings on the grounds of fairness. Sorry, they are just too good.