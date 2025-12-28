# India's Critical Minerals: Import-Export Analysis & Forecasting

## 🎯 Project Overview

This project provides a comprehensive analysis of India's import-export dependency and domestic production patterns for critical minerals essential for economic growth, clean energy transition, and national security. Using historical trade and production data (2017-2024), we analyze three key critical minerals - **Copper, Graphite, and Lithium (Electrodes)** - to identify strategic vulnerabilities, value-chain gaps, and forecast future trends.

## 📋 Problem Statement

India has identified several critical minerals essential for economic growth, clean energy transition, and national security. However, the country remains highly dependent on imports for many of these minerals, exposing it to:
- Supply chain disruptions
- Global price volatility
- Strategic vulnerabilities
- Limited domestic processing capacity

This project analyzes India's Export-Import (EXIM) and production data to identify trade dependencies, production gaps, and future trends using time-series forecasting.

## 🎯 Objectives

1. **Analyze Trade Patterns**: Examine import-export trends for ores, minerals, and specific critical minerals
2. **Identify Dependencies**: Quantify India's import dependency across different mineral categories
3. **Production Analysis**: Evaluate domestic production capabilities and gaps
4. **Forecast Future Trends**: Predict demand and trade patterns for 2026-2035 using time-series forecasting
5. **Strategic Insights**: Provide data-driven recommendations for policy and infrastructure planning

## 🔍 Key Features

### Overall Analysis
- **Comprehensive Trade Analysis**: Monthly import-export trends for ores and minerals
- **Trade Balance Assessment**: Export vs. import percentage analysis
- **Time-Series Visualization**: Historical trends and future forecasts

### Mineral-Specific Analysis

#### 1. **Copper**
- Production analysis (ore and concrete production)
- Import-export trade patterns
- Trade balance forecasting
- Production value trends

#### 2. **Graphite**
- Production and value analysis
- Import-export parity assessment
- Trade balance trends
- Production forecasting

#### 3. **Lithium Electrodes**
- Import-export dependency analysis
- Trade balance trends
- Future demand forecasting

## 📊 Key Findings

### Overall Trade Analysis
- **Import Dependency**: 88.44% of total trade is imports
- **Export Share**: Only 11.56% of total trade is exports
- **Trend**: Import share has been increasing over time, highlighting growing domestic demand

### Copper Insights
- Production shows growth but remains volatile
- Imports consistently exceed exports, indicating domestic supply constraints
- Dependency driven by **processing bottlenecks** rather than geological limitations
- Ore production accounts for 96.71% vs. 3.29% concrete production

### Graphite Insights
- **Near Parity**: 50.22% exports, 49.78% imports
- Rising imports alongside exports indicate quality differentiation
- India likely exports lower-grade graphite while importing battery-grade material
- **Opportunity**: Near-term potential for import substitution with improved processing capacity

### Lithium Electrodes Insights
- **High Dependency**: 72.71% imports, 27.29% exports
- Sharp increase in imports post-2021, aligned with EV and battery manufacturing growth
- Exports remain limited and volatile
- **Highest Strategic Risk**: Complete upstream dependency

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical visualization
- **Prophet**: Time-series forecasting (Facebook Prophet)
- **Jupyter Notebook**: Interactive analysis environment

## 📁 Dataset Information

### Data Sources
- **DGCI&S** (Directorate General of Commercial Intelligence and Statistics) Import-Export datasets
- **Indian Bureau of Mines** production data
- **Ministry of Commerce and Industry** trade records
- **Time Period**: 2017-2024 (historical data)

