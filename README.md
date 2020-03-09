# Viewability_test

This analysis was initiated in order to determine the impact of ad-refreshes on ad viewability. In an effort to secure more ad revenue, certain programmatic ads on certain platforms have been set to refresh every 30 seconds. While this increases the amount of impressions served and boosts short-term revenue, eCPMs have ultimately decreased. While part of the immediate eCPM drop has occured due to a surplus in supply in the bidding market, it is important to understand how our various ad KPIs such as viewability and CTRs have been impacted due to the refresh implementation. This would help us understand the long-term value of our inventory and thus the long-term implications of our market prices due to the new refresh policy. I've listed out the steps to the analysis below.

1.) Sampling: Pulled reporting for 30+ days of ad data from before and after the ad-refresh implementation.

2.) Outliers: Box plots were utilized to visualize signifcant outliers.

3.) Normality: Q-Q plots and histograms were used to visually assess the normality of our data.

4.) Welch's T-test: This test was selected since variances between the two sample's distributions seem to vary.

5.) Wilcoxon Signed Rank Test: This test was selected as a non-parametric test since one of our sample's distributions seemed to be trimodal and seemed to be non-normal.
