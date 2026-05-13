#  IBM Data Science Capstone – SpaceX Falcon 9 Landing Prediction

An end-to-end data science capstone project focused on predicting the success of **SpaceX Falcon 9 first-stage landings** using historical launch data, machine learning, web scraping, SQL analysis, and interactive dashboards.

This project was completed as part of the **IBM Data Science Professional Certificate Capstone**, integrating the complete data science workflow from data collection to predictive modeling and visualization.

---

##  Project Overview

SpaceX significantly reduces launch costs by reusing the **Falcon 9 first stage booster**. Predicting whether the booster will successfully land can help estimate mission costs and improve launch planning.

In this project, we analyze Falcon 9 launch data to answer key business questions:

- Can we predict whether a Falcon 9 first-stage landing will be successful?
- Which launch features affect landing success?
- How do payload mass, launch sites, orbit types, and booster versions impact outcomes?

The project combines:

✅ API Data Collection  
✅ Web Scraping  
✅ Data Wrangling & Cleaning  
✅ SQL Analysis  
✅ Exploratory Data Analysis (EDA)  
✅ Interactive Visual Analytics  
✅ Machine Learning Prediction  
✅ Geospatial Visualization with Folium  
✅ Dashboard Development

---

##  Repository Structure

```bash
IBM-Data-Science-Capstone/
│
├── 01_Data_Collection_API.ipynb
├── 02_Web_Scraping.ipynb
├── 03_Data_Wrangling.ipynb
├── 04_SQL_Analysis.ipynb
├── 05_Interactive_Visual_Analytics.ipynb
├── 06_Machine_Learning_Prediction.ipynb
├── 07_Folium_App.ipynb
├── 08_Dashboard_App.ipynb
├── README.md
```

---

##  Project Workflow

###  Data Collection Using API
**Notebook:** `01_Data_Collection_API.ipynb`

Collected Falcon 9 launch data using the **SpaceX REST API**.

### Tasks Performed:
- Retrieved historical launch records
- Extracted mission details
- Collected payload mass, orbit type, booster version, launch site, and landing outcomes
- Converted raw JSON data into structured tabular format using **Pandas**

### Technologies Used:
- Python
- Requests
- Pandas
- JSON

---

###  Web Scraping
**Notebook:** `02_Web_Scraping.ipynb`

Scraped additional Falcon 9 launch information from public web sources.

### Tasks Performed:
- Extracted launch records from HTML tables
- Parsed webpage content
- Cleaned scraped data for consistency

### Technologies Used:
- BeautifulSoup
- Requests
- Pandas

---

###  Data Wrangling
**Notebook:** `03_Data_Wrangling.ipynb`

Cleaned and transformed collected datasets for analysis.

### Tasks Performed:
- Handled missing values
- Removed inconsistencies
- Feature engineering
- Converted categorical variables
- Created target variable for landing success prediction

### Technologies Used:
- Pandas
- NumPy

---

###  SQL Analysis
**Notebook:** `04_SQL_Analysis.ipynb`

Performed SQL-based exploratory analysis to answer business questions.

### Questions Explored:
- Which launch sites had the highest number of launches?
- Which missions were most successful?
- What payload ranges had better landing rates?
- Which booster versions performed best?

### Technologies Used:
- SQL
- SQLite
- Pandas

---

###  Interactive Visual Analytics
**Notebook:** `05_Interactive_Visual_Analytics.ipynb`

Conducted exploratory data analysis using interactive visualizations.

### Visualizations Included:
- Payload vs Landing Success
- Orbit Type Analysis
- Launch Site Performance
- Booster Version Comparison
- Correlation Insights

### Technologies Used:
- Plotly
- Matplotlib
- Seaborn
- Pandas

---

###  Machine Learning Prediction
**Notebook:** `06_Machine_Learning_Prediction.ipynb`

Built classification models to predict Falcon 9 landing success.

### Models Evaluated:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

### ML Workflow:
- Feature selection
- Data preprocessing
- Train-test split
- Hyperparameter tuning using GridSearchCV
- Model comparison
- Accuracy evaluation

### Metrics Used:
- Accuracy Score
- Classification Performance
- Cross-validation

### Technologies Used:
- Scikit-learn
- NumPy
- Pandas

---

### Geospatial Visualization
**Notebook:** `07_Folium_App.ipynb`

Built an interactive geospatial visualization of Falcon 9 launch sites.

### Features:
- Interactive launch site map
- Launch success/failure markers
- Distance calculations
- Nearby infrastructure visualization

### Technologies Used:
- Folium
- Geopy
- Pandas

---

###  Dashboard Application
**Notebook:** `08_Dashboard_App.ipynb`

Developed an interactive dashboard for exploring Falcon 9 launch data.

### Dashboard Features:
- Launch site selection
- Payload range filtering
- Launch success pie charts
- Scatter plot analysis
- Dynamic interaction

### Technologies Used:
- Plotly Dash
- Dash Core Components
- Dash HTML Components

---

##  Technologies & Tools

### Programming Language
- Python

### Libraries & Frameworks
- Pandas
- NumPy
- Requests
- BeautifulSoup
- SQL / SQLite
- Matplotlib
- Seaborn
- Plotly
- Dash
- Folium
- Scikit-learn

### Development Environment
- Jupyter Notebook
- IBM Watson Studio
- VS Code

---

##  Machine Learning Objective

The primary objective of this project is to build a predictive model capable of determining whether a **Falcon 9 first-stage landing will be successful**.

The target variable:

```python
Class = 1 → Successful Landing
Class = 0 → Failed Landing
```

Using historical launch attributes, machine learning models attempt to classify landing outcomes.

---

## Key Insights

- Certain launch sites showed higher success rates.
- Payload mass influences landing success probability.
- Orbit type affects mission outcomes.
- Booster versions impact reusability performance.
- Machine learning models can reasonably predict landing success.

---

##  How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/yourusername/IBM-Data-Science-Capstone.git
```

### Navigate to Project Folder

```bash
cd IBM-Data-Science-Capstone
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install pandas numpy matplotlib seaborn plotly dash folium scikit-learn beautifulsoup4 requests
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open notebooks sequentially:

1. `01_Data_Collection_API.ipynb`
2. `02_Web_Scraping.ipynb`
3. `03_Data_Wrangling.ipynb`
4. `04_SQL_Analysis.ipynb`
5. `05_Interactive_Visual_Analytics.ipynb`
6. `06_Machine_Learning_Prediction.ipynb`
7. `07_Folium_App.ipynb`
8. `08_Dashboard_App.ipynb`

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- End-to-end data science workflow
- Data collection using APIs
- Web scraping techniques
- Data cleaning and feature engineering
- SQL querying and business analysis
- Interactive data visualization
- Machine learning model building
- Dashboard development
- Geospatial analysis using Folium

---

##  Contributing

Contributions, feedback, and suggestions are welcome.

If you'd like to improve the project:

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit a pull request

---

##  License

This project is for educational and portfolio purposes.

---

## Author

**Luqman Abban**  
Data Analyst | Ecommerce Data Specialist | Aspiring AI & Data Professional

GitHub: `https://github.com/yourusername`

---

### ⭐ If you found this project useful, consider giving it a star!
