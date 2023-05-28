## Employee BURN RATE Prediction

The dataset contains Employee information 

Dataset Source: Hackerearth

Independent Variables :
- 'Employee ID', 
- 'Date of Joining', 
- 'Gender', 
- 'Company Type',
- 'WFH Setup Available', 
- 'Designation', 
- 'Resource Allocation',
- 'Mental Fatigue Score', 
    

Dependent Variable :
- 'Burn Rate'

Event is continous varible - Rate i.e. 0 to 1 Value

Created Features :
- 'Vintage' : [Last Date - Date of Joining]


### Problem Type :
    Status Prediction Model

### ML algorithm used :
    Linear Regrssion Model


#### Categorical Varible

cat_var = ['Gender', 'Company Type', 'WFH Setup Available', 'Designation', 
           'Resource Allocation']

#### Continous Varible

df_cont_var = df1[['Designation','Resource Allocation','Mental Fatigue Score','Burn Rate']]


### FINAL EQUATION

Equation:   
-                y = 
-                [-0.08623414] + 
-                [0.0047] * Gender_dum + 
-                [-0.0111] * WFH_Setup_Available_dum + 
-                [-0.0045] * Designation + 
-                [0.0284] * Resource Allocation + 
-                [0.07409] * Mental Fatigue Score
