# Biosensor Health Monitoring

A comprehensive repository for biosensor-based health monitoring applications in rehabilitation medicine and substance use disorder treatment.

## Project Overview
This repository contains tools, analysis code, and documentation for implementing wearable biosensor technologies in clinical care settings. The project focuses on validating the feasibility and clinical utility of continuous physiological monitoring through two primary applications:

1. Accelerometer-based movement monitoring in stroke rehabilitation
2. Physiological detection of relapse risk in substance use disorders (ReSense project)

Both applications harness the potential of passive, continuous monitoring to reveal behavioral and physiological patterns not captured by traditional clinical assessments.

## Repository Structure

### Stroke Rehabilitation Components
* `accelerometer_analysis.ipynb`: Analysis of movement metrics and correlation with clinical assessments
* `clinical_comparison.md`: Comparison of accelerometer monitoring vs. traditional assessments
* `stroke_case_study.md`: Real-world application in stroke rehabilitation settings

### Substance Use Disorder Components
* `relapse_prediction.ipynb`: Machine learning models for predicting relapse risk from biosensor data
* `biosensor_processing.py`: Scripts for processing raw physiological data
* `usability_analysis.md`: Findings from usability studies across diverse populations

## Key Technologies
* **Movement Monitoring**: Wrist-worn accelerometers tracking affected vs. unaffected limb use
* **Physiological Monitoring**: Empatica E4 wearable biosensors capturing:
  - Electrodermal activity (EDA)
  - Heart rate variability (HRV)
  - Skin temperature
  - Movement data

## Research Methodologies

### Stroke Rehabilitation Study
* Comparison of M2 metrics with traditional FMA/MAL assessments
* Measurement of real-world movement in natural environments
* Integration of cognitive assessment with movement monitoring

### ReSense Substance Use Disorder Study
* 30 adults with confirmed CUD diagnosis
* Six-week continuous biosensor monitoring
* Ecological momentary assessments for self-reported cravings
* Machine learning models to predict relapse risk

## Key Findings

### Stroke Rehabilitation
* M2 provides objective, continuous measurement in natural environments
* Traditional assessments offer insights into movement quality not captured by sensors
* Combined approaches reveal patterns like learned non-use that single methods miss

### Substance Use Disorder (Preliminary)
* Physiological signals can detect stress and craving states
* Individual risk patterns can be identified through continuous monitoring
* Usability varies by demographic factors and requires personalized approaches

## Advantages of Biosensor Monitoring
* Objective, passive measurement that reduces reporting bias
* Continuous, real-time data collection in natural environments
* High temporal resolution enables detection of subtle patterns
* Potential for just-in-time interventions based on personalized risk profiles

## Limitations
* Cannot fully replace traditional clinical assessments
* Requires technical setup and patient compliance
* Challenges in data interpretation and standardization
* Privacy and ethical considerations for continuous monitoring

## Getting Started
1. Clone this repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Explore Jupyter notebooks for detailed analysis examples

## Dependencies
* Python 3.8+
* pandas
* numpy
* scipy
* matplotlib
* seaborn
* scikit-learn

## License
This project is provided under the MIT License.

## Acknowledgments
* Clinical partners who provided assessment data
* Patients who participated in biosensor monitoring studies
* Funding provided by research grants# Biosensor-Health-Monitoring
