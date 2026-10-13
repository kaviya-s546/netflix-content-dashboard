# Netflix Content Dashboard

An interactive Tableau dashboard that explores the Netflix catalogue: what type of content it has, where it comes from, and when it was added.

**Live dashboard:** https://public.tableau.com/app/profile/kaviya.stalin/viz/Netflix_Dashboard_17918663718390/NetflixDashboard

![Netflix Dashboard](Netflix%20Dashboard.png)

## Dataset
- Source: Netflix Titles dataset from Kaggle
- About 8,800 titles and 12 columns
- Columns include type, title, country, date added, release year, rating, duration and genre

## Tools
- Excel: data cleaning
- Tableau Public: charts and dashboard

## Data Cleaning (Excel)
- Counted blank cells in every column
- Removed duplicate titles using Show Id
- Filled blank country, director and cast cells with "Unknown"
- Left blank date_added cells unchanged
- Created helper columns: Year Added, Month Added, Primary Country and Main Genre
- Recorded every step in a Cleaning Log sheet

## Dashboard Charts
- Titles added per year
- Movies vs TV Shows
- Content map by country
- Top 10 countries
- Top 10 genres
- Filters for Type and Year Added

## Key Insights
1. Movies are about 70% of the catalogue (6,131 movies vs 2,676 TV shows).
2. The US has the most titles, followed by India.
3. Drama is the top genre, followed by Comedy.
4. Netflix added the most titles around 2019-2020.
5. Very few titles were added before 2015.

## What I Learned
- Cleaning messy text and date data in Excel
- Counting unique values with Count (Distinct) in Tableau
- Using Top N filters and filters that apply to all charts
- Publishing a dashboard on Tableau Public

## Author
S Kaviya
