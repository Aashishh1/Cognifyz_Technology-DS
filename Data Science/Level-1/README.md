<div align='center'><img style="width:30%" src='https://github.com/user-attachments/assets/d8006ac3-d3ea-4141-8d40-43e7d8172ad8'/></div>

This comprehensive report outlines the methodology and findings from three critical tasks: Data Exploration and Preprocessing, Descriptive Analysis, and Geospatial Analysis. Each task is meticulously documented with clear steps, detailed insights, and impactful visualizations to provide a holistic understanding of the dataset. 🚀

---
## Task Overview 📃

| **Task**    | **Description**                                                                                   |
|-------------|---------------------------------------------------------------------------------------------------|
| **Task 1**  | Data Exploration and Preprocessing: Handle missing values, remove duplicates, and analyze data distributions. |
| **Task 2**  | Descriptive Analysis: Calculate statistical measures and analyze categorical variables.           |
| **Task 3**  | Geospatial Analysis: Visualize restaurant locations and analyze location-based patterns.          |

---

## Task 1: Data Exploration and Preprocessing 🔍

### Steps Completed:

1. **Load Data:**
   - Imported the dataset using `pandas`.
   - Displayed the first few rows and data info.

2. **Handle Missing Values:**
   - Filled missing values in the `Cuisines` column with "Unknown".

3. **Remove Duplicates:**
   - Identified and removed duplicate rows from the dataset.

4. **Analyze Target Variable:**
   - Explored the distribution of the `Aggregate rating` column using histograms.

### Key Insights:

- Missing values in `Cuisines` were handled effectively.
- The `Aggregate rating` distribution showed a slightly skewed pattern.

### Visualization:

| **Visualization**              | **Description**                                                             |
|--------------------------------|-----------------------------------------------------------------------------|
| Histogram of Aggregate Ratings | Displayed the frequency of aggregate ratings with KDE for smoothness.       |

---

## Task 2: Descriptive Analysis 📊

### Steps Completed:

1. **Summary Statistics:**
   - Calculated mean, median, and standard deviation for numerical columns.

2. **Analyze Categorical Variables:**
   - Explored the distribution of `Country Code`, `City`, and `Cuisines`.
   - Visualized top 20 cities and cuisines with the highest number of restaurants.

3. **Identify Top Entries:**
   - Listed top 10 cuisines and cities by the number of restaurants.

### Key Insights:

- Significant variation observed in `Average Cost for two` and `Votes`.
- Cities like New York and Delhi NCR dominate the restaurant count.

### Visualization:

| **Visualization**                | **Description**                                                            |
|----------------------------------|----------------------------------------------------------------------------|
| Countplot of Country Codes       | Showed the number of restaurants per country.                              |
| Top 20 Cities by Restaurants     | Bar chart displaying cities with the highest number of restaurants.        |
| Top 20 Cuisines by Restaurants   | Bar chart displaying the most popular cuisines.                            |

---

## Task 3: Geospatial Analysis 🌍

### Steps Completed:

1. **Map Visualization:**
   - Visualized restaurant locations using latitude and longitude.
   - Created scatter plots to represent geographic patterns.

2. **Location-Based Analysis:**
   - Analyzed restaurant distribution across cities and countries.
   - Explored correlation between location and aggregate rating.

### Key Insights:

- High-density clusters observed in urban areas.
- Strong correlation between prime locations and higher ratings.

### Visualization:

| **Visualization**                | **Description**                                                            |
|----------------------------------|----------------------------------------------------------------------------|
| Global Restaurant Distribution   | Scatter plot of restaurant locations on a world map.                       |
| Correlation Analysis             | Heatmap to explore relationships between location and ratings.             |

---

## Conclusion ✅

This analysis provides valuable insights into the dataset, including rating distributions, popular cuisines, and location-based patterns. By preprocessing the data, conducting descriptive analysis, and leveraging geospatial techniques, meaningful conclusions were drawn to support business decisions. 💡

---

_Thank you for checking out the project! 🌟_
