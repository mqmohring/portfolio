---
permalink: /projects/
title: "Projects"
---
## Global Layoffs Analysis (2022-2025)  

The past few years have seen significant workforce reductions across industries, driven by economic uncertainty, technological shifts, and post-pandemic adjustments. This project explores global layoff trends from 2022 to 2025, analyzing between others:  

- **Most affected regions, companies, and industries**  
- **Timing of peak layoffs**  
- **Relationship between funding and workforce reductions**  

### Methodology  
- Cleaned and processed the dataset using **SQL** (Exploratory Data Analysis)  
- Visualized trends and insights using **Python** (Matplotlib/Seaborn)  
- Explored key questions like:  
  - Which sectors were hit hardest?  
  - Did well-funded companies lay off more or fewer employees?  
  - Were there regional differences in layoff patterns?  

### Key Findings  
🔹 **Consumer and retail** saw the highest layoffs  
🔹 Layoffs peaked in **early 2023**  
🔹 Companies with **lower funding rounds** were more likely to downsize


## 1. Global Layoffs 1: SQL Cleaning  
<iframe src="https://drive.google.com/file/d/1J_6bMXdwvX4F5DUIPNMFE8QLg14H8OZ2/preview" width="800" height="540" allow="autoplay"></iframe>  

## 2. Global Layoffs 2: SQL EDA  
<iframe src="https://drive.google.com/file/d/1-_EOt8C0qfodntrBniNRrNFVC50MiuU1/preview" width="800" height="540" allow="autoplay"></iframe>

## 3. Global Layoffs 3: Python Visualisation
2023 was the year with highest layout indexes, peaking in the first quarter:
<iframe src="https://mqmohring.github.io/portfolio/plots/layoffs_per_month_2022-2025.html" width="800" height="540"></iframe>
The most affected industries were Consumer, Retail and Hardware:
<iframe src="https://mqmohring.github.io/portfolio/plots/layoffs_per_industry_2022-2025.html" width="800" height="540"></iframe>
Denmark, Vietnam and Nigeria show the highest layoff indexes:
<iframe src="https://mqmohring.github.io/portfolio/plots/layoffs_by_country.html" width="800" height="540"></iframe>
Is there a correlation between company size and layoff indexes? 
(double-click to filter a stage)
<iframe src="https://mqmohring.github.io/portfolio/plots/layoffs_per_funding.html" width="800" height="540"></iframe>
While higher-funded companies lay off more people in total, this is largely due to their size. It seems necessary to cross-reference with layoff percentages:
<iframe src="https://mqmohring.github.io/portfolio/plots/layoff_percentage_box.html" width="800" height="540"></iframe>
Lower funding does seem to reflect on higher exposure to layoffs. A regression plot shows this clearly too:
<iframe src="https://mqmohring.github.io/portfolio/plots/layoff_percentage_per_funding.html" width="800" height="540"></iframe>
- Positive correlation in advanced stages like Series J, suggest that some companies raised significant funding but still had high layoff percentages.  
- This could reflect overexpansion or overhiring followed by corrections, strategic misalignment (money was raised, but business goals weren't met), or investor pressure to cut costs post-funding round.  
- This could point to overfunded companies in decline, poor capital efficiency or late-stage companies with bloated ops trimming aggressively. 

### Conclusions
🔹 According to these graphs, companies with **lower funding rounds were more likely to downsize proportionally**.  
🔹 Early-stage companies experience higher relative downsizing, meaning they are more likely to lay off a larger share of their staff, and in some cases, nearly all of it.  
🔹 This aligns with the common startup risk curve — early-stage companies face more volatility, resource constraints, and abrupt strategy pivots that lead to higher relative layoffs.  


📌 **See the full notebook:** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YvBxn3TdX7xyqJDTDd0ghOi1N5ELiRLG?usp=sharing) 
or the Seaborn version below: 
<iframe 
  src="https://mqmohring.github.io/portfolio/plots/LAYOFFS.py GRAPHS.pdf#toolbar=0&navpanes=0&scrollbar=0&view=FitH" 
  width="800" height="700"></iframe>




