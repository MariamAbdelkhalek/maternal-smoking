# Maternal Smoking and Birth Weight

![Maternal Smoking](images/smoking.jpeg)

Maternal smoking has been shown to have harmful effects on the newborn, including reduced birth weight. This [dataset](smoking.tsv) is a subset of a much larger study by the Child Health and Development Study (CHDS) that was conducted over several years.

The columns included in the subset described in the table below:

| Column | Description |
| -- | -- |
| `id` | id number |
| `date` | birth date |
| `gestation` | gestation days |
| `weight` | birth weight in ounce (999 unknown) |
| `parity` | 0=first born |
| `mom.race` | mom race |
| `mom.age` | mom age in years |
| `mom.edu` | mom eduction 0=(<8), 1=(8-<12), 2=12, 3=12+trade, 4=12+some college, 5=16, 6, 7 trade (hs unclear), 9 = unknown |
| `mom.height` | mom height in inches |
| `mom.weight` | mom prepreganncy weight in pounds |
| `dad.race` | dad race |
| `dad.age` | dad age |
| `dad.edu` | dad eduction |
| `dad.height` | dad height |
| `dad.weight` | dad weight |
| `marital` | 1=married, 2=seperated, 3=divorced, 4=widowed, 5=never married |
| `income` | total income in 2500 increements 0=under 2500, 1=2500-4999, ...., 9=15000+, 98=unknown, 99=not asked |
| `smoke` | mom smoking
| `quit.time` | how long ago quit 0=never, 1=still, 2=during preggancy, 3=1 year, 4=2 years, 5=3 years, 6=4 years, 7=5-9 years, 8=10+ years, 9=quit and don't know when, 98=unknown |
| `cigs` | number of cigs smoked a day for past and current smokers 0=never, 1=1-4, 2=5-9, 3=10-14, 4=15-19, 5=20-29, 6=30-39, 7=40-60, 8=60+, 9=smoke but don't know, 98=unknown |

Given the [dataset](smoking.tsv), address the following questions visually and numerically, if possible, and state your conclusion:

- **Q1.** Does the mom's smoking pattern affect the newborn birth weight?
- **Q2.** Does the mom’s race affect the newborn birth weight?
- **Q3.** Is there a correlation between the mom’s weight and the baby’s weight?
- **Q4.** Is there a correlation between the dad’s weight and the baby’s weight?
- **Q5.** From Q3 and Q4, which is a stronger correlation?
- **Q6.** Is there a correlation between the mom’s weight and the dad’s weight?
- **Q7.** On average, does the mom’s weight change across the races?
- **Q8.** Does mom’s smoking pattern change with the mom’s education?
- **Q9.** Does mom’s smoking pattern change with the family income?
- **Q10.** Is there a relationship between the mom’s race and the dad’s race?
- **Q11.** Among the different variables included in the dataset, which variable is the newborn birth weight most statistically significantly associated?
- **Q12.** Among the different variables included in the dataset, which variable has the most considerable effect on the newborn birth weight?
- **Q13.** Do the different variables provide grouping/clustering of the newborns according to the mom’s smoking pattern? If so, which variables are the most important?

You can start by copying [this notebook](smoking.ipynb) into Google Colaboratory. Make sure to name your notebook with your name (first and last).

**Hint**
- In the shared notebook, mom's smoking pattern (`smoke`) is converted to a factor. You might need to convert other categorical variables as you see fit.
- In **Q11**, **Q12**, and **Q13**, not all columns need to be included in the analysis, e.g., `id`.

Good luck 🌟

## Resources
Here are some cheat sheets that might be handy:
- [Data Transformation](resources/data-transformation.pdf)
- [Data Visualization](resources/data-visualization.pdf)
- [Visual Vocabulary](resources/visual-vocabulary.pdf)
- [R Tutorial](http://www.r-tutor.com/r-introduction)
