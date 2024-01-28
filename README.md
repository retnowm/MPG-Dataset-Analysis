# MPG-Dataset-Analysis
## Data Understanding
- The dataset has 9 columns, with a size of 398 rows
- 7 numeric columns, 2 categorical columns
  
Variables Description :
- MPG: mileage per gallon
- cylinders: number of cylinders
- displacement: piston stroke volume
- horsepower: engine power produced
- weight: the weight of the car
- acceleration: acceleration time from 0 to 60 km
- model_year : year of manufacture
- origin: the origin of the car
- name : car name
## Missing Value
1. There are missing values ​​in the horsepower column.
2. Check for outliers in the horsepower column to determine the next stage
3. There are outlier values ​​in the horsepower column, therefore we will impute medium value rather than mean value
## EDA (Exploratory Data Analysis)
### Correlation
Conclusion :
- Weight, displacement and horsepower have the same correlation results with respect to MPG, that is, the higher the weight, displacement and horsepower, the lower the MPG or the car tends to be less efficient in fuel use, which is reflected in a decrease in the "MPG" value.
- Cars with a high number of cylinders tend to have low fuel efficiency (low MPG), and often cars with a high number of cylinders also have high weight, displacement and horsepower.
- Larger displacement often indicates a larger or more complex engine, which can cause an increase in vehicle weight.
- Engines that have greater Displacement can usually burn more fuel and produce more power, which is reflected in a higher "horsepower" value
### Analysis by Origin
Conclusion :
- The largest number of cars comes from the USA (249) followed by Japan (79) and Europe (70)
- Based on the model year, cars from the USA have a lower MPG value than cars from Japan and Europe
- That cars from the USA tend to have lower fuel efficiency than Japan and Europe. In other words, cars from Japan and Europe have higher average "mpg", indicating better fuel efficiency.
- It can be seen from the comparison of weight and MPG for each origin, the USA has a heavier weight, followed by Europe and finally Japan. This can affect fuel efficiency (mpg), as heavier cars tend to require more energy to move, which can result in lower fuel efficiency.
### Analysis by Car Name
Conclusion :
- The name of the Pontiac Catalina car has the highest displacement, Pontiac Grand Prix is ​​the name of the car with the highest horsepower and Pontiac Safari (SW) is the name of the car that has the highest weight. Of the three categories of variables with the highest value comes from USA origin
- Meanwhile, the one with the highest MPG is the Mazda GLC from Japan and the car from the USA is not included in the top 5 cars with the highest MPG.
