Analyzed ride-hailing order data using Python, Pandas, and Matplotlib to identify the root causes of service failures (client cancellations vs. system rejections).

Performed feature engineering to categorize failures, discovering that "System Rejects" (all available drivers declined the offer) was the largest source of lost revenue.

Conducted temporal analysis to pinpoint peak failure "hotspots" at 8-10 AM and 5-7 PM, correlating these spikes with a surge in average ETAs.

Identified a critical 90-second window where clients without a driver assignment are 3x more likely to cancel, providing a clear target for match algorithm optimization.

Leveraged H3 and Folium for geospatial analysis, mapping high-failure zones to show that 80% of all failures originated from a small, concentrated number of locations.

Recommended a data-driven strategy to improve ride completion rates by 1) proactively repositioning drivers to known hotspots before peak hours and 2) optimizing the matching algorithm to prioritize "likelihood of acceptance" over just "closest driver."
