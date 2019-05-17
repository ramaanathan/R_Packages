##  A Window into the R Packages mentioned at the R New-York Conference 

I attended the R New York Conference https://www.rstats.nyc on May 10 and May 11, 2019, which was packed with a number of wonderful presentations. Many of the speakers were kind enough to share the R packages they used in the work they presented. Some were familiar but many of them were new to me. Here is a short summary of the different R packages. The *Use Cases* here correspond to the examples used by the speakers. 

1.	**[tidyverse](https://www.tidyverse.org):** collection of R packages designed for datascience
   * Speaker: Ludmilla Janda, Amplify
   * *Use case: Building Tidyverse from Scratch Using Scratch Box to teach Data Visualization to middle school students. Different blocks are created for each of the tidyverse components. The blocks can be chained together to complete the tasks. Students are able to do data processing and build complex visualizations by interacting only with the blocks.*
2. **[h20](https://cran.r-project.org/web/packages/h2o/h2o.pdf):** open source machine learning platform for parallelized implementations of supervised and unsupervised algorithms
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
3. **[sparklyr](https://spark.rstudio.com):** R interface to Apache Spark* 
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
4. **[usethis](https://www.tidyverse.org/articles/2018/02/usethis-1-3-0/):** A workflow package for creating R packages
   * Resources: [Git With R](https://happygitwithr.com), [R-Pkgs](https://r-pks.org)
   * Speaker: Emily Robinson, DataCamp
   * *Use Case: Building R packages*
5. **[drake](https://ropenscilabs.github.io/drake-manual/index.html):**  pipeline toolkit for building reproducible and replicable projects
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
12. **[plumber](https://www.rplumber.io)**: An R package that converts your existing R code to a web API using a handful of special one-line comments.
   * Speaker: Heather Nolis, T-Mobile
   * *Use Case: Put the sample neural network application to predict pet names into production using REST API*
   * Resource: [Detailed Instructions on using plumbr](https://medium.com/tmobile-tech/r-can-api-c184951a24a3)
13. **[rocker](https://hub.docker.com/_/r-base/)**: Use Docker (containers) to deploy an R Plumber API
  * Speaker: Heather Nolix, T-Mobile
  * *Use Case: Use elastic container storage on AWS to set up the dockers (containers) to deploy the neural network application built using plumbr*
  * Resource: [Detailed instructions on setting up docker](https://medium.com/tmobile-tech/using-docker-to-deploy-an-r-plumber-api-863ccf91516d)
