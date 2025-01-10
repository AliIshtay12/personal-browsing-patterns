# personal-browsing-patterns
## Description
This is a term project for Sabanci University course DSA210 (Introduction to Data Science) Fall 2024 - 2025. This project dives into the patterns and behaviors hidden within my personal browser history, turning everyday clicks and searches into meaningful insights. It's an exploration of my digital habits, revealing trends and unlocking stories from my online journey.

This README file contains an overview of the project. For the full analysis and project details, check the [project report here](https://docs.google.com/document/d/1xa0wo7gSF7Dr0b5PIVhqm1TfehyOi1VOCgi99xjv-Fw/edit?usp=sharing).
***
## Table of Contents
1. [Motivation](#motivation)

2. [Data Source](#data-source)

3. [Data Analysis](#data-analysis)

4. [Findings](#findings)

5. [Limitations and Future Work](#limitations-and-future-work)
***
### Motivation
While brainstorming for a project idea, I realized that a significant part of my interaction with the world happens through my web browser. It serves as my gateway to knowledge, entertainment, and exploration. This sparked the idea to analyze my personal browsing history.

The motivation behind this analysis is to uncover patterns and trends in my online activities. By examining the websites I visit and the frequency of my searches, I hope to gain a better understanding of my digital habits, interests, and how I allocate my efforts across various platforms.
***
### Data Source
The data for this project is sourced primarily from my browser history, collected through:

1. **History Trends Unlimited Extension**  
   I use Google Chrome as my primary browser, and the majority of the data is gathered using the *History Trends Unlimited* extension. This extension syncs my browsing history to a local database, circumventing Chrome’s approximate 3-month history limit. The extension ensures data privacy by storing all history locally, without sharing it over a network. It allows me to export raw browsing data, providing a detailed record for analysis. Features like search filters further help refine the data for this project. For more information on this tool, visit the extension’s page [here](https://chromewebstore.google.com/detail/history-trends-unlimited/pnmchffiealhkdloeffcdnbgdnedheme).

To collect this data, I used the export functionality provided by the *History Trends Unlimited* extension, which generates a detailed dataset from my local history database.

This source offers a rich dataset to analyze patterns and trends in my online activities while maintaining strict privacy by keeping all data stored locally.
***
### Data Analysis

The **Data Analysis** section of the project combines Exploratory Data Analysis (EDA), hypothesis testing, and machine learning techniques to uncover meaningful insights about personal browsing patterns. It employs tools like **Pandas**, **Matplotlib**, and **scikit-learn** to analyze and visualize trends.

#### Key Highlights:
- **EDA**: Patterns in temporal behaviors (e.g., weekday vs. weekend activity), academic vs. non-academic activity, and browsing spikes were examined using descriptive statistics and visualizations.
- **Hypothesis Testing**: Statistical tests like the Chi-Square test revealed significant relationships between academic cycles and browsing behavior.
- **Machine Learning**: A Random Forest Classifier was trained to classify activities as academic or non-academic. While achieving moderate accuracy (78%), the model highlighted challenges with class imbalance, prompting opportunities for further refinement.

This analysis not only demonstrates the alignment of digital habits with academic cycles but also provides a framework for improving productivity and understanding behavioral trends.
***
### Findings

The **Findings** section reflects on insights gained from analyzing personal browsing data. It highlights how browsing patterns align with academic responsibilities and lifestyle habits. Key takeaways include:

- **Academic vs. Non-Academic Behavior**: A clear increase in academic browsing during exam periods, while non-academic activity dominated weekends and breaks.
- **Temporal Patterns**: Mornings and afternoons were found to be more productive, with a noticeable decline in academic activity during evenings and weekends.
- **Machine Learning Insights**: The Random Forest model underscored the importance of temporal and academic period features in predicting activity types, though performance was limited by class imbalance.

Overall, the findings provide a deeper understanding of digital habits, offering actionable insights to improve productivity and align online behaviors with academic goals.

***
### Limitations and Future Work

The **Limitations and Future Work** section addresses areas for improvement and plans for extending the project's scope. Key points include:

- **Limitations**:
  - The machine learning model struggled with class imbalance, impacting prediction quality.
  - Features like content type and browsing intent were not fully explored, leaving room for greater contextual understanding.
  
- **Future Directions**:
  - Enhance features by integrating detailed content categorization (e.g., social media, streaming, academic).
  - Experiment with advanced machine learning models like gradient boosting or neural networks for better performance.
  - Collaborate with peers and advisors to gain new perspectives and refine methodologies.
  - Expand the project’s applicability by creating a framework to help others analyze their digital habits.

This project is a promising starting point for understanding digital behavior and its relationship with productivity, with exciting possibilities for future exploration and refinement.
