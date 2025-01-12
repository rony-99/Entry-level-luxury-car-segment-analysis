# Competitive Analysis: Entry-Level Luxury Car Market

## Project Overview
This project involves analyzing social media conversations to gain insights into the entry-level luxury car market in the USA. The analysis utilizes web scraping, natural language processing (NLP), statistical analysis, and data visualization to provide actionable insights for stakeholders.

## Objective
The primary goal is to conduct a competitive analysis of entry-level luxury cars using data collected from the Edmunds.com discussion forums. The insights aim to inform strategic decision-making regarding customer preferences, brand perception, and market trends.

## Key Features
1. **Web Scraping**: Extracted 5000+ posts from the Entry-Level Luxury Performance Sedans forum.
2. **NLP and Statistical Analysis**: Applied Zipf's law, frequency analysis, and lift ratio calculations.
3. **Data Visualization**: Created an MDS map to visualize brand associations.
4. **Business Insights**: Generated actionable insights for brand strategy and market positioning.

## Dataset
- **Source**: Edmunds.com discussion forums
- **Target**: Entry-Level Luxury Performance Sedans Forum
- **Format**: CSV with columns `date` and `message`

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: BeautifulSoup, Pandas, NLTK, Matplotlib, Scikit-learn
- **Visualization Tools**: MDS plot, frequency charts

---

## Methodology and Analysis

### 1. Testing Zipf's Law
- **Objective**: Validate Zipf's law for the dataset.
- **Method**:
  - Count word frequencies (without removing stopwords).
  - Plot top 100 words against theoretical predictions of Zipf's law.
- **Outcome**:
  - Visualization of word frequency vs. rank.
 


### 2. Brand Frequency Analysis
- **Objective**: Identify the top 10 brands.
- **Method**:
  - Map car models to brands.
  - Count unique brand mentions per post (ignoring stopwords).
- **Outcome**:
  - Frequency table of the top 10 brands.
 


### 3. Lift Ratio Calculations
- **Objective**: Analyze associations between top brands.
- **Method**:
  - Calculate lift ratios for co-occurrences of brands within a 5-7 word window.
- **Outcome**:
  - Lift ratio table.
 
 

  


### 4. MDS Map
- **Objective**: Visualize brand relationships.
- **Method**:
  - Perform multidimensional scaling (MDS) analysis.
  - Plot brands on a 2D map.
- **Outcome**:
  - MDS map depicting brand associations.
 
  




### 5. Feature Analysis
- **Objective**: Identify attributes associated with top brands.
- **Method**:
  - Frequency analysis of car attributes.
  - Map attributes to brands.
- **Outcome**:
  - Frequency table of attributes.
  - Attribute-brand mapping.

### 6. Aspirational Brand Analysis
- **Objective**: Determine the most aspirational brand.
- **Method**:
  - Analyze discussions for intent to purchase or own.
  - Assess brand desirability.
- **Outcome**:
  - Identified aspirational brand and its implications.

---

## Outputs and Visualizations
1. **Scraper Output**:
   - CSV file with `date` and `message` columns.
2. **Zipf's Law Plot**:
   - Top 100 words vs. theoretical predictions.
    
  ![image](https://github.com/user-attachments/assets/88c90885-1e18-4f47-99f2-12ab75d3d011)

  
3. **Top Brands**:
   - Frequency table.
  
    
  <img width="337" alt="image" src="https://github.com/user-attachments/assets/e0a1c563-11f5-4fa7-a698-632d19d3b0d4" />

  
4. **Lift Ratios**:
   - Tabular output of brand co-occurrence metrics.
  
     ![image](https://github.com/user-attachments/assets/dc893bc6-e0b2-4ed2-995d-70e1b78a7ae6)

     
5. **MDS Map**:
   - Visual representation of brand associations.
  
    ![image](https://github.com/user-attachments/assets/e4863cf8-0dd2-4f55-969d-840a6fe9da0b)

   
7. **Attribute Analysis**:
   - mapping to brands.
  
   ![image](https://github.com/user-attachments/assets/7185855a-3902-4fa5-99fd-3509ed2670d0)




---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Run the notebook:
   - Use Jupyter Notebook or Jupyter Lab to open `Entry_Level_Luxury_Analysis.ipynb`.

---

## Insights and Recommendations
1. **Market Trends**: Highlighted trends in consumer preferences.
2. **Brand Associations**: Identified strong associations and competitive clusters.
3. **Strategic Recommendations**:
   - Target marketing efforts towards aspirational segments.
   - Focus on features most valued by consumers.

---

## Authors
- Ronak Goyal and Team

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---

## Acknowledgments
- Resources: [Gary Sieling's Blog](http://www.garysieling.com/blog/exploring-zipfs-law-with-python-nltk-scipy-and-matplotlib), Edmunds.com
