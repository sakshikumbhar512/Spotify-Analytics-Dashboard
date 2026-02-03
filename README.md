# Spotify-Analytics-Dashboard
This project is a comprehensive data visualization tool that transforms Spotify "Extended Streaming History" into actionable insights. By analyzing years of listening data, this dashboard uncovers patterns in music consumption, favorite artists, and daily habits.

📜 Project Overview
The goal was to move beyond the yearly "Spotify Wrapped" and create a deep-dive tool that tracks listening trends over a multi-year period. The dashboard is divided into three main views:

1. The Executive Summary (Overview)
Big Picture Metrics: High-level tracking of total Albums (7.3k+), Artists (3.8k+), and Tracks (12.7k+).

Time-Series Analysis: A growth chart showing how listening habits have evolved from 2016 to 2024, peaking around 2021.

Platform & Behavior Filters: Ability to slice data by device (Android, Mac, Web Player) and track "Shuffle" vs. "Skipped" behavior.

Top 5 Charts: Quick look at all-time favorites, featuring legends like The Beatles and The Killers.

2. Behavioral Insights (Heatmaps & Trends)
Listening Heatmap: A "Listening Hours vs. Days" matrix that reveals exactly when I’m most active. (Apparently, late nights and early mornings are the "prime time" for music!)

Track Frequency vs. Duration: A scatter plot that helps distinguish between "background noise" (short, frequent tracks) and "deep listening" (longer, immersive tracks).

Weekday vs. Weekend: A donut chart comparison showing that the majority of listening happens during the work week.

3. Granular Data (Details View)
A drill-down table providing the "raw" stats for every album in the library.

Includes precise metrics like total milliseconds played and Average Listening Time (Min) per session, allowing for a technical audit of my own library.
Visuals & Charts Breakdown
To bring this data to life,
I utilized a variety of advanced visualization techniques:

Line Charts (Area Overlay): Used for the "Played Over Time" series to visualize growth trends and seasonality in listening habits from 2016 to 2024.

Donut Charts: Implemented to show the percentage split between Weekday vs. Weekend listening, providing a quick look at lifestyle patterns.

Bar Charts (Horizontal): Dedicated to the "Top 5" rankings for Albums, Artists, and Tracks, allowing for easy comparison of volume across different categories.

Matrix Heatmap: A color-saturated grid used to map Listening Hours vs. Days. This creates a "density map" that identifies my peak listening windows throughout the week.

Scatter Plot: A technical visual used to correlate Average Listening Time against Track Frequency. I added constant lines (X and Y-axis thresholds) to segment tracks into different "engagement" quadrants.

Slicers & Toggle Buttons: Integrated interactive filters for Platforms (Android, Mac, iOS), Shuffle mode, and Yearly toggles to allow for a highly customized user experience.

KPI Cards: High-level summary tiles used to display "Big Rocks" like total track counts and year-over-year (LY vs PY) comparisons.

Data Table (Detail View): A granular, multi-column list with conditional formatting and hierarchical drill-downs for deep-diving into specific album metrics.

🛠️ Tech Stack
Data Source: Spotify JSON Personal Data Export.

Tool: Power BI / DAX (Data Modeling & Visualization).

Design: Custom Dark Mode UI inspired by the Spotify brand guidelines.
 Screenshot : https://github.com/sakshikumbhar512/Spotify-Analytics-Dashboard/blob/main/Spotifydashbord1.jpg
              https://github.com/sakshikumbhar512/Spotify-Analytics-Dashboard/blob/main/SpotifyDashbord2.jpg
              https://github.com/sakshikumbhar512/Spotify-Analytics-Dashboard/blob/main/SpotifyDashbord3.jpg
