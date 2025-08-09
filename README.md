# Real Estate Data Analysis with Pandas

[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-data-clean-up-pandas-for-beginners-project/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-data-clean-up-pandas-for-beginners-project/actions/workflows/codespaces/create_codespaces_prebuilds)

A comprehensive data science project focused on real estate market analysis using Python and Pandas. This project demonstrates essential data cleaning, exploration, and visualization techniques through practical exercises with real-world data.

![Project Preview](assets/preview.png)


## Project Overview

This project analyzes real estate data from **Fotocasa**, one of Spain's most popular real estate websites. The dataset contains thousands of house listings and provides hands-on experience with:

- Data loading and exploration
- Data cleaning and null value handling
- Statistical analysis
- Data visualization
- Market analysis and insights


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you loose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (dependencies are pre-installed)

3. **Start Working**
   - Open `notebooks/assignment.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook

### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.10

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/assignment.ipynb
   ```


## Project Structure

```
├── .devcontainer/        # Development container configuration
├── assets/               # Images and other files 
│
├── data/                 # Data file directory
│   └── real_estate.csv   # Real estate dataset
│
├── notebooks/            # Jupyter notebook directory
│   ├── assignment.ipynb  # Assignment notebook
│   └── solution.ipynb    # Solution notebook
│
├── .gitignore            # Files/directories not tracked by git
├── project.ipynb         # Main Jupyter notebook with exercises
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## Dataset

The dataset (`assets/real_estate.csv`) contains real estate listings with the following key features:
- **Price**: Property prices in USD
- **Surface**: Property area in square meters
- **Location**: Hierarchical location data (country, regions, populations)
- **Property details**: Rooms, bathrooms, and other characteristics
- **Real estate information**: Agency details and contact information

**Note**: This dataset was collected for academic purposes only. No commercial benefit was obtained from web scraping activities.


## Learning Objectives

1. **Data Exploration**: Load and examine the real estate dataset
2. **Extreme Value Analysis**: Find most/least expensive and largest/smallest properties
3. **Geographic Analysis**: Count unique populations and analyze regional data
4. **Data Quality Assessment**: Identify and handle null values
5. **Market Analysis**: Calculate average prices by location
6. **Data Visualization**: Create histograms and analyze price distributions

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
