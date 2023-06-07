# ML-Assignment

**Bayesian Networks**

A Bayesian network is a directed acyclic graph in which each edge corresponds to a conditional
dependency, and each node corresponds to a unique random variable.
Bayesian network consists of two major parts: a directed acyclic graph and a set of conditional
probability distributions
 The directed acyclic graph is a set of random variables represented by nodes.
 The conditional probability distribution of a node (random variable) is defined for every
possible outcome of the preceding causal node(s).
For illustration, consider the following example. Suppose we attempt to turn on our computer,
but the computer does not start (observation/evidence). We would like to know which of the
possible causes of computer failure is more likely. In this simplified illustration, we assume
only two possible causes of this misfortune: electricity failure and computer malfunction.
The corresponding directed acyclic graph is depicted in below figure.

![Screenshot from 2023-06-07 16-17-15](https://github.com/Bhargav6031/ML-Assignment/assets/79755419/21f7359b-b533-4c61-b6e7-89b36d3fc407)

**Data Set**

 Heart Disease Databases
 
The Cleveland database contains 76 attributes, but all published experiments refer to using a
subset of 14 of them. In particular, the Cleveland database is the only one that has been used
by ML researchers to this date. The "Heartdisease" field refers to the presence of heart disease
in the patient. It is integer valued from 0 (no presence) to 4.
Database: 0 1 2 3 4 Total
Cleveland: 164 55 36 35 13 303

Attribute Information:
1. age: age in years
2. sex: sex (1 = male; 0 = female)
3. cp: chest pain type
 Value 1: typical angina
 Value 2: atypical angina
 Value 3: non-anginal pain
 Value 4: asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results
 Value 0: normal
 Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation
or depression of > 0.05 mV)
 Value 2: showing probable or definite left ventricular hypertrophy by Estes'
criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest
11.slope: the slope of the peak exercise ST segment
 Value 1: upsloping
 Value 2: flat
 Value 3: downsloping
12. ca = number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
14.Heartdisease: It is integer valued from 0 (no presence) to 4. Diagnosis of heart disease
(angiographic disease status)

