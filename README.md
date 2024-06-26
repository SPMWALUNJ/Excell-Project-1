# Excell-Project-1
ASSIGNMENT -1
Step 1: Calculate the average premium

1. Open the Excel file containing the insurance premiums.
2. Select the premium column .
3. Go to an empty cell 
4. Type: =AVERAGE() select whole column ctr+shift+downarrow
5. Press Enter to calculate the average premium.

Step 2: Highlight customers paying more than the average premium

1. Select the entire premium column (e.g., Column G).
2. Go to the "Home" tab in the Excel ribbon.
3. Click on "Conditional Formatting" in the "Top Bottom Rules" group.
4. Select Above Average.
5. Click on the "Format" button and select a highlight color.
6. Click "OK" to apply the formatting rule.



ASSIGNMENT -2


- Column H: Number of Technicians
- Column N: Labour Hours
- Column O: Parts Cost
- Column J: Hourly Cost (to be inserted)
- Column M: Total Cost of Service (to be calculated)
- Column K: Hourly Cost*Labour Hour
- Column l: Total Labour Cost: K2*H2
Steps:

1. Insert a new column J for Hourly Cost:
    - USE FORMULA I2/H2 Hourly Labour Cost
    - Drag the formula down to fill the rest of the cells in column j
2. Calculate the Total Labour Cost:
    - In a new column (e.g., K), enter the formula: =N2*J ( labour hours x hourly cost)
    - Drag the formula down to fill the rest of the cells in column F
3. Calculate the Total Cost of Service:
    - In column M, enter the formula: =l2+o2 (total labour cost + parts cost)
    - Drag the formula down to fill the rest of the cells in column E
