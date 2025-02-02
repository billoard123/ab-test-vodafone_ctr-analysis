A/B Test for Vodafone "Read more" vs "Find your Sim-only plan"

**Objective**
I wanted to find out if changing Vodafone's CTA from "Read more" to "Find your Sim-only plan" would lead to a minimum of a 10% increase in the CTR to compare and contrast the two approaches and to identify the better one. I looked for clear statistical significance and practical evidence to make an informed final decision on implementing the change.

**Methodology and TechStack**
**Python** - Pandas, NumPy and SciPy for data processing

**Hypothesis test/Z-test** -  I set the parameter alpha(α) at a 5% significance to determine if the observed CTR increase is likely to be driven by the CTA change, not by random fluctuation 

**Confidence interval (CI)** - The CI was 95%, to estimate the true range of CTR improvement, ensuring that the results are both statistically valid and practically meaningful.

****Visualizations**** - I used Seaborn & Matplotlib to present the results, including rejection regions and standard normal distributions, making the statistical evidence clear.

**Results & Interpretation**
The null hypothesis (H₀) was strongly rejected at α = 0.05, indicating that the observed CTR increase is highly unlikely to be attributed to random chance.![image](https://github.com/user-attachments/assets/3e2a1521-0141-4a71-8dff-f179f594783e)


**Key insights include -**

I found out that there was a narrow confidence interval around the CTR improvement estimate which indicates that the sample data is an accurate representation of the populations, in other words, these are accurate results.  The new CTA, "Find Your SIM-Only Plan," achieved a statistically significant increase in CTR, with the 95% confidence interval confirming that the improvement is meaningful. With a Minimal Detectable Effect (MDE) of 0.1, the difference between the control and experimental groups was not only statistically significant but also practically impactful, indicating that the CTR boost will translate into tangible outcomes, such as increased sales and higher revenue.

**Business Implications**
I believe Vodafone should be motivated to implement the new CTA "Find Your SIM-Only Plan" across its platform, as the results show clear, measurable benefits. This change isn’t just statistically significant; it is practically significant, meaning it will lead to higher CTR, greater user engagement, and ultimately, higher revenue.

By adopting this CTA, Vodafone can expect a boost in conversions, driving more customers to take the next steps, such as signing up for SIM-only plans. This increase in user interaction will likely have a direct, positive impact on revenue generation.

This study demonstrates the power of A/B testing in refining user experiences, optimising business outcomes, and making data-driven decisions that contribute to long-term growth and increased profitability.
