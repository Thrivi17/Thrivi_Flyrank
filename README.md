# FlyRank Engine & ML Content Pipeline

An end-to-end machine learning pipeline built for FlyRank to score and rank page-query combinations using predicted click-through rates (CTR) as an "opportunity score". This project covers the full lifecycle from data validation and feature engineering to model training and leakage demonstration.


## Project Overview

In SEO and content optimization, knowing which queries drive value for specific pages is critical. This pipeline automates the evaluation of page-query pairs by predicting their potential click-through rate, allowing content teams to prioritize optimization efforts efficiently.

* **Data Validation:** Verified dataset grain and feature availability using targeted queries prior to model construction.
* **Feature Engineering:** Developed five core predictive features, strictly validated to ensure they were knowable at decision time.
* **Demonstration of Data Leakage:** Deliberately introduced a label-derived feature to observe its impact (watching performance metrics artificially jump toward perfection), before systematically removing it to maintain model integrity and honest results.


