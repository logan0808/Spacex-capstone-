 SpaceX Falcon 9 Landing Prediction & Dashboard

 📊 Project Overview
This project analyzes SpaceX Falcon 9 launch data to identify key factors that influence successful first-stage landings. It also includes an interactive dashboard for exploring launch performance.


 🎯 Objectives
- Analyze factors affecting landing success (payload, orbit, launch site)
- Perform exploratory data analysis using SQL and Python
- Build interactive visualizations using Plotly Dash and Folium
- Develop machine learning models to predict landing outcomes


 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- SQL
- Plotly Dash (Interactive dashboard)
- Folium (Geospatial visualization)
- Jupyter Notebook

 📈 Key Insights
- Launch success rate has improved significantly over time
- Payload mass and launch site strongly influence landing success
- Certain orbit types show higher success rates than others
- Falcon 9 Block 5 boosters have the highest success performance


 🤖 Machine Learning
- Built classification models (Logistic Regression, Decision Tree, KNN, SVM)
- Evaluated models using accuracy metrics
- Best model achieved approximately **83% accuracy** in predicting landing success


 📊 Dashboard Features
- Dropdown menu to filter by launch site
- Pie chart showing success distribution
- Scatter plot of payload vs landing outcome
- Range slider for payload filtering



 🌍 Interactive Map
- Visualized launch sites using Folium
- Displayed success (green) and failure (red) markers
- Analyzed proximity to infrastructure (coastline, roads)



## 🚀 How to Run
```bash
python3 spacex-dash-app.py
