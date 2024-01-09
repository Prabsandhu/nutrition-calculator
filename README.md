# **NUTRITION CALCULATOR**
The nutrition calculator uses MS Excel features and formulas to calculate and visualize your nutritional needs on a user-friendly dashboard. 

- First section of the dashboard allows you to enter your personal information i.e., age, weight, height and gender which is then used to calculate your nutritional needs. Your daily calorie, carbohydrate, fat, protein and fiber needs are auto populated in ‘Your nutritional needs’ section. 
- Next section of the dashboard allows you to search and select food items that you had for each meal of the day. Once you enter the quantity, your nutritional intake is calculated and displayed at the bottom of the dashboard. You can enter up to 25 items per day.
- Calorie Distribution chart shows the % of calories that came from protein, fat, carbohydrates and fiber. 
- Needs vs Intake bar chart visually compares your daily nutritional needs and intake
- The water intake section allows you to check off number of water glasses you have had and shows the % of your total water needs met

## Calculations:
- The index match formula is used to search nutritional content, for example calories (per gram) of the item entered in the dashboard from the ‘reference sheet’. This number is then multiplied with the quantity entered to calculate the total calories received from this item. 
- A combination of SEARCH, ISNUMBER, FILTER and TRANSPOSE formulas is used to make the drop-down list searchable. 
- Other formulas used: CONCAT, IF, SUM, COUNTIF, COUNTA

## Formulas used to calculate nutritional needs:

_Calorie Needs:_ The Harris-Benedict Equation for Basal Energy Expenditure (BEE) is commonly used to figure energy requirements based on sex, height, weight and age. 

W = weight in kilograms H = height in centimeters A = age in years 

Men: BEE = 665 + 13.8(W) + 5.0(H) - 6.8(A)

Women: BEE = 655.1 + 9.6(W) + 1.9(H) - 4.7(A)

_Protein Needs:_ The American Dietetic Association (ADA) recommends daily protein intake for healthy adults as .8-1.0 g of protein/kg body weight. 

_Fat Needs:_ Fat intake should equal 30% of your total daily calories. 
_Carbohydrate Needs:_ The USDA recommends that 45 to 65 percent of your total daily calories come from carbohydrates. 

_Fiber Needs:_ The American Heart Association Eating Plan suggests that total dietary fiber intake should be 25-30gram per day. I have set the fiber needs at 25 grams/day for this project.

