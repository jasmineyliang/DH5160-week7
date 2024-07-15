## Quiz: Basic Data Manipulation and Visualization with ggplot2

### Question 1: Create a Data Frame
**Q:** Create a data frame named `patients` with the following columns:
- `id` (1 to 5)
- `age` (22, 25, 30, 35, 40)
- `gender` ("F", "M", "F", "M", "F")
- `weight` (55, 78, 67, 80, 72)

```r
# Your code here
```

### Question 2: Subset Data
**Q:** Subset the `patients` data frame to include only females.

```r
patients <- data.frame(id = 1:5, age = c(22, 25, 30, 35, 40), gender = c("F", "M", "F", "M", "F"), weight = c(55, 78, 67, 80, 72))
# Your code here
```

### Question 3: Calculate Mean Weight
**Q:** Calculate the mean weight of the patients.

```r
# Your code here
```

### Question 4: Basic ggplot
**Q:** Create a basic scatter plot of `age` vs `weight` using ggplot2.

```r
library(ggplot2)
# Your code here
```

### Question 5: ggplot with Color
**Q:** Create a scatter plot of `age` vs `weight` with points colored by `gender`.

```r
library(ggplot2)
# Your code here
```
