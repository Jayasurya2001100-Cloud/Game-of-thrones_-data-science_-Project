# Game of Thrones Data Science Project

## Project Overview
This project analyzes data from the *Game of Thrones* series using Python and data science techniques. We explore key events such as battles and character deaths to uncover patterns and insights about the world of Westeros.

## Files in the Repository

### 1. `GoT+code+file.ipynb`
- **Type**: Jupyter Notebook
- **Description**: The main analysis notebook for this project.
- **Contents**:
  - Data cleaning and preprocessing steps.
  - Exploratory Data Analysis (EDA) using visualizations.
  - Insights on battles, houses, and character survival trends.
  - Custom metrics to analyze the outcome of battles and the impact of key events.

### 2. `battles.csv`
- **Type**: CSV File
- **Description**: Dataset containing details of battles in the *Game of Thrones* series.
- **Columns**:
  - `name`: Name of the battle.
  - `year`: Year the battle occurred.
  - `attacker_king` and `defender_king`: Kings involved in the battle.
  - `attacker_1` to `attacker_4`, `defender_1` to `defender_4`: Houses involved on both sides.
  - `battle_type`: Type of battle (e.g., pitched battle, siege).
  - `major_death` and `major_capture`: Indicators of significant events.
  - Other details, such as location, outcome, and commander stats.

### 3. `character-deaths.csv`
- **Type**: CSV File
- **Description**: Dataset detailing character deaths in the *Game of Thrones* series.
- **Columns**:
  - `Name`: Character name.
  - `Allegiances`: House or group allegiance.
  - `Death Year`: Year of death (if applicable).
  - `Book of Death`: Book in which the character dies.
  - `Gender` and `Nobility`: Character demographics.
  - Additional columns for circumstances of death.

## Setup Instructions

1. **Install Required Libraries**:
   Ensure you have Python installed along with the following libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. **Run the Notebook**:
   Open `GoT+code+file.ipynb` in Jupyter Notebook or VSCode and execute the cells to view the analysis.

3. **Data Files**:
   Place `battles.csv` and `character-deaths.csv` in the same directory as the notebook.

## Analysis Highlights

### Battles
- Identified patterns in outcomes based on house alliances.
- Analyzed relationships between battle types and major deaths or captures.
- Visualized the geographic distribution of battles across Westeros.

### Character Deaths
- Explored survival trends based on gender, nobility, and allegiance.
- Analyzed the correlation between a character's allegiance and their likelihood of survival.
- Highlighted key events that led to significant death tolls.

## Visualizations
This project includes:
- Heatmaps showing battle intensity across regions.
- Bar plots comparing the frequency of battles for different houses.
- Pie charts depicting character death distributions by allegiance.

## Future Work
- Incorporate additional datasets, such as house lineages or alliances.
- Use machine learning to predict character survival based on traits.
- Explore text analysis of dialogues from the books or scripts.

## Dependencies
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## Acknowledgments
- Datasets sourced from publicly available Game of Thrones resources.
- Inspired by the work of the fan community and data enthusiasts.

---
