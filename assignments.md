### Problem: Analyzing Student Grades

You have a list of student names and their corresponding grades in a class. Your task is to analyze the grades and provide some basic statistics.

### Data
You are given the following data:

```r
students <- c("Alice", "Bob", "Charlie", "David", "Eva", "Frank", "Grace", "Hannah", "Ivy", "Jack")
grades <- c(85, 92, 78, 90, 88, 76, 95, 89, 84, 91)
```

### Tasks
1. **Create a Data Frame:**
   - Create a data frame named `df` that contains two columns: `students` and `grades`.

2. **Calculate Summary Statistics:**
   - Calculate the mean, median, and standard deviation of the grades.
   - Identify the highest and lowest grades and the corresponding students.

3. **Grade Distribution:**
   - Create a frequency table of grades (grouped into ranges: 70-79, 80-89, 90-100).

4. **Plot Grades:**
   - Create a bar plot of the grades with student names on the x-axis.

5. **Categorize Grades:**
   - Add a new column to the data frame named `grade_category` that categorizes the grades as "A" (90-100), "B" (80-89), "C" (70-79).
