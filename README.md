# Stellar Classification Capstone Project

## Overview
This is a capstone project for WGU C964 focusing on stellar classification using the SDSS17 dataset. The project implements machine learning algorithms to classify different types of celestial objects based on their spectral characteristics.

## Dataset
The project uses the **Stellar Classification Dataset SDSS17** from Kaggle, which contains spectral data from the Sloan Digital Sky Survey (SDSS). The dataset includes features such as:
- Right Ascension (ra)
- Declination (dec) 
- Ultraviolet filter (u)
- Green filter (g)
- Red filter (r)
- Near infrared filter (i)
- Infrared filter (z)
- Redshift (redshift)
- Plate ID (plate)
- Modified Julian Date (mjd)
- Fiber ID (fiber)

The target variable classifies objects into three categories:
- **STAR**: Stars in our galaxy
- **GALAXY**: Distant galaxies
- **QSO**: Quasi-stellar objects (quasars)

## Project Structure
```
Capstone Project/
├── Capstone.ipynb          # Main Jupyter notebook with analysis
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
├── .gitignore             # Git ignore rules
└── .venv/                 # Virtual environment (not tracked)
```

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- pip package manager
- Git (for version control)

### Installation
1. Clone this repository:
   ```bash
   git clone <your-repository-url>
   cd "Capstone Project"
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. Ensure your virtual environment is activated
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Capstone.ipynb` and run the cells sequentially

## Dataset Access
The project automatically downloads the dataset from Kaggle using the `kagglehub` library. Make sure you have:
- A Kaggle account
- Kaggle API credentials configured (if required)

## Features
- **Data Exploration**: Comprehensive analysis of the SDSS17 dataset
- **Data Preprocessing**: Cleaning and preparation of spectral data
- **Feature Engineering**: Creation of relevant features for classification
- **Model Development**: Implementation of machine learning algorithms
- **Model Evaluation**: Performance metrics and validation techniques
- **Visualization**: Charts and plots for data insights

## Technologies Used
- **Python**: Primary programming language
- **Jupyter Notebook**: Interactive development environment
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms
- **Matplotlib/Seaborn**: Data visualization
- **KaggleHub**: Dataset access and management

## Academic Context
This project is part of the WGU C964 Capstone course requirements. It demonstrates:
- Application of machine learning techniques to real-world astronomical data
- Data science workflow from data acquisition to model deployment
- Technical writing and documentation skills
- Problem-solving in the domain of astrophysics and data science

## Results
*This section will be updated as the project progresses with key findings, model performance metrics, and conclusions.*

## Future Enhancements
- Implementation of deep learning models
- Feature importance analysis
- Cross-validation strategies
- Deployment as a web application
- Integration with additional astronomical datasets

## Contributing
This is an academic project, but feedback and suggestions are welcome. Please open an issue or submit a pull request if you have improvements to suggest.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Western Governors University for the capstone program structure
- Kaggle for hosting the SDSS17 stellar classification dataset
- The Sloan Digital Sky Survey team for the original astronomical data
- The open-source community for the excellent Python libraries used in this project

---
**Note**: This is an educational project completed as part of the WGU C964 Capstone requirements.
**Note**: This read me was AI generated and is not meant to serve as an complete overview or whitepaper of the project, but merely give a brief overview