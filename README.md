# Power BI DAX Course Overview

## Description
This repository contains a summary of the Power BI DAX course, including key concepts, topics covered, and practical examples to enhance understanding of Data Analysis Expressions (DAX) for Power BI. It is a comprehensive resource for anyone looking to deepen their knowledge in data modeling, filter context, and advanced DAX functions.

## File Structure
```
📂 PowerBI-DAX-Course
├── 📂 CourseSummary
│   ├── DAX_Navigation_Functions.md
│   ├── Row_Context_and_Filter_Context.md
│   ├── Relationships_and_Bridge_Tables.md
│   ├── Time_Intelligence.md
│   ├── Semi_Additive_Measures.md
├── 📂 Examples
│   ├── Filter_Context_Override.pbix
│   ├── Time_Intelligence_Examples.pbix
│   ├── Bridge_Table_Relationships.pbix
├── 📂 Resources
│   ├── DAX_CheatSheet.pdf
│   ├── Course_Presentation.pdf
├── README.md
```

## Topics Covered

### 1. Introduction to DAX
- Understanding the basics of Data Analysis Expressions (DAX).

### 2. Navigation Functions
- Utilizing navigation functions in DAX to manage data traversal.

### 3. Row Context
- Understanding row context and its significance in calculated columns.

### 4. Conditional Logic
- Applying conditional logic in DAX expressions.
- First pass rule in conditional logic.

### 5. Building Relationships
- Creating relationships between tables.
- Handling many-to-many relationships with a bridge table.

### 6. Related and Related Tables
- Using `RELATED` function in scenarios where relationships do not apply.

### 7. Filter Context
- Understanding filter context.
- Modifying and overriding filter context using `CALCULATE`.
- Removing filters using `REMOVEFILTERS` and `ALL`.

### 8. SWITCH Function
- Applying `SWITCH` function for conditional calculations.

### 9. X Functions
- Iterative functions such as `SUMX`, `AVERAGEX`, etc.

### 10. Calculated Measures
- Difference between calculated measures and calculated columns.
- Why use calculated measures?

### 11. Semi-Additive Measures
- Calculating opening and closing balances.

### 12. Time Intelligence
- Importance of a time table in Power BI.
- Calculating YTD, previous year comparisons, and other time-based metrics.

### 13. Context Transition
- Transitioning between row and filter contexts.

## Example Scenarios
1. **Filter Context Override**: Demonstrates how to override filters using `CALCULATE` and `REMOVEFILTERS`.
2. **Time Intelligence**: Provides examples of year-to-date and previous year comparisons.
3. **Bridge Table Relationships**: Explains resolving many-to-many relationships with a bridge table.

## Courses
This course is an advanced Power BI training, covering:
- DAX Basics
- Advanced DAX Functions
- Data Modeling in Power BI
- Time Intelligence

---

## Resources
- [Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [DAX Reference Guide](https://dax.guide/)
- [Course Presentation](./Resources/Course_Presentation.pdf)
- [DAX Cheat Sheet](./Resources/DAX_CheatSheet.pdf)

---

### Author
[Your Name]  
Data Enthusiast | Power BI Specialist

---

Happy Learning!
