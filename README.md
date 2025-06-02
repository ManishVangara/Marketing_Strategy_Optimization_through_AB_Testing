# Marketing Strategy Optimization through A/B Testing

## Project Background

This project investigates the effectiveness of two distinct marketing strategies—'ad' (advertisement) and 'psa' (public service announcement)
on user conversion rates. The goal is to guide decision-making for future marketing investments and optimize ad exposures for higher engagement.

## Objective 

To determine whether there is a statistically significant difference in conversion rates between users exposed to the 'ad' group versus the 'psa' group.

## Dataset Description

- User ID: Unique identifier for each participant
- Test Group: Indicates the assigned group ('ad' or 'psa')
- Converted: Boolean outcome indicating whether the user converted
- Total Ads: Total number of ads shown to the user
- Most Ads Day: The day of the week the user saw the most ads

## Methodology

1. Data Cleaning and Exploration
   
   - Checked for null values
   - Summarized categorical and numerical columns
   - Validated group distributions and base conversion rates

2. Data Visualization

   - Count plots for test group and conversions
   - Boxplots to evaluate total ad exposure
   - Bar chart of conversion rates by weekday

3. Statistical Testing

   - Chi-Square Test: Assessed dependence between test group and conversion (p < 0.05)
   - Levene's Test: Checked for equal variances in ad exposure between converters and non-converters
   - Mann-Whitney U Test: Compared distribution of ad exposures across conversion status (non-parametric)

## Key Findings

- Users in the 'ad' group had a marginally higher conversion rate than those in the 'psa' group.
- Chi-square test results showed the difference in conversion rates between the groups is statistically significant.
- Users who converted generally saw more ads than those who did not, as supported by the Mann-Whitney U test.
- Variances in ad exposure across groups did not significantly differ, validating assumptions for comparison.

## Business Impact

The analysis suggests a measurable advantage in using direct advertisement over public service announcements for increasing conversion.
Additionally, insights on optimal ad exposure provide actionable recommendations for future marketing strategies.

## Recommendations

- Prioritize the 'ad' strategy in future campaigns.
- Monitor user engagement around optimal ad frequency.
- Conduct follow-up experiments to refine targeting and content design.


