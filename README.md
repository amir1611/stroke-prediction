# **Fuzzy Stroke Risk Assesment**

This project aims to create a fuzzy inference system that assesses the risk of stroke based on demographic information and health indicators.

## <br>Table of Contents<br/>
<br>•Pre-processing<br/>
<br>•Selection of Attributes<br/>
<br>•Fuzzy Antecedents and Consequent<br/>
<br>•Fuzzy Rules<br/>

<br>Pre-processing<br/>
The dataset healthcare-dataset-stroke-data.csv is pre-processed by removing rows with missing values and converting categorical input from string to int.

<br>Selection of Attributes<br/>
Unwanted attributes/columns are removed. The remaining attributes are gender, age, average glucose level, BMI, and stroke.

<br>Fuzzy Antecedents and Consequent<br/>
The antecedent variables are defined for gender, age, average glucose level, and BMI. The consequent variable is defined for stroke. Membership functions are defined for each antecedent and consequent variable.

<br>Fuzzy Rules<br/>
Fuzzy rules are defined using the antecedents and consequents.

<br>Dependencies<br/>
•Matplotlib
•NumPy
•Pandas
•scikit-fuzzy


<br>Output<br/>
The output of the system is a visual representation of the membership functions for each antecedent and consequent variable. The output is saved as a jpeg file named output.jpg.

# License
Feel Free to Fork Or Clone this repository by adhering to MIT License. 
