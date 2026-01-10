# 📊 Exploratory Data Analysis Projects

Welcome to my EDA Projects repository! This collection showcases hands-on exploratory data analysis techniques using Python and popular data science libraries.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Projects](#projects)
  - [Project 1: Word Cloud Generator](#project-1-word-cloud-generator)
  - [Project 2: Zomato Data Analysis](#project-2-zomato-data-analysis)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Key Learnings](#key-learnings)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 🎯 Overview

This repository contains **Exploratory Data Analysis (EDA)** projects that demonstrate:

- Data cleaning and preprocessing techniques
- Statistical analysis and insights extraction
- Data visualization using modern libraries
- Real-world data interpretation skills

Each project is implemented in Jupyter Notebook format for interactive exploration and learning.

---

## 🚀 Projects

### Project 1: Word Cloud Generator

**📁 File:** [`EDAProject_1_Generating_Word_Cloud.ipynb`](EDAProject_1_Generating_Word_Cloud.ipynb)

#### 🎨 Project Description

This project demonstrates text analysis and visualization through the creation of stunning word clouds. Word clouds are visual representations where the size of each word indicates its frequency or importance in the text.

#### 🎯 Objectives

- Process and clean text data
- Analyze word frequency distributions
- Generate visually appealing word clouds
- Customize word cloud appearance (colors, shapes, fonts)

#### 🛠️ Key Techniques

- Text preprocessing (removing stop words, punctuation)
- Natural Language Processing (NLP) basics
- Word frequency analysis
- Custom mask creation for shaped word clouds

#### 💡 Use Cases

- Social media sentiment analysis
- Document summarization
- Brand perception analysis
- Literature and content analysis

#### 📊 Expected Outputs

- Interactive word clouds with customizable parameters
- Frequency distribution charts
- Comparison of multiple text sources

---

### Project 2: Zomato Data Analysis

**📁 File:** [`EDAProject_2_Zomato_Data_Analysis.ipynb`](EDAProject_2_Zomato_Data_Analysis.ipynb)

#### 🍽️ Project Description

An in-depth analysis of Zomato restaurant data to uncover patterns, trends, and insights about the food industry. This project explores restaurant ratings, cuisines, pricing, locations, and customer preferences.

#### 🎯 Objectives

- Understand restaurant distribution across cities/locations
- Analyze rating patterns and factors affecting ratings
- Explore cuisine popularity and diversity
- Investigate price ranges and their correlation with ratings
- Identify top-performing restaurants and trends

#### 🛠️ Key Techniques

- Data cleaning and handling missing values
- Descriptive statistical analysis
- Correlation analysis
- Categorical data analysis
- Advanced data visualization (heatmaps, scatter plots, bar charts)
- Geospatial analysis (if location data available)

#### 📈 Analysis Areas

1. **Rating Analysis**: Distribution of ratings, factors influencing high ratings
2. **Cuisine Analysis**: Most popular cuisines, regional preferences
3. **Price Analysis**: Average costs, price vs rating correlation
4. **Location Analysis**: Restaurant density by area, hotspot identification
5. **Service Analysis**: Online delivery vs dine-in preferences

#### 💡 Business Insights

- Identify market gaps and opportunities
- Understand customer preferences
- Benchmark restaurant performance
- Guide restaurant owners on pricing and service strategies

#### 📊 Expected Outputs

- Comprehensive statistical summaries
- Interactive visualizations (charts, graphs, maps)
- Correlation matrices
- Key findings and recommendations

---

## 🛠️ Technologies Used

| Technology           | Purpose                             |
| -------------------- | ----------------------------------- |
| **Python 3.x**       | Core programming language           |
| **Pandas**           | Data manipulation and analysis      |
| **NumPy**            | Numerical computations              |
| **Matplotlib**       | Static visualizations               |
| **Seaborn**          | Statistical data visualization      |
| **WordCloud**        | Word cloud generation (Project 1)   |
| **NLTK/spaCy**       | Text processing (Project 1)         |
| **Jupyter Notebook** | Interactive development environment |

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python 3.7+ installed on your system.

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd EDA_Projects
   ```

2. **Install required packages**

   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud nltk jupyter
   ```

3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

4. **Open any project notebook** and run the cells sequentially!

### Quick Start

```python
# Example: Load and explore data
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Set visualization style
sns.set_style('whitegrid')

# Load your data
df = pd.read_csv('your_data.csv')

# Start exploring!
df.head()
```

---

## 📖 Key Learnings

Through these projects, you'll gain experience in:

✅ **Data Cleaning**

- Handling missing values
- Removing duplicates
- Data type conversions
- Outlier detection and treatment

✅ **Data Analysis**

- Descriptive statistics
- Correlation analysis
- Group-by operations
- Aggregations and pivot tables

✅ **Data Visualization**

- Choosing appropriate chart types
- Creating informative plots
- Customizing visualizations
- Storytelling with data

✅ **Insight Generation**

- Pattern recognition
- Trend identification
- Drawing actionable conclusions
- Presenting findings effectively

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:

- Fork the repository
- Create a new branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

---

## 📧 Contact

Have questions or suggestions? Feel free to reach out!

**Happy Analyzing! 📊✨**

---

## 📝 License

This project is open source and available for educational purposes.

---

### 🌟 Star this repository if you find it helpful!

_Last Updated: January 2026_
