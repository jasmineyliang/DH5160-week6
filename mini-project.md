``` r
patient_id <- c(1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 3)
name <- c("Alice", "Bob", "Charlie", "David", "Eva", "Frank", "Grace", "Hannah", "Ivy", "Jack", "Charlie")
age <- c(25, 30, 35, NA, 28, 32, 29, 24, 31, 27, 35)
gender <- c("F", "M", "M", "M", NA, "M", "F", "F", "F", "M", "M")
height_cm <- c(165, 170, 175, 180, 168, 172, NA, 158, 160, 177, 175)
weight_kg <- c(68, 75, 80, 85, 70, 78, 72, 65, NA, 82, 80)
bmi <- c(24.98, 25.95, 26.12, NA, 24.8, 26.37, 25.55, 26.04, 25.0, 26.18, 26.12)
bp_systolic <- c(120, 130, 125, 135, 128, 124, 126, NA, 122, 130, 125)
bp_diastolic <- c(80, 85, 82, 88, 84, 83, 81, 79, NA, 86, 82)
cholesterol <- c(190, 195, 180, 200, NA, 188, 185, 175, 180, 200, 180)

```


### Tasks
1. **Create the Data Frame:**
   - Create a data frame named `health_data` that contains the above columns.

2. **Inspect the Data:**
   - Display the first few rows and the structure of the data.

3. **Handle Missing Values:**
   - Identify missing values in the data.
   - Replace missing values in the `age`, `height_cm`, `weight_kg`, `bmi`, `bp_systolic`, `bp_diastolic`, and `cholesterol` columns with the mean or median of the respective columns.
   - Handle missing values in the `gender` column by filling in the mode or a default value (e.g., 'Unknown').

4. **Correct Data Types:**
   - Ensure that `age`, `height_cm`, `weight_kg`, `bmi`, `bp_systolic`, `bp_diastolic`, and `cholesterol` are numeric.
   - Ensure that `gender` is a factor.

5. **Remove Duplicates:**
   - Remove any duplicate rows based on the `patient_id` column.

6. **Standardize Column Names:**
   - Convert all column names to lower case.
   - Replace any spaces or special characters with underscores.

7. **Save the Cleaned Data:**
   - Save the cleaned data to a new CSV file named `cleaned_health_data.csv`.
