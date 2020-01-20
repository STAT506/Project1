# Project1

## Project Overview

The first course project will use a dataset from the dating site Ok Cupid. Data is available in R in the `okcupiddata` package. Additional information, including a data dictionary is available in the package documentation.

```{r}
#install.packages('okcupiddata')
library(okcupiddata)
data(profiles)
```


The profiles dataset is messier than most traditional academic datasets, but is similar to “real” datasets. You are free to propose your own research question; however, you should explore the difference of a continuous response across at least two grouping variables. Make sure you discuss “size” of impacts in as much detail as possible in your model of interest. Also make sure to include some useful visualizations of the responses versus variables. You should interpret/explain model coefficients of interest as well as clearly reporting your evidence. 

The report should contain sections such as introduction, methods, and results.This should be around 5 pages of double-spaced text with figures and tables following the text or around 10 pages with double-spaced text and tables and figures integrated within the document. Any analyses performed should be included as an appendix to this analysis with both code and output displayed. 

The following is a preliminary rubric that will be used to assess the report. Note this is the 

* Report generalities:

    - Paragraphs, section labels

    - Length, Double spaced

    - Appendix with code, output, figures
    
    - Figures (reporting and labeling)

    - Spelling, grammar, writing clarity
    
    - Citations for papers, statistical resources, and packages used

* Introduction

    - Sample size(s)

    - Variables with units and descriptive statistics (both for response and predictors)

    - Data source and study design

    - Research question

* Methods (Statistical Procedures)

    - Data visualization 
    
    - Model(s) to fit and why

    - Discuss/assess assumptions

* Results

    - Concise complete report of final estimated model

    - Interactions? plot(s) and discussion
    
    - Summarize patterns/"size" of estimates from final model
    
    - Scope of Inference: how were missing data treated? how can the results be generalized?




