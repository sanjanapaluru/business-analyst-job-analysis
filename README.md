#  Business Analyst Job Market Insights

This project analyzes Business Analyst job postings across industries, cities, job types, and experience levels to uncover salary trends, hiring cycles, and the evolving nature of remote/hybrid work. It also explores AI applications in data scraping and visualization.

##  Project Overview

This end-to-end data analytics project includes:

- Web scraping job postings from [BusinessAnalyst.com](https://businessanalyst.com)
- Data cleaning and transformation
- Exploratory Data Analysis (EDA) and outlier removal
- Visual insights into salary trends across:
  - Industry
  - City
  - Job location (Remote/Hybrid/Onsite)
  - Experience level
- Sector-specific focus on Healthcare
- AI applications in data scraping and visualization

##  Project Structure

├── business_analyst_jobs.csv # Cleaned dataset
├── model.ipynb # Data analysis, cleaning, feature extraction
├── visualization.ipynb # Exploratory data visualizations
├── DATA_ANALYTICS_PPT.pdf # Presentation summarizing findings
└── README.md # Project documentation

markdown
Copy
Edit

##  Tools & Libraries

- **Python**: pandas, numpy, matplotlib, seaborn
- **Web Scraping**: BeautifulSoup, requests
- **Data Cleaning**: IQR method for outlier removal
- **Visualization**: Matplotlib, Seaborn
- **AI Techniques**: NLP, intelligent scraping, real-time visualization (discussed conceptually)

##  Key Insights

- **Top Paying Industries**: Crypto, Automotive, and Tech
- **Cities with Highest Median Salaries**: San Francisco, New York, Boston
- **Remote vs Onsite**: Hybrid jobs offer the highest median salaries
- **Experience Impact**: 5–10 years of experience yields the highest average salary
- **Hiring Cycle**: Job postings peak around July
- **Healthcare Sector**:
  - Highly volatile salaries
  - Remote roles dominate (58.5%)
  - Onsite roles are rare (9.4%)

##  AI Applications (Conceptual)

- **Web Scraping**: NLP for unstructured text, adaptive scrapers using ML
- **Visualization**: AI-generated insights, immersive VR/AR dashboards, real-time visual updates

##  Sample Visuals

> See the [`visualization.ipynb`](visualization.ipynb) and slides (`DATA_ANALYTICS_PPT.pdf`) for plots such as:
> - Salary by Industry
> - Salary trends by city
> - Salary vs experience level
> - Job type distribution in Healthcare
