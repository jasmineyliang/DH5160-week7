
## Assignment: Data Manipulation and Visualization with ggplot2

### Part 1: Data Preparation
1. **Create a Data Frame:**
   - Create a data frame named `health_data` with the following columns: `patient_id` (1 to 10), `age` (20, 22, 24, 26, 28, 30, 32, 34, 36, 38), `gender` ("M", "F", "F", "M", "M", "F", "M", "F", "M", "F"), `height` (170, 165, 160, 175, 180, 155, 178, 160, 165, 168), `weight` (65, 55, 50, 75, 80, 45, 78, 50, 70, 60).

2. **Inspect the Data:**
   - Display the first few rows and the structure of the data frame.

### Part 2: Data Manipulation
1. **Calculate BMI:**
   - Add a new column to the data frame named `bmi` calculated as `weight / (height/100)^2`.

2. **Subset Data:**
   - Subset the data to include only male patients.

### Part 3: Data Visualization with ggplot2
1. **Scatter Plot:**
   - Create a scatter plot of `age` vs `bmi`.

2. **Box Plot:**
   - Create a box plot of `bmi` grouped by `gender`.
