# Twitter Link Analysis: News Source Distribution Research

**BSc Computer Science Thesis**  
University of Sussex, 2023  
Supervisor: Prof. David Weir

## Overview

This research examined how news sources are distributed across Twitter 
discussions on five topics: Politics, Government, Economy, Sports, and 
Entertainment. The study analyzed 5,000+ tweets to understand information 
dissemination patterns and source credibility variations.

## Research Questions

1. Which news sources are most frequently linked on Twitter?
2. How does news source distribution vary by topic?
3. What patterns emerge in information dissemination across topics?

## Methodology

- **Data Collection:** Python (snscrape library)
- **Data Processing:** pandas, URL resolution, text cleaning
- **Analysis:** Natural language processing, frequency analysis
- **Visualization:** matplotlib, wordcloud, pie charts, network graphs
- **Sample:** 1,000 tweets per topic (5,000 total)
- **Period:** January 2022 - March 2023
- **Language:** English-only tweets

## Key Findings

### Economy
- **CNBC dominated:** 62.9% of all economic news links
- High concentration: Top 3 sources = 75%+ of coverage

### Politics
- **More distributed:** greenmediashowbiz (21.9%), apple.com (16.3%)
- CNN and Fox News lower than expected (9% and 7.6%)

### Government
- **The Guardian led:** 14.6% of government news
- Daily Mail second: 12.4%

### Sports
- **Sporting News:** 33.5%
- No Smokes Sport: 24.3%
- More balanced distribution than economy

### Entertainment
- **Inner Beauty Challenge:** 18.2%
- Fairly balanced across top 5 sources

## Technical Stack

- Python 3.x
- snscrape (Twitter scraping)
- pandas (data manipulation)
- matplotlib (visualization)
- wordcloud (word cloud generation)
- Natural Language Processing techniques

## Research Implications

1. **News source diversity varies significantly by topic**
   - Economic coverage highly concentrated
   - Political coverage more distributed

2. **Non-traditional sources gaining prominence**
   - greenmediashowbiz outperformed CNN in politics sample
   - Suggests shifting media landscape

3. **Twitter as news dissemination platform**
   - Different patterns than traditional media consumption
   - User curation creates unique distribution patterns

## Limitations

- Sample size: 1,000 tweets per topic
- Time-bound: Jan 2022 - Mar 2023
- Language: English-only
- Platform: Twitter API restrictions
- Geographic: No location filtering

## Visualizations

*Word clouds, pie charts, and network graphs generated - see thesis document*

## Academic Context

This research contributes to understanding:
- Information dissemination on social media
- News source credibility patterns
- Topic-specific media consumption
- Digital journalism landscape

## Citation
```
Raharja, I. A. V. (2023). Twitter Link Analysis: News Source Distribution 
and Information Dissemination Patterns [View Final_Year_Project.pdf]. University 
of Sussex.
```

## Future Work

Potential extensions:
- Sentiment analysis of news coverage
- Real-time monitoring dashboard
- Comparative analysis across platforms (Twitter, Reddit, Bluesky)
- Misinformation detection and source verification
- Temporal trend analysis

## Contact

**Igusti Agung Vadayogi Raharja**  
LinkedIn: [linkedin.com/in/vadayogi](https://linkedin.com/in/vadayogi)  
Email: raharjaagungvadayogi@gmail.com

---

*Note: This repository contains research documentation. Original code 
remains on University of Sussex systems. Research conducted under 
supervision of Prof. David Weir, 2023.*
