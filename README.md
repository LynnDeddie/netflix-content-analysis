# content-analysis
##Project 1: Netflix Content Analysis
Project Overview

This project involves cleaning and analyzing a Netflix titles dataset, which includes shows and movies released on the platform. The goal was to uncover meaningful insights such as the most common genres, the distribution of content over the years, and how various metrics like runtime, type, and production countries affect content on Netflix.
Tools Used

    Python (Pandas, NumPy)

    Jupyter Notebook

    (Optional: Matplotlib/Seaborn – to be added)

 Key Tasks Performed

    Data Cleaning

        Handled missing values

        Removed redundant/irrelevant entries

        Converted data types (e.g., year, ratings)

        Created a content_age column to reflect how old the content is

    Feature Engineering

        Extracted new insights like:

            Content age (2025 - release_year)

            Aggregated genres and production countries

        Grouped and counted various fields like type, release years, and genres

    Insights & Analysis

        Most popular content type (movies vs. shows)

        Most common genres (e.g., comedy, drama)

        Years with highest releases

        Most frequent production countries

        Observed distribution of runtime and content aging

Sample Insights

    The most frequent type on Netflix is Movie

    The most common genre is Comedy

    2019 had the highest number of releases
    
    
    Why This Matters

Netflix relies heavily on analytics to decide what content to recommend, renew, or acquire. This type of data analysis mimics real-world business intelligence work, where data-driven decisions improve user experience and engagement.



    ##Project 2: World Happiness Report Analysis
    Project Overview

This project dives into the World Happiness dataset, analyzing happiness scores across countries, regions, and time. The primary goal was to understand what regions are the happiest, how countries rank, and to engineer new features to support these insights.
 Tools Used

    Python (Pandas)

    Jupyter Notebook

 Key Tasks Performed

    Data Cleaning

        Checked and handled missing values

        Standardized region names

        Cleaned up scoring columns and removed inconsistencies

    Feature Engineering

        Created happiness_ratio (normalized happiness score)

        Mapped regions to new region IDs

        Grouped countries by average score

        Extracted top 10 happiest countries

    Insights & Analysis

        Highest-ranking regions in happiness

        Average happiness per country

        Regions with highest average happiness scores

Sample Insights

    Norway, Denmark, and Iceland were among the top 3 happiest countries

    The region with the highest happiness score was Western Europe

    Feature engineering helped categorize regions into IDs for easier grouping

 Why This Matters

Understanding happiness across regions can help governments, NGOs, and researchers prioritize development initiatives and measure the impact of their policies. Data storytelling here plays a critical role in making such data approachable.


Final Notes

Both of these projects are foundational examples of:

    Real-world data cleaning

    Insight extraction

    Working with messy, practical data

 
