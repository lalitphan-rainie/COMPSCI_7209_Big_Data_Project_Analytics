# Crime, Housing Prices, and Urban Inequality: A Big Data Study in Adelaide, SA

## Project Overview

This project analyzes the relationship between crime rates and housing prices through exploratory data analysis and clustering techniques. The analysis aims to identify patterns and correlations between criminal activity and real estate values in Adealaide suburbs on spatial analysis.

## Project Structure
```
├── Data/
│   ├── Clean_Crime_Stats.csv
│   ├── Clean_House_Price.csv
│   └── ADL_Suburbs_shp.zip
├── Code/
│   ├── Crime_House_Suburbs_Modelling.ipynb
│   └── EDA_SA_Crime_House_Suburbs.ipynb
├── README.md
├── requirements.txt
└── COMP_SCI_7209_Assignment4_a1932456.pdf

```

## Dataset Description

The project uses 3 main datasets:

- **SA Crime Statistics**: Contains cleaned crime statistics including crime types, frequencies, and geographic information
- **SA House Rate & Sales Data**: Contains cleaned housing market data including prices, property characteristics, and location details

Both datasets have been preprocessed and cleaned for analysis.

- **Adelaide Suburb Shape Files**: Contains Adelaide Suburb geographical boundaries shape file, extract the zip file before use.

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd <repository-name>
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install required packages**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install Jupyter Notebook**
   ```bash
   pip install jupyter
   ```
   
   Or if you prefer JupyterLab:
   ```bash
   pip install jupyterlab
   ```

### Using Jupyter Notebooks

For interactive analysis, you can run the code in Jupyter notebooks.

## Key Findings & Methodology

All details of this project can be found in `COMP_SCI_7209_Assignment4_a1932456.pdf`

## File Descriptions

### Data Folder
- `Clean_Crime_Stats.csv`: Preprocessed crime statistics data
- `Clean_House_Price.csv`: Preprocessed housing market data
- `ADL_Suburbs_shp.zip`: Geographical boundaries shape file

### Code Folder
- `EDA_SA_Crime_House_Suburbs.ipynb`: Code for initial data exploration and statistical analysis
- `Crime_House_Suburbs_Modelling.ipynb`: Code for implementing clustering algorithms and model evaluation

## Contributing

This is a course assignment project. For any questions or suggestions, please contact [lalitphan.sae-teoh@student.adelaide.edu.au].

## Author

**Name**: Lalitphan Sae-teoh

**Course Name**: COMPSCI 7209 Big Data Project & Analysis - (Trimester2/2025) 

**Institution**: The University of Adelaide

## Acknowledgments

- Original Data sources: South Australia Government Data Dictionary, Data.SA – Government of South Australia, viewed 15 June 2025, https://data.sa.gov.au/data/dataset/.

---

*Last updated: 17/08/2025*

