# shopify-sales-analysis
\# 🛒 Analyzing Shopify Sales Data

\### Marketing and Finance Insights and Recommendations

\## Project Background

Shopify is a complete, cloud-based commerce platform that lets anyone
build, customize, and run an online store or sell in person. Founded in
2016, it has grown into a major player in global e-commerce, generating
large volumes of data across sales, marketing, finance, and products.

This project analyzes Shopify's sales data from 2023 to 2025 to
understand the company's revenue growth and uncover critical insights
that can help improve business performance.

**\## Data Structure & Initial Checks**

The dataset consists of a single transactional table containing 19
fields, covering order details, customer and product attributes, and
financial performance metrics.

![](media/image1.png){width="6.499998906386701in" height="4.875in"}

Before analysis, the data was checked for missing values, duplicate
order IDs, and inconsistencies in returned vs. refunded orders, ensuring
accuracy across all downstream calculations.

\# Executive Summary

\## Summary of Insights

From 2023 to 2025, net revenue reached $50.86M (+2.2%), with GMV at
$72.86M (+2.2%) — showing the platform is bringing in and converting
customers well. Growth wasn't steady across the period, though.

In 2024, GMV ($29.60M) and net revenue ($20.62M) were both essentially
flat, down slightly (-0.1% and -0.3% vs. the prior month). AOV also
dipped slightly (-0.3%), while unique customers held steady at 18,275
(0.0%).

In 2025 (year-to-date through June), GMV ($13.81M) and net revenue
($9.67M) both declined close to 6% (-5.8% and -5.5%), a red flag worth
watching. Unique customers also fell (-5.7%). On the positive side, AOV
rose slightly (+0.9%) and revenue lost to returns dropped 7.7% — two
green flags suggesting that even as fewer customers ordered, each order
was worth more and returns were better controlled.

Net profit margin stayed essentially flat across all three views
(98.40%, 98.40%, 98.42%) despite swings in every other metric — a
pattern worth flagging as a possible calculation issue rather than a
genuine result.

![](media/image2.PNG){width="6.5in" height="3.622916666666667in"}

\## Sales Trends

. Even though 2024 shows a red flag overall, product profit stayed high
that year. In 2025, profit shows a green sign because revenue lost to
returns declined compared to other years.

. Canada held steady between 2023 and 2024, then dropped by roughly 55%
in the 2025 partial-year view compared to either prior year. Australia
as the stable top performer, Canada as the one market worth flagging for
further investigation.

\## recommendation

. Revenue lost to returns climbed in both 2023 (+8.0%) and 2024 (+1.4%),
signaling a worsening trend. This reversed sharply in 2025, with returns
dropping 7.7% — a strong positive signal. To sustain this improvement,
the company should continue focusing on product quality and delivery
processes to reduce damage, spoilage, and other causes of returns.

. GMV and net revenue show a modest decline when comparing 2024's
full-year pace to 2025's annualized pace (roughly 6–7%). However,
unique customer counts are actually tracking *higher* than 2024 when
adjusted for the partial year — suggesting the business is still
attracting new customers, but each customer is generating less revenue
on average. This points less toward a traffic/awareness problem and more
toward a potential issue with average order value, repeat purchase
behavior, or product mix. Before investing in new traffic sources, it
may be more effective to investigate why existing and new customers are
spending less per visit.

. To improve country-level sales, investigate Canada's
sharper-than-expected 2025 decline while studying Australia, the most
stable market, to replicate what's working. Since customer counts
aren't actually falling once adjusted for the partial year, focus on
improving spend per customer — AOV, discounts, product-market fit —
rather than driving more traffic. Check whether the 2025 improvement in
returns is happening across all countries or just a few, and prioritize
delivery/packaging investment accordingly. Hold off on major
country-specific budget shifts until 2025 is a complete year, since
current comparisons are based on only six months of data. Overall, the
strategy should prioritize retention and conversion quality over broad
traffic expansion.