### Datasets Included
- `ORES_AND_MINERALS_EXIM.xlsx` - Overall ores and minerals trade data
- `COPPER_PRODUCTION.xlsx` - Copper production data
- `COPPER AND PRODUCTS MADE OF COPPER IMPORT EXPORT DATA.csv` - Copper trade data
- `COPPER PRODUCTION DATA.csv` - Copper production statistics
- `GRAPHITE IMPORT EXPORT DATA.csv` - Graphite trade data
- `GRAPHITE PRODUCTION AND VALUE DATA.csv` - Graphite production statistics
- `graphite_exim_data.xlsx` - Graphite trade data (Excel format)
- `graphite_production_data.xlsx` - Graphite production data (Excel format)
- `LITHIUM-ELECTRODES-EXPORT-IMPORT-DATA.csv` - Lithium electrodes trade data
- `Lithium_Electrodes_EXIM.xlsx` - Lithium electrodes trade data (Excel format)

## 🚀 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd CODEVATIVE_IITD
   ```

2. **Install required packages**
   ```bash
   pip install pandas numpy matplotlib seaborn prophet jupyter openpyxl
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the analysis notebook**
   - Open `CODEVATIVE_EXIM_ANALYSIS.ipynb` in Jupyter Notebook

## 📖 Usage

1. **Ensure datasets are in the correct location**
   - All datasets should be in the `Datasets/` folder
   - Maintain the folder structure as provided

2. **Run the notebook cells sequentially**
   - The notebook is organized into sections:
     - Overall Ores & Minerals Trade Analysis
     - Mineral-wise Analysis (Copper, Graphite, Lithium)
     - Forecasting Results
     - Consolidated Insights

3. **View visualizations**
   - All plots and charts are generated inline
   - Forecasts include confidence intervals

4. **Interpret results**
   - Review key insights sections for each mineral
   - Examine forecasting results for future trends

## 📈 Forecasting Methodology

- **Model**: Facebook Prophet (additive time-series model)
- **Features**:
  - Yearly seasonality
  - Monthly seasonality (custom)
  - Trend detection
  - Confidence intervals
- **Forecast Period**: 2026-2035 (10-year projection)
- **Output**: Monthly predictions with upper and lower bounds

## 🎯 Strategic Recommendations

Based on the analysis:

1. **Copper**: Invest in beneficiation and refining infrastructure to reduce processing bottlenecks
2. **Graphite**: Enhance processing capacity for battery-grade material to achieve import substitution
3. **Lithium**: Highest priority - develop upstream mining and processing capabilities to reduce strategic vulnerability
4. **Policy**: Implement strategic reserves and diversify import sources
5. **Infrastructure**: Focus on value-addition capabilities across the mineral supply chain

## 🔮 Future Work

- [ ] Expand analysis to include more critical minerals
- [ ] Incorporate price volatility analysis
- [ ] Add country-wise import source analysis
- [ ] Develop interactive dashboards
- [ ] Implement real-time data integration
- [ ] Create policy impact simulation models
- [ ] Add environmental impact assessment

## 📝 Project Structure

```
CODEVATIVE_IITD/
│
├── CODEVATIVE_EXIM_ANALYSIS.ipynb    # Main analysis notebook
├── Datasets/                          # All data files
│   ├── COPPER_*.csv/xlsx
│   ├── GRAPHITE_*.csv/xlsx
│   ├── LITHIUM_*.csv/xlsx
│   └── ORES_*.csv/xlsx
├── README.md                          # This file
└── LICENSE                            # MIT License
```

## 👥 Contributors

- **Arshil Masood** (Team Leader) - Frontend Developer
- **Kamran Rizvi** -  Data Analyst
- **Pranav Mishra** - Data Analyst and Backend Developer
- **Ammar Khan** - Full Stack Developer
- **Abdullah Ansari** - Frontend Developer

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Data Sources**:
  - Directorate General of Commercial Intelligence and Statistics (DGCI&S)
  - Indian Bureau of Mines
  - Ministry of Commerce and Industry, Government of India

- **Libraries**:
  - Facebook Prophet for time-series forecasting
  - Python data science ecosystem

## 📧 Contact

For questions, suggestions, or collaborations, please open an issue in the repository.

---

**Note**: This analysis is based on historical data and forecasting models. Results are indicative and intended to support policy-level decision-making. Actual future trends may vary based on policy interventions, market conditions, and technological developments.

