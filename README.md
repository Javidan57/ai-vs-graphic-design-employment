# The Influence of AI Growth on the Unemployment Rate of Graphic Designers

## Project Overview
This project investigates the relationship between the rise of AI technologies (such as **Midjourney**, **DALL·E**, **Canva AI**, and **ChatGPT**) and the employment trends of graphic designers.  
By analyzing data from the past decade (2015–2024), this project aims to uncover whether the growing popularity of AI-driven creative tools correlates with a decline in employment opportunities or job demand for graphic designers.

### Key Research Questions
- How strongly does the rise of AI tools (measured by search trends or adoption metrics) correlate with the decrease in employment or job postings for graphic designers?
- Is there a visible impact of AI popularity on designer salaries or wage growth?
- Can data-driven evidence support the hypothesis that AI automation is transforming the creative job market?

---

## Motivation
Over the last few years, tools like **Midjourney**, **DALL·E**, **Canva AI**, and **ChatGPT** have changed the way digital art and design are created.  
Many designers fear that AI-generated content may be replacing human creativity, while others see it as a way to increase efficiency and creativity.

This project aims to analyze real data to understand whether these fears are justified.  
By studying employment and AI popularity trends together, I want to explore if the creative industry is being disrupted—or just evolving—in response to AI innovations.

---

## Objectives
- Find out if there is a negative correlation between AI tool adoption and graphic designer employment.  
- Identify how salaries, job postings, and industry growth have changed over the last 10 years.  
- Create visualizations that clearly show the trends between AI growth and design jobs.  
- Discuss whether AI has replaced or reshaped creative work and what the data suggests about the future.

---

## Data Sources

### 1. Employment and Wage Data
- **Source:** U.S. Bureau of Labor Statistics (BLS)  
- **URL:** https://www.bls.gov/oes/current/oes271024.htm  
- **Description:** Provides yearly employment, wage, and industry data for “Graphic Designers” (occupation code 27-1024) between 2012 and 2024.  
- **Goal:** Analyze job counts, growth rates, and salary trends.

### 2. AI Popularity and Adoption Data
- **Source:** Google Trends  
- **Keywords:** “AI art”, “Midjourney”, “DALL·E”, “Canva AI”, “AI design tools”  
- **Description:** Tracks the popularity and adoption rate of AI creative tools over time.  
- **Goal:** Build an AI Popularity Index based on normalized search interest from 2015–2024.

### Enrichment
- Additional Kaggle datasets related to AI usage or creative industry trends.

---

## Data Collection Plan

### 1. Collect Employment Data
**Tool:** Python + pandas  
- Download historical employment and wage CSV files from BLS.  
- Extract columns such as *Year*, *Employment Count*, *Average Salary*.

### 2. Collect AI Popularity Data
**Tool:** Google Trends + Python  
- Export CSV files for AI-related search terms.  
- Compute yearly averages to create an AI Popularity Index.

### 3. Merge and Clean Data
**Tool:** pandas  
- Merge both datasets by year (2015–2024).  
- Handle missing values or inconsistent data.  
- Save as a single processed CSV.

### 4. Analyze and Visualize
- Use line graphs to show trends in AI popularity vs. employment.  
- Calculate the correlation coefficient between AI growth and employment decline.  
- Visualize findings with scatter plots, regression lines, and heat maps.

---

## Expected Outcomes
- A correlation analysis showing whether AI adoption negatively affects graphic designer employment.  
- Time-series plots that visualize changes in both AI popularity and job trends.  
- Insightful visualizations showing how creative industries adapt to technological shifts.  
- A short discussion on ethical implications and the future of creative work in the age of AI.

---

## Tools
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scipy  
- **Environment:** Jupyter Notebook  
- **Data Sources:** BLS, Google Trends, Kaggle
