# Sentiment-Analysis-on-Marvel-IMDb-Reviews


This repository contains the full code and presentation slides for our case study on sentiment analysis of Marvel Movie IMDb reviews. The master branch includes our Python code and a PPT presentation summarizing our work.

**Team Members:**  
- Bashir Gulistani  
- Isha Jain  
- Rohan Rana  
- Seayar Sroosh  
- Tanish Kandivlikar  

## Table of Contents
1. [Business Problem](#business-problem)
2. [Motivation](#motivation)
3. [Conjectures](#conjectures)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Recommendations](#recommendations)

## Business Problem
- Determine how audience perception has changed in recent years compared to older movies and series (pre-2019).  
- Help Marvel understand the reasons behind the recent drop in movie performance—whether due to changing audience behavior, novelty effects, or a decline in production quality.

## Motivation
- Marvel movies and series form a connected universe where audience feedback is vital for success.  
- Given the passion and dedication of the Marvel audience, their reviews provide insightful and actionable feedback.  
- Leveraging these insights can guide improvements and maintain the elements that the audience values most.

## Conjectures
- **Shift in Audience Preferences:** Creative direction may have shifted away from what longtime fans appreciate.  
- **Storytelling & Character Development:** Discontent might stem from aspects of narrative or character arcs in newer productions.  
- **Comparative Success:** Some MCU titles still excel, suggesting issues are confined to specific movies or series rather than the entire franchise.

## Methodology
- **Data Collection:**  
  - Scraped data from IMDb for Marvel movies—including titles, budget, reviews, and box office collections (US & Canada and worldwide).  
  - Collected comparable data from Invincibles (a non-Disney show) for contrast.
- **Data Cleaning:**  
  - Removed rows with missing values.
  - Divided the Marvel data into three sets:  
    1. All movies/series  
    2. Movies/series in the first three phases (up to 2019)  
    3. Movies/series in the 4th and 5th phases (post-2019)
- **Exploratory Data Analysis (EDA):**  
  - Constructed rating histograms and box plots (budget and box office).  
  - Analyzed the top 20 emojis by frequency in reviews.
- **Text and Sentiment Analysis:**  
  - Processed review texts and computed polarities.
  - Applied sentiment analysis with the top 20 trigrams as topics.

## Results
- Generated box plots for both US & Canada and worldwide box office earnings.
- Identified a shift in audience preferences over time.
- Compared Vader polarity scores across different phases.
- Extracted insights:
  - **Positive Elements:** Noted in movies up to *Spider-Man: Far From Home*.
  - **Negative Elements:** Issues such as visual effects, character development, action sequences, scene overuse, and plot holes in movies post *Spider-Man: Far From Home*.

## Recommendations
- **Enhance Special Effects & Action:**  
  Given their significance in both positive and negative feedback, continue investing in cutting-edge visual and action sequences.
- **Focus on Narrative Quality:**  
  Address audience concerns regarding plot holes and character development by refining the creative direction.
- **Innovate Scene Management:**  
  Experiment with new storytelling techniques to reduce scene overuse.
- **Leverage Star Power:**  
  Continue engaging beloved actors (e.g., Robert Downey Jr., Tom Holland) to sustain positive audience sentiment.

---

