# Real Estate Data Analysis with Pandas

A comprehensive data science project focused on real estate market analysis using Python and Pandas. This project demonstrates essential data cleaning, exploration, and visualization techniques through practical exercises with real-world data.

![Project Preview](assets/preview.png)

## Project Overview

This project analyzes real estate data from **Fotocasa**, one of Spain's most popular real estate websites. The dataset contains thousands of house listings and provides hands-on experience with:

- Data loading and exploration
- Data cleaning and null value handling
- Statistical analysis
- Data visualization
- Market analysis and insights

## Dataset

The dataset (`assets/real_estate.csv`) contains real estate listings with the following key features:
- **Price**: Property prices in USD
- **Surface**: Property area in square meters
- **Location**: Hierarchical location data (country, regions, populations)
- **Property details**: Rooms, bathrooms, and other characteristics
- **Real estate information**: Agency details and contact information

**Note**: This dataset was collected for academic purposes only. No commercial benefit was obtained from web scraping activities.

## Getting Started

### Prerequisites

- Python 3.11+
- Jupyter Notebook or VS Code with Jupyter extension
- Required packages (see `requirements.txt`)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/4GeeksAcademy/gperdrizet-data-clean-up-pandas-for-beginners-project.git
   cd gperdrizet-data-clean-up-pandas-for-beginners-project
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the project**:
   ```bash
   jupyter notebook project.ipynb
   ```
   
   Or open `project.ipynb` in VS Code with the Jupyter extension.

### Using Dev Container (Recommended)

This project includes a dev container configuration for a consistent development environment:

1. Open in VS Code
2. Install the "Dev Containers" extension
3. Press `Ctrl+Shift+P` and select "Dev Containers: Reopen in Container"
4. The environment will be automatically configured with all dependencies

## Project Structure

```
├── .devcontainer/          # Development container configuration
├── assets/                 # Data files and resources
│   ├── preview.png        # Project preview image
│   └── real_estate.csv    # Real estate dataset
├── project.ipynb          # Main Jupyter notebook with exercises
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## Learning Objectives

### Part 1: Basic Python Practices
- Variable declaration and data types
- Working with lists and dictionaries
- Basic statistical calculations

### Part 2: Pandas Data Analysis
- Loading and exploring CSV data
- Data cleaning and null value handling
- Finding extremes (min/max values)
- Counting unique values
- Filtering and grouping data
- Statistical analysis and visualization

## Key Exercises

1. **Data Exploration**: Load and examine the real estate dataset
2. **Extreme Value Analysis**: Find most/least expensive and largest/smallest properties
3. **Geographic Analysis**: Count unique populations and analyze regional data
4. **Data Quality Assessment**: Identify and handle null values
5. **Market Analysis**: Calculate average prices by location
6. **Data Visualization**: Create histograms and analyze price distributions

## Key Findings

Based on the analysis of the cleaned dataset:

- **Dataset Size**: 5,367 properties across 38 unique locations
- **Price Range**: Properties range from ~$165K to $8M USD
- **Most Expensive**: Alcobendas - $8,000,000 USD
- **Geographic Coverage**: Comprehensive coverage of Madrid metropolitan area
- **Arroyomolinos Analysis**: 110 properties with average price of $298,780

## Sample Visualizations

The project includes price distribution analysis with:
- Histogram visualizations
- Statistical summaries (mean, median, standard deviation)
- Market trend analysis
- Data quality assessments

## Technologies Used

- **Python 3.11**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Data visualization
- **Jupyter**: Interactive development environment

## Contributing

This is an educational project. Contributions for improving the analysis or adding new insights are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Legal Notice

This project uses data obtained through web scraping for **academic purposes only**. The dataset was collected by Henry Navarro with no commercial intent. Please respect website terms of service and use data responsibly.
