# Analytics for Unstructured Data: Entry-Level Luxury Car Market Analysis

## Project Overview
This project was developed as part of the "Analytics for Unstructured Data" course. The task is to analyze social media conversations to provide insights for JD Power and Associates about the entry-level luxury car market in the USA. The analysis leverages web scraping, natural language processing (NLP), statistical analysis, and data visualization.

## Objective
The main goal is to perform a competitive analysis of entry-level luxury cars based on data collected from the Edmunds.com discussion forums. Insights will inform decision-making regarding customer preferences, brand perception, and market trends.

## Key Features
1. **Web Scraping**: Extracted 5000+ posts from the Entry-Level Luxury Performance Sedans forum.
2. **NLP and Statistical Analysis**: Applied Zipf's law, frequency analysis, and lift ratio calculations.
3. **Data Visualization**: Created an MDS map to visualize brand associations.
4. **Business Insights**: Generated actionable insights for client strategy.

## Dataset
- Source: Edmunds.com discussion forums
- Target: Entry-Level Luxury Performance Sedans Forum
- Format: CSV with columns `date` and `message`

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: BeautifulSoup, Pandas, NLTK, Matplotlib, Scikit-learn
- **Visualization Tools**: MDS plot, frequency charts

---

## Tasks and Methodology

### Task A: Testing Zipf's Law
- **Objective**: Validate Zipf's law for the dataset.
- **Method**:
  - Count word frequencies (without removing stopwords).
  - Plot top 100 words against theoretical predictions of Zipf's law.
- **Outcome**:
  - Visualization of word frequency vs. rank.

### Task B: Brand Frequency Analysis
- **Objective**: Identify the top 10 brands.
- **Method**:
  - Map car models to brands.
  - Count unique brand mentions per post (ignoring stopwords).
- **Outcome**:
  - Frequency table of the top 10 brands.

### Task C: Lift Ratio Calculations
- **Objective**: Analyze associations between top brands.
- **Method**:
  - Calculate lift ratios for co-occurrences of brands within a 5-7 word window.
- **Outcome**:
  - Lift ratio table.

### Task D: MDS Map
- **Objective**: Visualize brand relationships.
- **Method**:
  - Perform multidimensional scaling (MDS) analysis.
  - Plot brands on a 2D map.
- **Outcome**:
  - MDS map depicting brand associations.

### Task E: Insights from Lift and MDS Analysis
- **Objective**: Provide insights based on brand associations.
- **Method**:
  - Interpret lift values and MDS map clusters.
- **Outcome**:
  - Recommendations for marketing and competitive positioning.

### Task F: Feature Analysis
- **Objective**: Identify attributes associated with top brands.
- **Method**:
  - Frequency analysis of car attributes.
  - Map attributes to brands.
- **Outcome**:
  - Frequency table of attributes.
  - Attribute-brand mapping.

### Task G: Recommendations for Clients
- **Objective**: Suggest strategies based on attribute analysis.
- **Outcome**:
  - Business recommendations.

### Task H: Aspirational Brand Analysis
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
3. **Top Brands**:
   - Frequency table.
4. **Lift Ratios**:
   - Tabular output of brand co-occurrence metrics.
5. **MDS Map**:
   - Visual representation of brand associations.
6. **Attribute Analysis**:
   - Frequency table and mapping to brands.

---

## Project Structure
- `Assignemt_1_Unstructrued_data_analytics.ipynb`: Python notebook containing code and analysis.
- `data/`: Folder containing scraped data (CSV format).
- `images/`: Folder containing visualizations (e.g., Zipf's law plot, MDS map).

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   - Use Jupyter Notebook or Jupyter Lab to open `Assignemt_1_Unstructrued_data_analytics.ipynb`.

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
- Course: MSBA F2024, University of Texas at Austin
- Instructor: [Name of Instructor]
- Resources: [Gary Sieling's Blog](http://www.garysieling.com/blog/exploring-zipfs-law-with-python-nltk-scipy-and-matplotlib), Edmunds.com
