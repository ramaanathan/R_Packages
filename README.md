##  A Window into the R Packages mentioned at the R New-York Conference 

I attended the R New York Conference https://www.rstats.nyc on May 10 and May 11, 2019. The conference was packed with a number of wonderful presentations. Many of the speakers were kind enough to share the R packages they used in the work they presented. I was familiar with a few of the packages but most were new to me. Here is a short summary of the different R packages that were mentioned by the different speakers in the conference. All the package names are linked to their documentation. The *Use Cases* here correspond to the examples used by the speakers. 

1. **[tidyverse](https://www.tidyverse.org):** Collection of R packages designed for datascience
   * Speaker: Ludmilla Janda, Amplify
   * *Use case: Building Tidyverse from Scratch Using Scratch Box to teach Data Visualization to middle school students. Different blocks are created for each of the tidyverse components. The blocks can be chained together to complete the tasks. Students are able to do data processing and build complex visualizations by interacting only with the blocks.*
2. **[h20](https://cran.r-project.org/web/packages/h2o/h2o.pdf):** Open source machine learning platform for parallelized implementations of supervised and unsupervised algorithms
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
3. **[sparklyr](https://spark.rstudio.com):** R interface to Apache Spark* 
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
4. **[usethis](https://www.tidyverse.org/articles/2018/02/usethis-1-3-0/):** A workflow package for creating R packages
   * Speaker: Emily Robinson, DataCamp
   * *Use Case: Building R packages*
   * Resources: [Git With R](https://happygitwithr.com), [R-Pkgs](https://r-pks.org)
5. **[drake](https://ropenscilabs.github.io/drake-manual/index.html):**  Pipeline toolkit for building reproducible and replicable projects - an alternate to Makefile
   * Resource: [NYC FIRES](https://github.com/aedobbyn/nyc-fires)
   * Speaker: Amanda Dobbyn, Earlybird Software
   * *Use Case: Workflow for analysing when and where fires happen in NYC*
6. **[arrow](https://spark.rstudio.com/guides/arrow/):** R interface to Apache Arrow, a cross-language development platform for in-memory data
   * Resource: [Arrow Apache](https://arrow.apache.org)
   * Speaker: Wes McKinney, Ursa Labs
   * *Use Case: Build compatibility between the different platforms of R, Python, Matlabs, etc *
7. **[rnn](https://www.rdocumentation.org/packages/rnn/versions/0.8.1)**: Recurrent neural network
   * Speaker: Dr. Michelle Gill, Benevolent AI
   * *Use Case: AI driven drug discovery*
8. **[glmnet](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html)**: Fit a generalized linear model via penalized maximum likelihood
   * Speaker: Dr. Adam Chekroud, Spring Health
   * *Use Case: In the process of personaling mental health care, fit a model to measure risk by predicting suicide attempts and suicide deaths following outpatient visits*
9. **[xgboost](https://xgboost.readthedocs.io/en/latest/R-package/xgboostPresentation.html)**: Extreme Gradient Boosting
   * Speaker: Dr. Adam Chekroud, Spring Health
   * *Use Case: In the process of personalizing mental health care, rank most likely reasons why an individual won’t get treatment*
10. **[lme4](https://cran.r-project.org/web/packages/lme4/lme4.pdf), [nlme](https://cran.r-project.org/web/packages/nlme/nlme.pdf)**: Fit linear and non-linear mixed effects models
   * Speaker: Dr. Adam Chekroud, Spring Health
   * *Use Case*: Compare new informed treatment versus psychological treatment for depression and anxiety
11. **[keras](https://keras.rstudio.com)**: High level neural network API using Pythin and tensorflow in the background
   * Speaker: Jacqueline Nolis, Nolis LLC
   * *Use Case: Create a sample neural network to predict new pet names*
12. **[plumber](https://www.rplumber.io)**: A R package that converts your existing R code to a web API using a handful of special one-line comments.
   * Speaker: Heather Nolis, T-Mobile
   * *Use Case: Put the sample neural network application to predict pet names into production using REST API*
   * Resource: [Detailed Instructions on using plumbr](https://medium.com/tmobile-tech/r-can-api-c184951a24a3)
13. **[rocker](https://hub.docker.com/_/r-base/)**: Use Docker (containers) to deploy an R Plumber API
  * Speaker: Heather Nolix, T-Mobile
  * *Use Case: Use elastic container storage on AWS to set up the dockers (containers) to deploy the neural network application built using plumbr*
  * Resource: [Detailed instructions on setting up docker](https://medium.com/tmobile-tech/using-docker-to-deploy-an-r-plumber-api-863ccf91516d)
14. **[rvest](https://cran.r-project.org/web/packages/rvest/rvest.pdf)**: Scrape data from web html pages
   * Speaker: Namita Nandakumar, Philadelphia Eagles
   * *Use Case: Scrape hockey reference draft data*
15. **[rstanarm](https://mc-stan.org/users/interfaces/rstanarm)**: Bayesian applied regression modeling via Stan
   * Speaker: Namita Nandakumar, Philadelphia Eagles
   * *Use Case: Used baysian statistics and logistic regression to estimate the probability of picking overagers during draft*
   * Resource: [Code and slides on Github](https://github.com/namitanandakumar/Draft-Analysis/tree/master/NYC%20R)
16. **[neuroconductor](https://neuroconductor.org)**: An open source platform in R for rapid testing analyzing neuro images
   * Speaker: Elizabeth Sweeney, Weill Cornell
   * *Use Case: Analyse structural MRI images*
17. **[fslr](https://cran.r-project.org/web/packages/fslr/fslr.pdf)**: Useful open-source scriptable software using wrapper fucntions for neuroimaging analysis.
   * Speaker: Elizabeth Sweeney, Weill Cornell
   * *Use Case: Analyze functional MRI images of the brain*
18. **[brms](https://cran.r-project.org/web/packages/brms/brms.pdf)**: Bayesian regression models using Stan
   * Speaker: Jim Savage, Scmidt Futures
   * *Use Case: Integrate loss function over posterior estimate*
19. **[bart](https://cran.r-project.org/web/packages/bartMachine/vignettes/bartMachine.pdf)**: Machine learning with bayesian additive regression trees
   * Speaker: Jim Savage, Scmidt Futures
   * *Use Case: Machine learning as a bayesian equivalent to xgboost*
20. **[rchie](https://cran.rstudio.com/web/packages/rchie/rchie.pdf)**: A parser for Archie ML. 
   * Speaker: Dr. Naom Ross, ROpenSci & EcoHealth Alliance
   * Resource: [Archie ML](http://archieml.org) - Archie Markup Language is a structured text format optimized for human writability.
   * *Use Case: Write in google doc with a little markup*
21. **[redoc](https://noamross.github.io/redoc/index.html)**: Two-way R Markdown-Microsoft Word workflow. It generates Word documents that can be de-rendered back into R Markdown, retaining edits on the Word document, including tracked changes.
   * Speaker: Dr. Naom Ross, ROpenSci & EcoHealth Alliance
   * *Use Case: Collaboration between datascience and management teams using spearate R workflow and office workflow*
22. **[parsnip](https://www.tidyverse.org/articles/2018/11/parsnip-0-0-1/)**: Tidymodels package that generalizes model interfaces across package - part of caret, has a tidy interface and creates a unified interface to models 
   * Speaker: Dr. Max Khun,, RStudio
   * *Use Case: Build any of the machine learning models*
23. **[tabulizer](https://cran.r-project.org/web/packages/tabulizer/vignettes/tabulizer.html)** - provides R bindings to the Tabula java library, which can be used to computationally extract tables from PDF documents
  * Speaker: Brooke Wason, Senior Data Scientist, ACLU
  * *Use Case: ACLU extracts tables from pdf documents on immigration reports*
24. **[daff](https://cran.r-project.org/web/packages/daff/daff.pdf)**: Identify changes in dataframes over time
  * Speaker: Brooke Wason, Senior Data Scientist, ACLU
  * *Use Case: ACLU tracks changes in data extracted from immigration reports*
25. **[readr](https://readr.tidyverse.org)**: Tidyverse package providing a fast and friendly way to read rectangular data (like csv, tsv, and fwf).
  * Speaker: Brooke Wason, Senior Data Scientist, ACLU
  * *Use Case: Read multiple file types*
26. **[visdat](https://cran.r-project.org/web/packages/visdat/vignettes/using_visdat.html)**: Visual display of observations
with missing data
  * Speaker: Brooke Wason, Senior Data Scientist, ACLU
  * *Use Case: Visualize missing data*
27. **[rtweet](https://rtweet.info/index.html)**: R client for accessing Twitter’s REST and stream APIs
  * Speaker: Amanda Dobbyn, Earlybird Software
  * *Use Case: Gather incidents of fires in NYC from twitter feed*
28. **[ggmap](https://cran.r-project.org/web/packages/ggmap/ggmap.pdf)**: Extension of ggplot2 to visualize spatial data and models on top of static maps from various online sources like Google maps
  * Speaker: Amanda Dobbyn, Earlybird Software
  * *Use Case: Map the locations of the NYC fires*
29. **[survival](https://cran.r-project.org/web/packages/survival/survival.pdf)**: R package for doing survival analysis
   * Speaker: Elizabeth Sweeney
   * *Use Case: Survival analysis of data from clinical trials*
