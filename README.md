# Project Overview

This project collects and analyzes data from publicly listed World of Warcraft private servers on TopG.org.

The objectives of the project were to:

practice web scraping using Python & BeautifulSoup

build a structured dataset from a paginated website

explore trends across expansions, patches, and ranking positions

design a Power BI dashboard for insights and storytelling

create supporting Python visualizations and EDA

Only the first 3 listing pages were scraped for this analysis.

This project was created strictly for learning purposes.

## Please Read!!!!

## ⚠ Ethical & Data Responsibility Notice

Only publicly visible listing information was scraped

No authentication, login areas, or restricted pages were accessed

No user data, emails, or personal information was collected

Data is used only for educational / analytical practice

## Data Fields Extracted

Field	Description
Server Name	Public listing title
Rank	Position on TopG page
Expansion	Detected expansion
Patch Version	Patch label (when available)
URL	Server listing link

## Data pipeline:

Python dictionary → Pandas dataframe → CSV export → Power BI dashboard

Pagination was applied across pages 1–3.

## Key Insights

From the analysis:

Wrath of the Lich King is the dominant expansion (84 tracked servers)

Patch 3.3.5a is overwhelmingly the most common version, indicating strong ecosystem standardization around late-WotLK builds

Wrath and TBC servers tend to achieve better average rankings, suggesting higher stability & player engagement

Newer expansions (e.g., Dragonflight) appear less frequently and rank lower on average

These trends likely reflect:

community nostalgia preferences

technical maturity of older cores

development stability around WotLK patches

## Power BI Dashboard

The dashboard analyzes:

number of servers per expansion

patch version popularity

average rank by expansion

overall ranking distribution

Dashboard includes:

KPI metrics (Total Servers, Expansions, Rank Median)

Server count by expansion

Server count by patch

Average rank by expansion

Dataset notes & limitations

Screenshots are included in the repository.

## Tools & Libraries

__Python__

__requests__

__BeautifulSoup__

__pandas__

__numpy__

__Environment__

__Jupyter Notebook__

__Visualization__

__Power BI__

## Future Improvements

Planned next steps:

collect server population / activity metrics

automate periodic re-scraping to track changes over time

classify servers by type (PvE / PvP / Blizzlike)

compare expansion age vs ranking stability

## Source Website

TopG — WoW Private Servers:
https://topg.org/wow-private-servers/

## PowerBI Overview

<img width="1969" height="1112" alt="dashboard_preview" src="https://github.com/user-attachments/assets/db8a687f-817e-4235-b6c7-3c96ffdfc668" />



