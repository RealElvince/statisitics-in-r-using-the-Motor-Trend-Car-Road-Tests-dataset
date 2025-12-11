# Motor Trend Car Road Tests (mtcars Dataset)

## Description
The **mtcars** dataset was extracted from the 1974 *Motor Trend* US magazine. It contains fuel consumption data and 10 aspects of automobile design and performance for **32 automobiles** (1973–1974 models).  
It is widely used for regression modeling, machine learning, and exploratory data analysis in R.

---

## Format
A data frame with **32 observations** on **11 numeric variables**:

| Column | Variable | Description |
|--------|----------|-------------|
| 1 | **mpg** | Miles per US gallon |
| 2 | **cyl** | Number of cylinders |
| 3 | **disp** | Displacement (cubic inches) |
| 4 | **hp** | Gross horsepower |
| 5 | **drat** | Rear axle ratio |
| 6 | **wt** | Weight (1000 lbs) |
| 7 | **qsec** | 1/4 mile time |
| 8 | **vs** | Engine type (0 = V-shaped, 1 = straight) |
| 9 | **am** | Transmission (0 = automatic, 1 = manual) |
| 10 | **gear** | Number of forward gears |
| 11 | **carb** | Number of carburetors |

---

## Notes
Henderson and Velleman (1981) reported that Hocking (the original transcriber):

- coded the Mazda’s **rotary engine** as a *straight six-cylinder engine*  
- coded the Porsche’s **flat engine** as a *V engine*  
- included the diesel **Mercedes 240D**

These inconsistencies were intentionally kept so results would remain comparable with previous analyses.

---

## Source
Henderson and Velleman (1981).  
*Building multiple regression models interactively.*  
**Biometrics**, 37, 391–411.

---

## Example in R

```r
# Load and preview the dataset
data(mtcars)
head(mtcars)

# Summary statistics
summary(mtcars)
