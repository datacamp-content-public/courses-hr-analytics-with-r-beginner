---
title: 'Dataframes in R'
description: 'Dataframes are the most commonly used R object for storing and analysing our HR data. The rows typically represent individual officers, whilst the columns could be demographics (e.g. Age) or employment details (e.g. Salary). '
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

In every DataCamp exercise, you are writing and running real R code. You won’t just learn the theory, you’ll get hands-on experience exploring real data sets in courses covering the entire data science workflow.

`@instructions`


`@hint`


`@pre_exercise_code`
```{r}
library(readxl)
library(janitor)
hrdf <- read_excel("https://community.watsonanalytics.com/wp-content/uploads/2015/03/WA_Fn-UseC_-HR-Employee-Attrition.xlsx")
hrdf <- clean_names(hrdf)
```

`@sample_code`
```{r}
colnames(hrdf)
```

`@solution`
```{r}

```

`@sct`
```{r}

```
