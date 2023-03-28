# Algorithmic Trading Bot
Goal: To create an algorithmic trading bot that learns and adapts to new markets. Existing trading signals are fed into machine learning algorithms that can adapt to new data.  

---

## Technologies

This program uses the following programs:  
Pandas version 1.5.2    
NumPy version 1.21.5    
hvPlot version 0.8.2    
Matplotlib version 3.5.3     
scikit-learn version 1.1.3    
Python version 3.9.15     

---

## Installation Guide

To check your current Python version, run the following code in your terminal:  
python --version  

To check if the aforementioned packages are installed on your local machine, use the following code:   
pip show pandas  
pip show numpy  
pip show hvplot  
pip show matplotlib  
conda list scikit-learn

If installation og these packages is required, run the collowing code:  
pip install pandas  
pip install numpy  
pip install hvplot  
conda install matplotlib 
pip install -U scikit-learn

---

## Usage

Important: This program is intended purely for academic purposes, and is solely an example of what is possible. This repository, program, and relevant files are not intended to provide actual investment advice.  

To begin using this program, please download the following files (included in the repository's 'Resources' folder) to your local machine:   
emerging_markets_ohlcv.csv    

Initialize the imports and follow along for calculations and analsysis. 

---

## Report Summaries

The Baseline Algorithm is per the standard code unaltered. The Date Offset Adjusted Algorithm changes the 'DateOffset' parameter to 6 (from 3 originally). The Window Adjusted Algorithm reverts the 'DateOffset' and changes the SMA Short Window to 7 and the SMA Long Window to 50. 
 
Baseline Algorithm Performance:   
<img src="Resources/baseline strategy performance.png">

Baseline Algorithm Report:  
<img src="Resources/baseline strategy report.png">
 
Date Offset Adjusted Algorithm Performance:  
<img src="Resources/tuned date offset performance.png">
Date Offset Adjusted Algorithm Report:  
<img src="Resources/tuned date offset report.png">
  
Window Adjusted Algorithm Performance:  
<img src="Resources/tuned window performance.png">
Window Adjusted Algorithm Report:  
<img src="Resources/tuned window report.png">

---


## Contributors 

Shahrukh Alam

---

## License

Columbia Engineering: FinTech Bootcamp
