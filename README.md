# Machine Learning with Python

### Task
Build a machine learning model that would predict the political party to which a taxpayer belongs to.

The dataset contains information about US taxpayers. There are 10 independent columns and 1 dependent column. This dataset includes attributes like household income, household debt level, if the taxpayer is married or not, how many cars their household has, if they filed their taxes in the last three years or not. 

### Data Description
HHI: Household income
HHDL: Household debt level
Married: There are three categories for a taxpayer 0, 1, 2 with regards to marriage.
PoliticalParty: Name of the political party
CollegeGrads: Grade in College out of 5
AHHAge: Average household age
cars: number of cars in house
Filed in YYYY: Tax filed in given year YYYY

### Data Sets used
Training: 
tax_data  = pd.read_csv("https://raw.githubusercontent.com/dphi-official/Datasets/master/tax_payers/train_set_label.csv" )

Testing:
test_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/tax_payers/test_set_label.csv')

