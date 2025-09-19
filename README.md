# NFL Kicker Analysis - 2025 Data Bowl

## Project Overview
This project analyzes NFL kicker performance using 2025 Data Bowl data, focusing on Week 1 statistics to identify the best and worst performing kickers using various analytical methods including PCA (Principal Component Analysis).

## Files Description

### Analysis Files
- `NFL_kicker_cut_predictions.ipynb` - Main Jupyter notebook containing comprehensive kicker analysis
- `kickers.Rmd` - R Markdown file for additional R-based analysis
- `NFL_kicker_analysis.Rmd` - Original R Markdown analysis file

### Data Files
- `nfl_kick_attempts(in).csv` - Input dataset containing NFL kick attempt data

### Supporting Files
- `kickers_read_csv.R` - R script for data loading
- `install_dplyr.R` - R script for package installation
- `renv.lock` - R environment lock file
- `renv/` - R environment management directory

## Analysis Features

### Key Analyses Performed
1. **Basic Statistics**
   - Field goal percentage calculations
   - Kick distance analysis
   - Score differential impact

2. **Custom Weighted Scoring**
   - FG% (50% weight)
   - Average kick distance (20% weight)
   - Close game performance (20% weight)
   - Games played (10% weight)

3. **Principal Component Analysis (PCA)**
   - Feature importance analysis
   - Best and worst performer identification
   - Elbow plot for optimal components
   - 3-component analysis for performance ranking

4. **Performance Categories**
   - Most accurate kickers by various metrics
   - Worst performers analysis
   - Close game performance evaluation
   - Distance-based difficulty assessment

### Key Metrics Analyzed
- `fg_pct` - Field goal percentage
- `avg_distance` - Average kick distance
- `avg_score_diff` - Average score differential at kick time
- `attempts` - Number of kick attempts
- `made` - Number of successful kicks

## Technologies Used
- **Python**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **R**: dplyr, ggplot2, knitr
- **Jupyter Notebooks**: Interactive analysis environment
- **Git**: Version control

## Getting Started

### Prerequisites
- Python 3.x with packages: pandas, numpy, matplotlib, seaborn, scikit-learn
- R with packages: dplyr, ggplot2, knitr
- Jupyter Notebook

### Running the Analysis
1. Clone this repository
2. Ensure the CSV data file is in the project directory
3. Open `NFL_kicker_cut_predictions.ipynb` in Jupyter
4. Run cells sequentially for complete analysis

## Key Findings
The analysis identifies top-performing kickers using multiple methodologies:
- Traditional field goal percentage
- Weighted composite scoring
- PCA-based performance ranking
- Situational performance (close games, kick difficulty)

## Future Enhancements
- Seasonal trend analysis
- Weather impact on performance
- Playoff vs regular season comparison
- Multi-year performance tracking

## Author
NFL Data Bowl 2025 Analysis Project

## License
This project is for educational and analytical purposes as part of the NFL Data Bowl 2025.