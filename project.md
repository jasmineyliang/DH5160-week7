## Mini-Project: Health Data Analysis with ggplot2

### Goal:
Write a script in R to analyze a health data set using data manipulation techniques and visualize the results using ggplot2. The data set contains information on patients' health metrics.

### Data:
Suppose you have the following data:

```r
patient_id <- 1:15
age <- c(25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95)
gender <- c("F", "M", "M", "F", "F", "M", "M", "F", "F", "M", "F", "M", "F", "M", "F")
height_cm <- c(160, 175, 180, 158, 162, 178, 182, 157, 165, 170, 159, 180, 163, 175, 168)
weight_kg <- c(55, 70, 80, 50, 60, 85, 90, 45, 58, 75, 50, 80, 56, 78, 63)
cholesterol <- c(200, 180, 220, 190, 210, 230, 240, 185, 195, 225, 200, 220, 215, 210, 200)
```

### Tasks
1. **Create the Data Frame:**
   - Create a data frame named `health_data` that contains the above columns.

2. **Inspect the Data:**
   - Display the first few rows and the structure of the data frame.

3. **Calculate BMI:**
   - Add a new column to the data frame named `bmi` calculated as `weight_kg / (height_cm/100)^2`.

4. **Summary Statistics:**
   - Calculate summary statistics (mean, median, and standard deviation) for `age`, `bmi`, and `cholesterol`.

5. **Visualize Data:**
   - Create a scatter plot of `age` vs `bmi` with points colored by `gender`.
   - Create a histogram of `cholesterol`.
   - Create a box plot of `bmi` grouped by `gender`.

6. **Save the Cleaned Data:**
   - Save the cleaned data to a new CSV file named `cleaned_health_data.csv`.
