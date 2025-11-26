# Spotify-Top-50-World-Power-BI-Analytics-Dashboard

📌 Project Overview

This project analyzes the Top 50 World Songs on Spotify, providing insights into song trends, artists, popularity patterns, duration analytics, and release behavior.
The dashboard is designed with a dark-themed Spotify-style UI, offering a clean and interactive analytics experience.

The goal of this project is to showcase data modeling, DAX calculations, UI/UX dashboarding, and storytelling through data.

✨ Key Features
🔹 1. Overview Metrics

Total distinct songs

Count of unique artists

Average song duration

Average popularity score

🔹 2. Song Categories & Distribution

Songs by Artist

Song by Year (2023 vs 2024 comparison)

Song by Album Type (Single, Album, Compilation)

Explicit vs Non-Explicit songs

🔹 3. Trend Analysis

Average Popularity by Month

Count of Distinct Songs by MonthIndex

🔹 4. Interactive Song Player Panel

Custom visual with song preview image

Play/pause styled UI elements

🔹 5. Highly Customized User Interface

Spotify-themed colors

Rounded card visuals

Fully aligned grid layout

Consistent iconography

📊 Dashboard Preview
Screenshot	Description

	Main dashboard view
<img width="1913" height="955" alt="Screenshot 2025-11-26 014714" src="https://github.com/user-attachments/assets/f6d2da64-d59e-4661-9eb6-f9d2fa325e68" />

🧠 DAX Measures Used

Some core DAX measures built for the dashboard:

Total Songs = COUNTROWS('Top-50-World')

Distinct Artists = DISTINCTCOUNT('Top-50-World'[artist])

Avg Duration = AVERAGE('Top-50-World'[duration_ms]) / 60000

Avg Popularity = AVERAGE('Top-50-World'[popularity])

Singles Count = CALCULATE(COUNTROWS('Top-50-World'), 'Top-50-World'[album_type] = "single")

📁 Dataset Used

spotify-top-50-world.csv

Columns include:
artist, track_name, album_type, popularity, duration_ms, is_explicit, release_date, month, monthIndex

🛠️ Tools & Technologies

Power BI Desktop

Power Query

DAX

Custom UI Design

CSV Dataset

🚀 How to Use This Project

Clone or download the repository

Open Spotify_Dashboard.pbix in Power BI

Load the provided CSV dataset

Explore dashboards & visuals

🧩 Skills Demonstrated

Data Cleaning & Transformation

Data Modeling

DAX Calculations

UI/UX Design in Power BI

Analytical Storytelling

Dashboard Optimization

⭐ Why This Project?

This dashboard demonstrates your ability to work with:

Real music streaming data

Trend analysis

Advanced Power BI visuals and themes

Business insights discovery

Perfect for Analytics, BI, Product Analyst, and Data roles.
