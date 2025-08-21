[![Athena Award Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Faward.athena.hackclub.com%2Fapi%2Fbadge)](https://award.athena.hackclub.com?utm_source=readme)
# Data Science Capstone Project: Viral Toy Trends & Digital Consumer Behavior

## Project Overview

This project explores the psychological triggers behind impulsive purchases and digital consumer behavior across platforms and regions. The focus is on how rapid content cycles and algorithmic targeting on social media stimulate dopamine-driven shopping habits. To uncover these patterns, developed four data visualizations mapping trends across age, interests, social media use and impulse-buying tendencies.

## Data Pipeline & Processing

The data journey started with raw datasets from Kaggle, Google Trends API and social media surveys. And then started with Google Sheets for starting organization and basic cleaning, then moved to SQL for more complex transformations and data querying. Then the final step involved Tableau for creating interactive dashboards that could tell a story about consumer behavior. The data cleaning process is a systematic process. I began by assessing the quality of the data and it's completeness, then handled fixing missing values strategically. The detection of outliers was crucial for identifying anomalous data points that could skew the analysis. 

## Key Insights & Findings

Viral Toy Microtrends
Each year from 2020-2025 had one dominant viral toy: Mini Brands (2020), Pop Its (2021), Squishmallows (2022), Sonny Angel (2024), and Labubu (2025), with social media platforms dramatically accelerating trend lifecycles from years to weeks.

Regional Scarcity Psychology
Consumers in Can Tho consistently report the highest concern across all scarcity factors—promotion deadlines, time limits, quantity constraints, and fear of stockouts—while provinces like Tra Vinh and Soc Trang show lower levels of scarcity concern, revealing regional differences in digital shopping psychology.

Sustainable Shopping Gap
70% of U.S. shoppers still buy items brand new, with only 17% choosing to thrift and 13% buying from resale platforms, despite the rise of sustainable fashion and secondhand marketplaces, highlighting the gap between environmental awareness and actual shopping behavior.

## Educational Value

This project served as a comprehensive example of the complete data science workflow from raw data to great insights. It demonstrates Tableau & SQL mastery through advanced visualization techniques and dashboard design, and also provides insights into consumer behavior analysis.

## Screenshot
<img width="2833" height="1430" alt="image" src="https://github.com/user-attachments/assets/fb12db27-3b16-454d-b851-c3f90e16f6dc" />

## Data Viz 1

Consumer Behavior Correlation
Analysis of Viral Toy Trends and Microtrends from 2020-2025

What It's About
This data visualization explores the most viral toys from 2020 to 2025 by analyzing search interest and social media hashtag metrics. The goal is to identify how collectible toy trends rise and fall over time, and what drives a toy to go viral.

Sources Used
Google Trends – to analyze peak search interest by year for toy names like "Pop Its" or "Sonny Angel"
TikTok (in-app search) – for hashtag view counts (e.g. #sonnyangel had 533K videos)
Instagram (via desktop and app) – for total post counts per hashtag (e.g. #sonnyangel had 901K posts)
What This Data Viz Tells Us
This visualization highlights how microtrends, which are fast-moving, internet-driven trends, are reshaping modern consumer behavior, especially in the toy and collectibles market. A niche obsession can become a global sensation in weeks due to TikTok virality and emotional reliability. It can be shown that the lifecycle of toy trends is shortening.

Key Insights
Each year from 2020 to 2025 had one dominant viral toy:

2020: Mini Brands
2021: Pop Its
2022: Squishmallows
2023: Smiski
2024: Sonny Angel
2025: Labubu
Labubu began trending in late 2023 but peaked in 2024–2025.

What This Data Viz Tells Us
This visualization highlights how microtrends, which are fast-moving, internet-driven trends, are reshaping modern consumer behavior, especially in the toy and collectibles market. A niche obsession can become a global sensation in weeks due to TikTok virality and emotional reliability. It can be shown that the lifecycle of toy trends is shortening.

Implications for Blind Box Culture
This analysis shows how blind box collecting has evolved from a niche hobby to a mainstream trend driven by social media virality. The shortening trend lifecycle means collectors must adapt quickly to changing interests, and brands must innovate constantly to maintain relevance. The emotional connection and dopamine rush from unboxing videos create a perfect storm for viral spread.


## Data Viz 2

Social Media Product Discovery Analysis
Number of Responders Citing Product Discovery and Reviews as a Major or Minor Reason for Social Media Use, by Platform

What It's About (& Sources)
This data visualization shows the number of responders who said product discovery and reviews were a major or minor reason for their social media usage. It aims to explore the level of trust consumers have in the word of influencers and social media when it comes to their consumption choices.

Sources
Dataset: American Trends Panel Wave 144
Article: A majority of U.S. TikTok users are there for reviews and recommendations
Key Insights
The trend of the data shows that Instagram users were generally more likely to use the social media platform with product discovery in mind.
This was followed by TikTok users and X/Twitter users.
The data reveals consumers' tendency to trust social media to help evaluate their consumption choices.
Interactive Chart

What This Data Viz Tells Us
This visualization shows consumers' tendency to trust social media to help evaluate their consumption choices. With internet microtrends on the rise, trinkets like Labubus and Sonny Angels are spurred forward by social media virality, especially on platforms like Instagram and TikTok, which are designed to optimize quick, visual media consumption.

As consumers are more willing to try things popular on social media, the cycle continues, encouraging impulsive consumerism. This data reveals how social media platforms have become powerful drivers of consumer behavior, particularly for younger demographics who rely heavily on these platforms for product discovery and reviews.

## Data Viz 3

TikTok Shop Scarcity Analysis
Understanding Consumer Perceptions of Scarcity on TikTok Shop in Vietnam

What It's About (& Sources)
The data visualization illustrates the concerns of consumers on TikTok Shop in Vietnam by analyzing consumers' perceptions of scarcity on TikTok Shop — how much users feel urgency, limited quantity, or risk of missing out (FOMO) while shopping on the platform.

Sources Used
Kaggle: https://www.kaggle.com/datasets/jocelyndumlao/impulse-buying-factors-on-tiktok-shop?resource=download

Dataset: Impulse Buying Factors on TikTok Shop - Understanding What Drives Impulse Purchases Among Vietnamese Students on TikTok

Key Insights
Can Tho shows the highest scarcity concern
Tra Vinh and Soc Trang show the lowest concern
Promotion-related urgency is the most triggering
Regional digital behaviors may influence perception
Limited quantity and out-of-stock worries are closely related

What This Data Viz Tells Us
This visualization explores regional differences in scarcity-driven shopping behavior on TikTok Shop across multiple provinces. It reveals that consumers in Can Tho consistently report the highest concern across all scarcity factors—promotion deadlines, time limits, quantity constraints, and fear of stockouts. In contrast, provinces like Tra Vinh and Soc Trang show lower levels of scarcity concern.

These insights suggest that perceptions of urgency and limited availability vary by location, potentially influenced by regional digital engagement, socioeconomic factors, or exposure to online shopping cues.


## Data Viz 4

U.S. Shopping Behavior Analysis
How Americans Shop: First-Hand vs Reused

What It's About (& Sources)
This pie chart breaks down how people in the United States shop:

Buying first-hand (new) products
Purchasing from thrift stores
Shopping via resale or consignment platforms
The data was compiled using public consumer trend reports from sources like ThredUp's Resale Report and Statista (2024), and was simplified to reflect general population behavior.

Sources
ThredUp's Resale Report - Consumer shopping behavior trends
Statista (2024) - U.S. retail and shopping statistics
Key Insights
70% of U.S. shoppers still buy items brand new.
Only 17% choose to thrift, while 13% buy from resale or consignment sources.
Despite the rise of sustainable fashion and secondhand platforms, reuse is still underutilized by the majority.

What This Data Viz Tells Us
This chart highlights a major opportunity:

Americans could significantly reduce waste by shifting even a portion of their shopping from new to reused options.

It suggests we need to encourage creativity, sustainability, and reusability — not just for the environment, but also to challenge consumer culture and inspire innovation.
