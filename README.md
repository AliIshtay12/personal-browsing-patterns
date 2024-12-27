# personal-browsing-patterns
## Description
This is a term project for Sabanci University course DSA210 (Introduction to Data Science) Fall 2024 - 2025. This project dives into the patterns and behaviors hidden within my personal browser history, turning everyday clicks and searches into meaningful insights. It's an exploration of my digital habits, revealing trends and unlocking stories from my online journey.

For the final report see here. (TO ADD)
***
## Table of Contents
1. [Dataset and Project Plan](#dataset-and-project-plan)
   - [Project Idea](#project-idea)
   - [Project Plan](#project-plan)
   - [Dataset Description](#dataset-description)

3. [Motivation](#motivation)

4. [Project Details](#project-details)
   - [Important Information!](#important-information)
   - [Data Source](#data-source)
   - [Data Analysis](#data-analysis)
   - [Findings](#findings)
   - [Limitations and Future Work](#limitations-and-future-work)
***
### Dataset and Project Plan
This section provides an overview of the project concept, outlines the plan for conducting a successful analysis, and includes a description of the dataset.

#### Project Idea
In today’s digital age, our online activities reflect a significant part of our daily lives, providing insights into our habits, interests, and priorities. This project aims to analyze my personal browser history to uncover patterns and trends that define my interaction with the digital world. By examining the websites I visit, the time spent online, and the frequency of my activity, the project seeks to understand how my online behavior reflects my broader lifestyle and interests. This analysis highlights the growing relevance of web history as a tool for self-reflection and behavioral understanding.

#### Dataset Description

The dataset for this project consists of approximately 6 months of browsing history, spanning from **Monday, June 3, 2024**, to **Saturday, November 30, 2024**. It includes a total of **16,814 unique URLs** visited **65,841 times**. This comprehensive dataset captures detailed information about my online activity, providing a rich basis for analysis.

#### Key Statistics:
- **Daily Stats**:
  - Average Visits Per Day: **369**
  - Median Visits Per Day: **289**

- **Top 5 Most Visited Domains**:
  1. `sabanciuniv.edu`: **25,630 visits**
  2. `google.com`: **18,073 visits**
  3. `youtube.com`: **3,704 visits**
  4. `chatgpt.com`: **1,268 visits**
  5. `github.com`: **1,104 visits**

#### Data Structure:
The dataset was exported using the *History Trends Unlimited* extension, which generates a tab-delimited file with the following columns:
- **URL**: The full address of the visited webpage (e.g., `http://example.com`).
- **Host**: The hostname of the URL (e.g., `subdomain.example.com`).
- **Domain**: The top-level domain of the URL (e.g., `example.com`).
- **Visit Time (ms)**: Timestamp of the visit in milliseconds since January 1, 1970.
- **Visit Time (string)**: Readable timestamp in the format `YYYY-MM-DD HH:MM:SS`.
- **Day of Week**: Numerical representation of the weekday (Sunday=0, Monday=1, etc.).
- **Transition Type**: Describes how the browser navigated to the URL (e.g., link, typed, reload).
- **Page Title**: The title of the webpage visited.

#### Insights Potential:
This dataset provides a detailed lens to explore browsing trends, identify frequently visited websites, and analyze time-based activity patterns. A particular focus of this project is to observe how my online behavior changes during my college exam periods, offering insights into the impact of academic stress and deadlines on my digital habits.

#### Project Plan

As a student, my web browsing patterns often mirror the highs and lows of academic life—late-night study sessions, frantic research before deadlines, or leisurely breaks exploring interests beyond coursework. The goal of this project is to dive deep into my browser history and uncover how my online behavior shifts during key academic periods like exams, assignments, and breaks.  

To kick off the project, I conducted an initial round of **Exploratory Data Analysis (EDA)** to ensure the dataset meets expectations and provides enough depth for meaningful insights. This early step was crucial for confirming that my data is both accurate and rich enough to capture the essence of my digital habits as a student.  

From here, the project will follow a structured, yet flexible plan:  
1. **Data Visualization**  
   Bringing the data to life through graphs and charts that tell the story of how my browsing habits evolve—whether it’s a spike in academic websites during finals week or a shift to entertainment sites during breaks.  

2. **Pattern Analysis**  
   Identifying hidden trends, like the times of day I’m most active online or how certain academic deadlines influence the types of websites I visit. This step will aim to answer how my online behavior reflects my priorities as a student.  

3. **Machine Learning Models**  
   Leveraging machine learning to explore deeper insights, like clustering my browsing patterns into "study mode," "relaxation mode," or "procrastination mode." The models might even predict when I’m entering a stressful academic period based on my web activity.

This project isn’t just about analyzing data—it’s about understanding myself as a student in today’s digital age. By drawing connections between my academic life and online habits, I hope to create a blueprint for self-awareness, helping me (and potentially other students) make better use of time and digital resources during key academic periods.
***
### Motivation
While brainstorming for a project idea, I realized that a significant part of my interaction with the world happens through my web browser. It serves as my gateway to knowledge, entertainment, and exploration. This sparked the idea to analyze my personal browsing history.

The motivation behind this analysis is to uncover patterns and trends in my online activities. By examining the websites I visit, the time I spend online, and the frequency of my searches, I hope to gain a better understanding of my digital habits, interests, and how I allocate my time across various platforms.
***
### Project Details
#### Important Information!
This project utilizes techniques like Exploratory Data Analysis (EDA), data visualization, and machine learning models to uncover insights from my browsing history. While raw data remains private for privacy reasons, analysis scripts will be shared for transparency and reproducibility. A .gitignore file is used to keep the repository clean and organized, ensuring sensitive data is excluded.

### Data Source
The data for this project is sourced primarily from my browser history, collected through two methods:

1. **History Trends Unlimited Extension**  
   I use Google Chrome as my primary browser, and the majority of the data is gathered using the *History Trends Unlimited* extension. This extension syncs my browsing history to a local database, circumventing Chrome’s approximate 3-month history limit. The extension ensures data privacy by storing all history locally, without sharing it over a network. It allows me to export raw browsing data, providing a detailed record for analysis. Features like search filters further help refine the data for this project. For more information on this tool, visit the extension’s page [here](https://chromewebstore.google.com/detail/history-trends-unlimited/pnmchffiealhkdloeffcdnbgdnedheme).

2. **Default Chrome History System**  
   In addition to using the extension, I rely on Chrome’s native history system for recent browsing activities. Although it has limitations in terms of the time range and depth of data, it serves as a complementary source for quick insights and comparison.

To collect this data, I used the export functionality provided by the *History Trends Unlimited* extension, which generates a detailed dataset from my local history database. The default Chrome history system served as a reference for validating and supplementing this data. 

These combined sources offer a rich dataset to analyze patterns and trends in my online activities while maintaining strict privacy by keeping all data stored locally.

### Data Analysis

### Findings

### Limitations and Future Work
