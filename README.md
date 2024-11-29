# personal-browsing-patterns
## Description
This is a term project for Sabanci University course DSA210 (Introduction to Data Science) Fall 2024 - 2025. This project dives into the patterns and behaviors hidden within my personal browser history, turning everyday clicks and searches into meaningful insights. It's an exploration of my digital habits, revealing trends and unlocking stories from my online journey.

Final Website / short video / report. (To ADD).
***
## Table of Contents
1. [Motivation](#motivation)

2. [Project Details](#project-details)
   - [Important Information!](#important-information)
   - [Data Source](#data-source)
***
### Motivation
While brainstorming for a project idea, I realized that a significant part of my interaction with the world happens through my web browser. It serves as my gateway to knowledge, entertainment, and exploration. This sparked the idea to analyze my personal browsing history.

The motivation behind this analysis is to uncover patterns and trends in my online activities. By examining the websites I visit, the time I spend online, and the frequency of my searches, I hope to gain a better understanding of my digital habits, interests, and how I allocate my time across various platforms.
***
### Project Details
#### Important Information!
This project utilizes techniques like Exploratory Data Analysis (EDA), data visualization, and machine learning models to uncover insights from my browsing history. While raw data remains private for privacy reasons, analysis scripts will be shared for transparency and reproducibility. A .gitignore file is used to keep the repository clean and organized, ensuring sensitive data is excluded.

#### Data Source
The data for this project is sourced primarily from my browser history, collected through two methods:

1. **History Trends Unlimited Extension**  
   I use Google Chrome as my primary browser, and the majority of the data is gathered using the *History Trends Unlimited* extension. This extension syncs my browsing history to a local database, circumventing Chrome’s approximate 3-month history limit. The extension ensures data privacy by storing all history locally, without sharing it over a network. It allows me to export raw browsing data, providing a detailed record for analysis. Features like search filters further help refine the data for this project. For more information on this tool, visit the extension’s page [here](https://chromewebstore.google.com/detail/history-trends-unlimited/pnmchffiealhkdloeffcdnbgdnedheme).

2. **Default Chrome History System**  
   In addition to using the extension, I rely on Chrome’s native history system for recent browsing activities. Although it has limitations in terms of the time range and depth of data, it serves as a complementary source for quick insights and comparison.

To collect this data, I used the export functionality provided by the *History Trends Unlimited* extension, which generates a detailed dataset from my local history database. The default Chrome history system served as a reference for validating and supplementing this data. 

These combined sources offer a rich dataset to analyze patterns and trends in my online activities while maintaining strict privacy by keeping all data stored locally.
