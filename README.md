# Luxury-car-analysis

This project analyzes brand perception and market structure in the entry-level luxury sedan market by scraping and analyzing over 10,000 posts from an Edmunds forum.

The primary goal is to identify the "most aspirational" brand. To achieve this, the analysis first identifies the top-10 most-discussed brands and then calculates two types of lift ratios.

First, brand-to-brand lift is used to map the competitive landscape. This analysis, visualized with a Multi-Dimensional Scaling (MDS) plot, reveals distinct "cross-shopping" clusters: a "Japanese mainstream" group (Honda, Toyota, Nissan) and a "luxury pack" (Audi, Mercedes, VW). BMW is identified as a market outlier with low cross-shopping consideration.

Second, brand-to-attribute lift is calculated to define what features consumers associate with each brand, identifying "luxury" and "interior" as key differentiators.

Finally, to pinpoint the most aspirational brand, the project calculates the lift between each brand and a custom set of aspirational phrases (e.g., "want," "best," "dream car"). The analysis concludes that Audi is the most aspirational brand (Lift: 1.57), followed by Mercedes and Nissan. This aspirational positioning is strongly linked to Audi's high association with "luxury" and, uniquely, "interior" quality.
