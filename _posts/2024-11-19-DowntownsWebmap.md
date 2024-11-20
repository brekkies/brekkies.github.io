---
title: Bay Area Suburban Downtowns
date: 2024-11-17 18:00:00 -0800
categories: [Data Visualization, Urbanism]
tags: [qgis,postgis,sql,gis]     # TAG names should always be lowercase
---

# Part 1 in my attempt to rank every Bay Area downtown

In Summer 2023, a friend and I went on a quest to rank all of the downtowns in the Bay Area. We visited all the downtowns and created a tier list ranking them from S-tier to F-tier. However, we caught a lot of flak as we showed off our tier list. We faced accusations of bias (I plead not guilty) and others pointed out several missing downtowns (sorry Sunnyvale). 

![Tierlist v1.0](/assets/OrginalTierlist.png)

**To add more weight to my rankings, I am embarking on a journey to make a data-driven ranking of downtowns in my region.** 

To kick things off, I tried to find official data that demarcated the boundaries for each downtown. This proved to be complicated. OpenStreetMap did not have such data and zoning codes are remarkably inconsistent between jurisdictions. However, I managed to find one dataset with all the zoning codes in CA. From there, I manually selected and validated each jurisdiction's downtown. Of the 101 municipalities in the Bay Area's nine counties, I found 64 unique downtowns. Below is a map showing their locations and extents. Please feel free to review the map and email me with feedback before I embark on actually ranking them!


### [Check out the map here!](https://brekkies.github.io/Bay-Area-Downtowns-Webmap/)

## Note on exclusions
I am excluding San Francisco from this ranking. If I didn't, it would simply be unfair. I am also excluding more urban downtowns, such as Oakland, Berkeley, and San Jose. Again, these cities are clearly in a league of their own. Each has more suburban downtowns which made the list, however.
