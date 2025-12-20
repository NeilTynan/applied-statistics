# applied-statistics
Repository for the Project of 25-26: 8651 -- APPLIED STATISTICS

This README has been written with [GitHub's documentation on README's](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) in mind.

## About this Project

This repository looks at the problems outlined in the assement instructions for 25-26: 8651 -- APPLIED STATISTICS. As part of the course, we are required to examine four problems related to statistics and to answer the questions associated with them. The problems in question are:
- *Problem 1: Extending the Lady Tasting Tea* - An expanded version of the Lady Tasting Tea test.
- *Problem 2: Normal Distribution* - How differences in the standard deviation impact variance in a large sample size
- *Problem 3: t-Tests* - Determining how/if differences in the means diffence in samples can impact the likelyhood that the null hypothesis will be rejected in a t-test.
- *Problem 4: ANOVA* - Comparing the effectiveness of ANOVA vs multiple indepdent t-test.

The full text of each problem is provided in problems.ipynb. The full problem description is provided at the start of each section, followed by the solution to the problem and its associated questions.

## Use of this Project

This repository may be of some interest to other students engaged in similar coursework around statistics. Feel free to use whatever you like from it (though if another party has been referenced, I would ask that you likewise cite them).

## Getting Started

The workbook is structured in a linear fashion, so reading through it from start to finish is the best approach.

To understand how the workbook has developped to date, please see below a timeline of the work done on the notebook and the material referenced in the course of this work:

- 06/10/2025 - Created ReadMe and Gitignore file. Gitignore file generated using the template at Python gitignore template at https://github.com/github/gitignore/blob/main/Python.gitignore, the Windows gitignore template at https://github.com/github/gitignore/blob/main/Global/Windows.gitignore, the MacOS gitignore template at https://github.com/github/gitignore/blob/main/Global/macOS.gitignore and the Linux gitignore template at https://github.com/github/gitignore/blob/main/Global/Linux.gitignore.
- 10/10 - Created problems.ipynb. Added libraries based off lecture 16-notebook-overview. Other coursework referenced included: Started work on problem 1. 15-lady-tasting-tea-intro, 17-permutations-and-combinations.
- 14/10 - Continued work on problem 1. Coursework referenced included: 18-choose-function, 19-counting-possibilities, 20-hypothesis-testing.
- 15/10 - Finished up analysis of Problem 1. Added in some explanatory text to improve readability. External materials referenced: https://www.geeksforgeeks.org/python/introduction-to-python-tabulate-library/ (how to use tabulate to return tuples as tables), https://www.geeksforgeeks.org/python/formatted-string-literals-f-strings-python/ (f strings in python), https://martintaggart.com/how-to-determine-statistical-significance-using-p-values/ (what is a p-value and how to select it).
- 27/10 - Started work on problem 2. Outlined the problem and focussed on trying to generate the sample data Coursework referenced included:
- 04/11 - Briefly continued work on problem 2. Attempted to complete
- 24/11 - Continued work on problem 2, referencing more external material. Completed work on computing the standard deviation and started the problem analysis. External materials referenced included. https://tidystat.com/how-to-calculate-standard-deviation-in-python-numpy/ (How to plot the standard deviation in Python)
- 26/11 - Finished up analysis of problem 2. Finsihed up the analysis and added in some additional text and formatting to improve readability. External materials referenced.https://www.statology.org/population-vs-sample-standard-deviation/ (Population SD vs Sample SD)
- 27/11 - In order to justify the conclusion to problem 2, went back and added a section where the anaysis was tested with a second histogram.
- 08/12 - Started work on problem 3. Generated the samples data for graphing, in line with the problem description. Course material referenced: https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/t-tests.ipynb (course notebook). External material referenced includes: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html (how to preform an independent t-test).
- 09/12 - Continued work on problem 3, adding in the graph and some more expalantory text.
- 15/12 - Completed the final part of problem 3, explaining the changes in the type 2 error rate. Added in more explanatory text and annotations to problem 3 and also adjusted some of the formating in the notebook to make it more readable. External material referenced included: https://www.simplypsychology.org/type_i_and_type_ii_errors.html (what are type 1 and type 2 errors), https://www.statisticalaid.com/type-i-and-type-ii-errors/ (impact of the effect size on type 2 error rate).
- 17/12 - Started problem 4, creating the samples and running the ANOVA and t-tests. Course material referenced included: 43-multiple-t-tests, 44-anova, https://github.com/ianmcloughlin/applied-statistics/blob/main/materials/anova.ipynb.
- 18/12 - Continued work on problem 4, simplifing some of the code (in part to keep it more coherent and consistent) adding in more notations and explanatory text and adding in an expanded breakdown of the results of the ANOVA and t-tests. External material referenced: https://bobbyhadz.com/blog/how-to-print-bold-text-in-python (how to bold text in Python).
- 19/12 - Finished problem 4, completing the sections discussing the comparison of the results and the reasons why ANOVA tests would be preferred for this type of experiment. Added in a section at the start of the workbook explaining its purpose and how to navigate it. Finished tidying up all the references and updates in the ReadME. External Material referenced included: https://www.geeksforgeeks.org/data-science/difference-between-t-test-and-anova/#key-differences-between-ttest-and-anova (ANOVA vs t-test, strengths and weaknesses). https://medium.com/@stathacks/analysis-of-variance-anova-vs-t-test-differences-uses-and-examples-68147d0eff4a (Differnce between ANOVA and t-tests).

## Getting help

Queries about this repository can be directed directly to my GitHub account (NeilTynan).

## Other References

**General Web References**
Statistics with Python, geeksforgeeks.com - https://www.geeksforgeeks.org/python/statistics-with-python/

**ChatGpt Prompts Referenced**
What is ddof in the context of the standard deviation?
What is the null hypothesis specifically measuring in this test? (in reference to problem 4)

## Author

I am student Atlantic Technological University's Higher Diploma in Data Science.
