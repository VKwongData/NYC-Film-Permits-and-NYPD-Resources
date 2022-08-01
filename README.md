# Analysis of the Burden of Film Permits on NYPD Resources Using R Markdown

This is a repository for my final class project for the course STA/OPR9750 Software Tools for Data Analysis (Fall 2021 semester) at the Zicklin School of Business. This was an individual class project and involved using R Markdown to create a PDF report.

## Introduction

The goal of this analysis was to study the NYC Open Data dataset that had information on film permits and to analyze it from the perspective of how much of a burden they were on NYPD resources. To do this, three datasets had to be utilized: 

<ol>
<li><a href="https://data.cityofnewyork.us/City-Government/Film-Permits/tg4x-b46p">Film permit data provided by the Mayor’s Office of Media and Entertainment</a></li>
<li><a href="https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz">NYPD precinct map data</a></li>
<li><a href = "https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Current-Year-To-Date-/5uac-w243">NYPD complaint data</a></li>
</ol>

Permits are required with productions that use large equipment in public locations or production vehicles that require parking privileges. Additionally, any production that needs exclusive use of NYC-owned property, or uses prop weapons, prop vehicles, actors in police uniform or stunts is required to file a permit. Most uses of a permit require the assistance of the NYPD Movie/TV Unit, which provides its services free of charge to media productions. Services range from posting No Parking Orders to lending NYPD presence for safety and crowd-control purposes. Therefore, any NYPD precinct that serves an area for which a large number of film permits are filed will have to dedicate resources towards handling the privileges provided to production crews. 

## R Packages Used

<ul>
<li><b>sf:</b> used to encode spatial vector data</li>
<li><b>tidyverse:</b> a set of packages used in everyday data analysis. Tidyverse packages used in this project include:
<ul>
<li><b>readr:</b> to read in data</li>
<li><b>dplyr:</b> to manipulate and transform data, such as through filtering, mutating, arranging or grouping</li>
<li><b>ggplot2:</b> to create graphics to visualize data</li>
</ul>
</li>
</ul>

## Relevant Files in Repository

<ul>
<li><a href="https://github.com/VKwongData/NYC-Film-Permits-and-NYPD-Resources/blob/main/NYC%20Film%20Permits%20and%20NYPD%20Resources%20-%20R%20Markdown.rmd">R Markdown Code</a>: the code used to generate the PDF report</li>
<li><a href="https://github.com/VKwongData/NYC-Film-Permits-and-NYPD-Resources/blob/main/NYC%20Film%20Permits%20and%20NYPD%20Resources_Report.pdf">R Markdown Report</a>: the PDF report generated from R Markdown, including comments, code chunks and written analysis</li>
</ul>

Other files included in this repository were additional files imported into R Markdown. 





