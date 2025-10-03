#  Aviation Accident Data Analysis

##  Project Overview
This project analyzes aviation accident data (1919–2023) to identify trends, risk factors, and insights that can guide safer aviation practices.  
We used Python (Pandas, Matplotlib, Seaborn) to clean, analyze, and visualize the dataset.


# Tools & Libraries
- **Python** (3.10+)
- **Pandas** → data cleaning & analysis
- **Matplotlib** & **Seaborn** → visualizations
- **Jupyter Notebook** → interactive analysis


## Dataset
- **File**: `aviation-accident-data-2023-05-16.csv`  
- **Rows**: ~23,800 records  
- **Columns**:  
  - `date` – date of the accident  
  - `type` – aircraft type  
  - `operator` – airline/operator  
  - `fatalities` – number of fatalities  
  - `location` – where the accident occurred  
  - `country` – country of accident  
  - `year` – extracted year of accident  

---

## Key Steps
1. **Data Cleaning**
   - Converted `year` to numeric and removed invalid values (`unknown`, `NaN`).
   - Dropped rows with missing or ambiguous entries in critical columns.
   - Standardized column names for consistency.

2. **Exploratory Data Analysis (EDA)**
   - shows fatailites  (histogram).
   - Top 5 countries by accident counts (bar chart).
   - show fatailities over the year (line chart).

3. **Visualization**
   - Simple, clear charts to highlight safety insights.

## Results

### 1. Distribution of Fatalities
- Most accidents involve **0–5 fatalities**, meaning many are small-scale incidents.
- A few high-fatality accidents create long tails.

### 2. Countries with the Most Accidents
- Highest accident counts observed in **USA, Russia, Indonesia, Brazil, and India**.
- Indicates operational and regulatory differences.

### 3. Trends Over Time
- Accidents have **decreased significantly since the 1990s**, reflecting better safety regulations and technology improvements.

## Business Recommendations
1. **Highlight Modern Safety Improvements**  
   Accidents are decreasing over time; new aircraft and regulations make flying safer.  
   Marketing should emphasize these trends.

2. **Focus on Regional Safety Audits**  
   High-incident regions (e.g., Indonesia, Russia) need stricter compliance and training.  
   Entry into such markets should include additional safety protocols.

3. **Prioritize Smaller Aircraft Safety**  
   Most incidents involve smaller planes.  
   Extra investments in **pilot training** and **equipment upgrades** will mitigate risks.

this is the link to the [tableau dashboard](https://public.tableau.com/views/AviationAccident_17593162661470/AviationAccidents?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)








