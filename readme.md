Task for this project is to write a report addressing the following problem:

Is there a significant difference in income between men and women? Does the difference vary depending on other factors (e.g., education, profession, criminal history, marriage status, etc.)?

To address this problem you will use the NLSY97 (National Longitudinal Survey of Youth, 1997 cohort) data set. The NLSY97 data set contains survey responses on thousands of individuals who have been surveyed every one or two years starting in 1997.
Base data set: To get you started, I’ve pulled together over 60 variables from the broader data set. This base data set is posted on Moodle, along with accompanying info files that tell you about the variables.

A natural outcome variable for the data is the one coded as T75456.00 [YINC-1700], which gives the TOTAL INCOME FROM WAGES AND SALARY IN PAST YEAR (2011 survey question). Note that this quantity is topcoded, meaning that you do not get to see the actual incomes for the top 2% of earners. For the top 2% of earners, the income variable is set to the average income among the 2% of earners. The implication of this topcoding is something you’ll want to discuss as part of your analysis.

Project requirements

Your end-product for the project will be an R Markdown report that contains at least the following sections.

1. Data summary (10 points)

You should begin by describing the data you have available. You will want to display tabular summaries of means and proportions where appropriate. Since the main question is one of gender differences, you may want your tabular summaries to also break things down by gender.

Your score for this section will be based on the following criteria:

•Meaningful variable names, factor variables, and factor level names
•Insightful graphical and tabular summaries of the data
•Proper labelling of figure axes and table columns
•Discussion of the graphical and tabular summaries.

Note: Figures and tables that are presented without accompanying description/discussion will receive at most half credit. To earn full credit, you must describe what each table/figure is showing and discuss any key takeaways. In other words, it is not sufficient to simply display R output. You must also provide thoughtful discussion of the output. Make sure that your discussion could easily be understood by a first year college student trying to learn more about income inequality between men and women.

2. Methodology (10 points)

In this section you should provide an overview of the approach you took to exploring and analyzing the data. This is where you tell the story of how you got to your main findings. It’s too tedious to carefully format plots and tables for every approach you tried, so you can also use this section as a place to explain the various types of analyses that you tried.

You should address at least the following questions:

•How did you deal with missing values? What impact does your approach have on the interpretation or generalizability of the resulting analysis?
•How did you deal with topcoded variables? What impact does your approach have on the interpretation or generalizability of the resulting analysis?
•Did you produce any tables or plots that you thought would reveal interesting trends but didn’t?
•What relationships did you investigate that don’t appear in your findings section?
•What’s the analysis that you finally settled on? What income and gender related factors do you investigate in the final analysis?

Note: Figures and tables that are presented without accompanying description/discussion will receive at most half credit. To earn full credit, you must describe what each table/figure is showing and discuss any key takeaways. In other words, it is not sufficient to simply display R output. You must also provide thoughtful discussion of the output. Make sure that your discussion could easily be understood by a first year college student trying to learn more about income inequality between men and women.

3. Findings (15 points)

In this section you give a careful presentation of your main findings concerning the main problem of income (in)equality between men and women. You should provide, where appropriate:

•Tabular summaries (with carefully labelled column headers)
•Graphical summaries (with carefully labelled axes, titles, and legends)
•Regression output + interpretation of output + interpretation of coefficients
•Assessments of statistical significance (output of tests, models, and corresponding p-values)

As part of your analysis you must run a regression model. When running regressions, you should discuss whether the standard diagnostic plots indicate issues with the model (trends in residuals, variance issues, outliers, etc.). You will not receive full credit for your regression unless you clearly display and discuss the diagnostic plots.

Note: Figures and tables that are presented without accompanying description/discussion will receive at most half credit. To earn full credit, you must describe what each table/figure is showing and discuss any key takeaways. In other words, it is not sufficient to simply display R output. You must also provide thoughtful discussion of the output. Make sure that your discussion could easily be understood by a first year college student trying to learn more about income inequality between men and women.

4. Discussion (5 points)

In this section you should summarize your main conclusions. You should also discuss potential limitations of your analysis and findings. Are there potential confounders that you didn’t control for? Are the models you fit believable?
You should also address the following question: How much confidence do you have in your analysis? Do you believe your conclusions? Are you confident enough in your analysis and findings to present them to policy makers? (You will not be deducted points for saying that you are unsure of your analysis. This is just something I want you to reflect upon.)
