# converting-float-to-integer of a column in python
# converting 'Weight' from float to int 

df['Weight'] = df['Weight'].astype(int) 

# checking type of column

df1.dtypes



df['FRS_Id'] = df['FRS_Id'].apply(np.int64)   # updated version to avoid error
