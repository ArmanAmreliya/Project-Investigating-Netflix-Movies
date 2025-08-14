# 🍿 Netflix 1990s Movie Analysis

<div align="center">
  <img src="redpopcorn.jpg" alt="Netflix Analysis" width="200"/>
  
  [![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)](https://python.org)
  [![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)](https://pandas.pydata.org/)
  [![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-orange.svg)](https://matplotlib.org/)
  [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
</div>

## 📖 About The Project

Welcome to the **Netflix 1990s Movie Analysis** project! 🎬 

This project dives deep into the golden era of cinema - the 1990s - using Netflix's extensive movie database. Perfect for nostalgic movie lovers and data enthusiasts alike, this analysis explores movie durations, genres, and trends from one of the most iconic decades in film history.

### 🎯 What We Explore
- 📊 **Movie Duration Analysis** - Distribution patterns of 90s films
- 🎭 **Genre Deep Dive** - Focus on Action movies from the decade
- 📈 **Data Visualization** - Beautiful charts and insights
- 🔍 **Statistical Analysis** - Count and categorize movie characteristics

## 🚀 Getting Started

### Prerequisites
- Python 3.12+
- Jupyter Notebook
- Basic knowledge of data analysis

### 📦 Required Libraries
```python
import pandas as pd
import matplotlib.pyplot as plt
```

### 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd netflix-1990s-analysis
   ```

2. **Install required packages**
   ```bash
   pip install pandas matplotlib jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open `notebook.ipynb`** and start exploring!

## 📁 Project Structure

```
📦 Netflix-1990s-Analysis
 ┣ 📜 notebook.ipynb          # Main analysis notebook
 ┣ 📊 netflix_data.csv        # Netflix dataset
 ┣ 🖼️ redpopcorn.jpg         # Project banner image
 ┣ 🖼️ 14f056b7-7937-4255-bc91-8162859cc934.jpg  # Additional image
 ┗ 📜 README.md              # You are here!!
```

## 📊 Dataset Information

### 🎬 Netflix Data Schema
| Column | Description |
|--------|-------------|
| `show_id` | Unique identifier for each show |
| `type` | Content type (Movie/TV Show) |
| `title` | Title of the content |
| `director` | Director name(s) |
| `cast` | Main cast members |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Original release year |
| `duration` | Content duration (minutes for movies) |
| `description` | Plot description |
| `genre` | Primary genre classification |

## 🔍 Key Analysis Features

### 🎯 Movie Filtering
- **Decade Focus**: Movies released between 1990-1999
- **Type Filtering**: Movies only (excluding TV shows)
- **Genre Analysis**: Special focus on Action movies

### 📈 Visualizations
- **Duration Distribution**: Histogram showing movie length patterns
- **Statistical Insights**: Count analysis of short vs. long films
- **Data Exploration**: Interactive filtering and analysis

### 🏆 Key Findings
- **Most Common Duration**: ~100 minutes for 1990s movies
- **Action Movie Analysis**: Detailed breakdown of short action films
- **Trend Identification**: Patterns in movie production during the decade

## 🎨 Sample Visualizations

The notebook generates beautiful visualizations including:
- 📊 **Duration Distribution Histogram**
- 📈 **Genre Analysis Charts**
- 🎯 **Filtered Data Insights**

## 🤝 Contributing

Contributions are what make the open source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Usage Examples

### Quick Start
```python
# Load the data
netflix_df = pd.read_csv("netflix_data.csv")

# Filter for 1990s movies
movies_1990s = netflix_df[
    (netflix_df["type"] == "Movie") & 
    (netflix_df["release_year"] >= 1990) & 
    (netflix_df["release_year"] < 2000)
]

# Visualize duration distribution
plt.hist(movies_1990s["duration"])
plt.title('1990s Movie Duration Distribution')
plt.show()
```

## 🏷️ Tags
`#DataAnalysis` `#Netflix` `#Movies` `#1990s` `#Python` `#Pandas` `#Matplotlib` `#DataVisualization` `#Cinema` `#EDA`


## 🙏 Acknowledgments

- **Netflix** for providing the comprehensive dataset
- **The 1990s** for being an amazing decade for cinema
- **Open Source Community** for the fantastic tools and libraries
- **Movie Enthusiasts** everywhere who appreciate data-driven insights

---

<div align="center">
  <p><strong>⭐ Star this repository if you found it helpful! ⭐</strong></p>
  <p>Made with ❤️ and lots of ☕</p>
</div>

---

**Happy Analyzing! 🎬📊**


