# Solar Data Challenge - Week 0  
**Cross-Country Solar Farm Analysis for Benin, Sierra Leone & Togo**  

[![Python 3.12](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/downloads/)

[![GitHub Actions](https://github.com/Turemo-Bedho/solar-data-challenge-week0/actions/workflows/ci.yml/badge.svg)](https://github.com/Turemo-Bedho/solar-data-challenge-week0/actions)

[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)


## 📋 Project Overview
This repository contains the complete solution for 10 Academy's Week 0 challenge, performing comparative analysis of solar irradiance data across three West African countries. Key deliverables include:
- Automated data cleaning pipelines
- Country-specific EDA notebooks
- Statistical comparison framework
- Visualization

## 🛠️ Environment Setup

### Prerequisites
- Python 3.12+
- Git
- Jupyter Notebook (optional)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Turemo-Bedho/solar-data-challenge-week0.git
   cd solar-data-challenge-week0
   ```

2. **Create and activate virtual environment**:
   ```bash
   python -m venv .solarvenv
   # Windows:
   .\.solarvenv\Scripts\activate
   # macOS/Linux:
   source .solarvenv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 📂 Repository Structure
```
solar-data-challenge-week0/
├── data/                   # Raw and cleaned datasets (gitignored)
├── notebooks/
│   ├── benin_eda.ipynb     # Complete Benin analysis
│   ├── sierraleone_eda.ipynb
│   └── togo_eda.ipynb
├── src/                    # Python modules
├── .github/workflows/      # CI/CD pipelines
│   └── ci.yml              
├── requirements.txt        # Dependency list
└── README.md               # This document
```

## 🚀 Usage

### Running Analysis
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open any country notebook (e.g., `notebooks/benin_eda.ipynb`)
3. Execute cells sequentially

## 🤝 Contributing
1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
2. Commit changes:
   ```bash
   git commit -m "feat: add new visualization"
   ```
3. Push and create a Pull Request

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



