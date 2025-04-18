# Corrio SPC Segmentation & Usage Behavior Analysis

A data analytics project that segments Corrio SPC user accounts by usage behavior using a Jupyter Lab notebook. This analysis involved cleaning and combining raw user activity logs from Corrio SPC, computing key usage metrics for each user, performing K-means clustering to create user segments, and examining the usage patterns of each segment. The goal is to uncover distinct user behavior profiles and insights into how different groups engage with the service.
Project Overview

**Data Cleaning & Preparation:** Combined multiple raw event log files (spanning five years of Corrio SPC usage) into a single dataset. Performed cleaning and standardization (fixing data types, handling missing values, and ensuring consistency in timestamps and IDs).

**Usage Metrics Computation:** Aggregated detailed per-account usage metrics – for example, total number of events (calls/messages), number of active days, revenue generated, average events per day, and other engagement indicators for each user account.

**K-Means Clustering (User Segmentation):** Applied K-means clustering on the aggregated metrics to group user accounts into distinct segments based on their behavior patterns. Determined an optimal number of clusters using methods like the elbow plot and silhouette analysis, then labeled each account with its cluster/segment.
Segment Behavior Analysis: Analyzed each segment’s characteristics to interpret usage patterns. This includes examining metrics like engagement frequency, duration of use, and revenue contribution per segment. We identified how segments differ (e.g. a high-usage segment vs. a low-engagement segment) and drew insights about user behavior trends in Corrio SPC’s customer base.

## Data Privacy & Access
This repository is a public landing page that describes the project, but it does not contain the actual data or code. The full Jupyter Notebook (created in JupyterLab) and the dataset are kept in a private repository because they contain proprietary data from Corrio SPC (a startup). Corrio SPC has granted permission for the author to share the complete analysis privately with specific individuals (such as prospective employers), on a need-to-know basis. If you are interested in viewing the full notebook, including the code and results:
Access Request: Please contact the author (via email or GitHub message) to request access. Kindly mention your affiliation and reason for interest. With approval, you will be granted read access to the private repository containing the notebook and data. (For example, if you are a hiring manager or recruiter who wishes to review this work, permission will be given to you to view the project privately.)
