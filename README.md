# F1 Driver Championship Performance Analysis

## Project Overview
This project analyzes and visualizes F1 (Formula 1) driver championship performance across multiple seasons to identify patterns in driver dominance, consistency, and career trajectories. We compare top drivers' points progression, win rates, podium finishes, and other key metrics to understand what makes champions successful.



## Project Objectives

### Key Questions to Answer:
1. What factors determine championship success?
2. How do different drivers' performances compare across seasons?
3. What's the relationship between pole positions and race wins?
4. Which driver had the most consistent performance?
5. How did different drivers' careers peak and decline?

## Project Structure

```
F1-Driver-Championship-Analysis/
│
├── README.md                          # Project overview
├── requirements.txt                   # Python dependencies
├── .gitignore                         # Git ignore file
│
├── data/
│   ├── raw/                           # Raw F1 data (downloaded)
│   │   ├── races.csv
│   │   ├── drivers.csv
│   │   └── results.csv
│   └── processed/                     # Cleaned data
│       └── f1_processed_data.csv
│
├── notebooks/
│   ├── 1_data_collection.ipynb        # Data loading and exploration
│   ├── 2_data_preprocessing.ipynb     # Data cleaning
│   ├── 3_visualizations.ipynb         # Create charts
│   ├── 4_analysis.ipynb               # Statistical analysis
│   └── main_analysis.ipynb            # Combined notebook
│
├── src/
│   ├── __init__.py
│   ├── data_loader.py                 # Data loading functions
│   ├── data_preprocessor.py           # Cleaning and preprocessing
│   ├── visualizations.py              # Visualization functions
│   └── analysis.py                    # Analysis functions
│
├── visualizations/
│   ├── 01_points_progression.png
│   ├── 02_championship_wins.png
│   ├── 03_career_heatmap.png
│   ├── 04_head_to_head.png
│   └── 05_interactive_dashboard.html
│
├── report/
│   ├── F1_Driver_Championship_Report.pdf
│   └── report_template.md
│
└── presentation/
    └── F1_Analysis_Presentation.pptx
```



## Key Visualizations

1. **Points Progression Through Season** - Line graph showing cumulative points race-by-race
2. **All-Time Championship Wins** - Bar chart of drivers with most championships
3. **Career Performance Heatmap** - Shows points earned by driver across multiple seasons
4. **Head-to-Head Rivalry** - Compare top drivers' performances
5. **Interactive Dashboard** - Plotly-based interactive exploration

## Data Sources

- **Kaggle:** Formula 1 World Championship Dataset (1950-2024)
- **Ergast API:** Real-time F1 statistics (http://ergast.com/api/f1/)
- **Official F1 Website:** ESPN F1 statistics

## Technologies Used

- **Python 3.8+**
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computations
- **Matplotlib:** Static visualizations
- **Seaborn:** Statistical data visualization
- **Plotly:** Interactive visualizations
- **Jupyter Notebook:** Development environment

## Installation

```bash
# Clone the repository
git clone https://github.com/fsaleem471/F1-Driver-Championship-Analysis.git
cd F1-Driver-Championship-Analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

```bash
# Run Jupyter notebook
jupyter notebook notebooks/main_analysis.ipynb
```

## Key Findings (To be updated)

- Placeholder for main discoveries
- Driver dominance patterns
- Career trajectory insights
- Statistical correlations

## Timeline

| Phase | Duration | Status |
|-------|----------|--------|
| Data Collection | 3-4 days | ⏳ |
| Data Preprocessing | 2-3 days | ⏳ |
| Visualizations | 4-5 days | ⏳ |
| Analysis | 2-3 days | ⏳ |
| Report Writing | 2-3 days | ⏳ |
| Presentation | 1-2 days | ⏳ |

## Submission Checklist

- [ ] Data collection complete
- [ ] Data preprocessing complete
- [ ] All visualizations created
- [ ] Analysis and insights documented
- [ ] PDF report generated
- [ ] Code commented and documented
- [ ] README updated
- [ ] Repository ready for submission

## Author
**Farhan Saleem Kiani**
- 
- IQRA University Islamabad
- Batch: AI-FA-23

## Submission Details
- **Due Date:** 09 June 2026
- **Presentation Date:** 15-18 June 2026
- **Format:** PDF Report + Python Code + Presentation

## References

- Ergast Developer API: http://ergast.com/
- Kaggle F1 Dataset: https://www.kaggle.com/
- Formula1.com Official: https://www.formula1.com/
- Matplotlib Documentation: https://matplotlib.org/
- Seaborn Documentation: https://seaborn.pydata.org/
- Plotly Documentation: https://plotly.com/

## License
This project is for educational purposes at IQRA University Islamabad.

---

**Last Updated:** 11 June 2026
