# Geo Localization and Newsworthiness Analysis of Tweets

Developed a comprehensive geo-localization and newsworthiness analysis system for tweets, focusing on data from London.

Constructed an algorithm to compute the distance between tweet coordinates using the Haversine formula and created a grid system over London to visualize tweet distribution.

Processed a dataset containing 13,192 tweets, identifying significant variations in tweet distribution, with 4,298 tweets in the highest activity grid cell and an average of 4.66 tweets per grid cell.

Created visualizations, including a heatmap and histogram, to display the distribution of tweets across London, highlighting central London as the area with the highest tweet activity.

Developed a newsworthiness computation method, employing term frequencies and likelihood ratios to score tweets. Achieved notable findings, such as 86% of high-quality texts being classified as newsworthy at a threshold of 2.

Conducted extensive data analysis on newsworthiness thresholds, examining thresholds from 1.5 to 4. Observed that higher thresholds reduced the proportion of texts classified as newsworthy, while maintaining consistent trends in average scores and standard deviations.

Evaluated the impact of stopwords removal on newsworthiness scores, finding that 99.28% of high-quality texts were classified as newsworthy at a threshold of 1.5 after stopwords removal.

Determined that a threshold of 0.77 (median score) was optimal for separating newsworthy from non-newsworthy tweets, leading to the removal of 48.83% of tweets with low scores.

Created visualizations comparing the distribution of newsworthiness scores before and after cleaning, showing a more balanced distribution post-cleaning.

Identified issues with geo-localization due to the reliance on third-party platforms like Instagram for tweet coordinates, which accounted for 10,529 out of 13,192 tweets, highlighting potential inaccuracies in geolocation data.
