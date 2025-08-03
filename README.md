# sleep-project
This project is an interactive **Sleep Disorder Analysis Dashboard** built using **Streamlit** and **Plotly**, aimed at exploring the factors influencing sleep quality and sleep disorders.

## Features

* **Data Loading & Cleaning:** Loads sleep-related data from a CSV file and replaces missing values in the "Sleep Disorder" column with "Normal".
* **Sidebar Filters:** Allows filtering visualizations by key categorical variables like Gender, Occupation, BMI Category, and Sleep Disorder.
* **Key Performance Indicators (KPIs):** Displays summary metrics including average age, count of participants, maximum daily steps, and average sleep duration.
* **Visualizations:**

  * Scatter plot showing the relationship between stress level and sleep quality, color-coded by the selected filter.
  * Bar chart displaying average sleep duration by occupation.
  * Pie chart comparing average sleep quality by gender.
  * Pair plot of selected numerical features to visualize relationships.
  * Correlation heatmap of key numerical variables including sleep duration, quality, physical activity, stress level, heart rate, and daily steps.

## Technologies Used

* Python
* Pandas & NumPy (data manipulation)
* Plotly Express (interactive visualizations)
* Seaborn & Matplotlib (statistical plotting)
* Streamlit (dashboard interface)

## How to Use

1. Install required libraries (`pandas`, `numpy`, `plotly`, `streamlit`, `seaborn`, `matplotlib`).
2. Place your sleep data CSV (`sleep.csv`) and image (`download.jpg`) in the working directory.
3. Run the Streamlit app with:

   ```bash
   streamlit run your_script_name.py
   ```
4. Use the sidebar to explore different filters and interact with the visualizations.

---

If you want, I can help you format it as a full README.md too!
