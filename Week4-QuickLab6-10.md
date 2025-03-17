# Quick 10 Labs for ERP: Lab 6 to Lab 10

## Lab 6: Introduction to pandas
````
# Lab 6: Introduction to pandas
# Add a new column for transaction type (i.e., "Debit/Credit")

import pandas as pd
ledger = {'Account': ['Cash', 'Revenue'], 'Amount': [1000, 2000]}
df = pd.DataFrame(ledger)
print(df)


# Creating the original DataFrame
ledger = {
    "Account": ["Cash", "Revenue"],
    "Amount": [1000, 2000]
}

# Re-importing necessary libraries after execution state reset
import pandas as pd

# Creating the original DataFrame
ledger = {
    "Account": ["Cash", "Revenue"],
    "Amount": [1000, 2000]
}

df = pd.DataFrame(ledger)

# Adding a new column for transaction type
df["Transaction Type"] = ["Debit", "Credit"]  # Assuming Cash is Debit and Revenue is Credit

print('*** Add a new column for transaction type (i.e., "Debit/Credit") ***')
print(df)

-- Output Result:

   Account  Amount
0     Cash    1000
1  Revenue    2000
*** Add a new column for transaction type (i.e., "Debit/Credit") ***
   Account  Amount Transaction Type
0     Cash    1000            Debit
1  Revenue    2000           Credit

````


## Lab 7: Reading and Writing CSV Files

![image](https://github.com/user-attachments/assets/753d5562-7a54-4031-a2f9-95986cad01c4)

## Lab 8: Data Cleaning with pandas

![image](https://github.com/user-attachments/assets/ec5e7097-6313-40a2-b7fd-f4e3a6d93700)

## Lab 9: Data Aggregation

![image](https://github.com/user-attachments/assets/97ebdfbb-ddf2-49ea-89e2-8a726a8639c8)

## Lab 10: Visualizing Data with matplotlib

![image](https://github.com/user-attachments/assets/5c7607f7-fa92-46a2-a6d1-045648b7d3be)


