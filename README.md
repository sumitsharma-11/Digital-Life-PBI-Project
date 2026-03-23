# Digital-Life-PBI-Project

Digital Life Audit: Browser History Analytics Dashboard 🌐📊

Project Overview
This project is a personal data analytics initiative designed to visualize and audit digital habits. By exporting and processing browser history data, this Power BI dashboard provides a "Digital Life" audit, uncovering patterns in productivity, entertainment consumption, and web-based activity.

The goal is to transform raw, unstructured digital footprints into actionable insights regarding time management and online focus.

Key Features
Activity Volume Tracking: Analysis of peak browsing hours and high-activity days.
Domain & Category Profiling: Automatic grouping of websites into categories (e.g., Learning, Social Media, Professional, Entertainment).
Session Duration Insights: Identification of deep-work periods versus frequent context-switching.
Search Intent Analysis: Breakdown of recurring search topics and interests over time.
Productivity Scorecard: A custom metric comparing "Growth/Learning" sites against "Distraction" sites.

Visualizations Included
Habit Overview: A high-level summary of total links visited, top 10 most visited domains, and daily activity trends.
Time Distribution: Heatmaps showing activity by hour of the day and day of the week.
Content Classification: Tree maps and pie charts representing the diversity of web usage.
Deep Dive Search: A word cloud or frequency table of the most common search terms.

Tech Stack
Data Source: Browser History (JSON/CSV export).
Data Cleaning: Power Query (M Language) for URL parsing, domain extraction, and timestamp normalization.
Analysis: DAX (Data Analysis Expressions) for calculating time spent and frequency metrics.
Visualization: Power BI Desktop.

How to Setup
Data Export: Export your browser history using a tool (like "History Trends Unlimited" or Chrome's native export).
File Placement: Place the exported file in the Data/ folder.
Refresh: Open Digital Life Project.pbix in Power BI Desktop and click Refresh to populate the visuals with your own data.

Insights & Reflection
Productivity: Discovered that peak learning happens between 10 AM and 1 PM.
Focus: Identified specific "echo-chamber" domains that contribute to time-sinks.
Optimization: Used these insights to set site timers on high-distraction domains.
