##  A Window into the R Packages mentioned at the R New-York Conference 

I attended the R New York Conference https://www.rstats.nyc on May 10 and May 11, 2019. Many of the speakers were kind enough to share the R packages they used in the work they presented. Some were familiar but many of them were new to me. Here is a short summary of the different R packages. The *Use Cases* here correspond to the examples used by the speakers.


1.	**tidyverse:** collection of R packages designed for datascience
   * [Documentation](https://www.tidyverse.org)
   * Speaker: Ludmilla Janda, Amplify
   * *Use case: Building Tidyverse from Scratch Using Scratch Box to teach Data Visualization to middle school students. Different blocks are created for each of the tidyverse components. The blocks can be chained together to complete the tasks. Students are able to do data processing and build complex visualizations by interacting only with the blocks.*
2. **h20:** open source machine learning platform for parallelized implementations of supervised and unsupervised algorithms
   * [Documentation](https://cran.r-project.org/web/packages/h2o/h2o.pdf) 
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
3. **sparklyr:** R interface to Apache Spark*
   * [Documentation](https://spark.rstudio.com) 
   * Speaker: Emily Dodwell, AT&T Labs Research
   * *Use Case: Building recommendation systems for DirectTV using tangled Lasso and Boosted trees*
4. **usethis:** A workflow package for creating R packages
   * [Documentation](https://www.tidyverse.org/articles/2018/02/usethis-1-3-0/) 
   * Resources: [Git With R](https://happygitwithr.com), [R-Pkgs](https://r-pks.org)
   * Speaker: Emily Robinson, DataCamp
   * *Use Case: Building R packages*
5. **drake:**  pipeline toolkit for building reproducible and replicable projects
   * [Documentation](https://ropenscilabs.github.io/drake-manual/index.html)
   * Resource: [NYC FIRES](https://github.com/aedobbyn/nyc-fires)
   * Speaker: Amanda Dobbyn, Earlybird Software
   * *Use Case: Workflow for analysing when and where fires happen in NYC*
6. **arrow:** R interface to Apache Arrow, a cross-language development platform for in-memory data
   * [Documentation](https://spark.rstudio.com/guides/arrow/)
   * Resource: [Arrow Apache](https://arrow.apache.org)
   * Speaker: Wes McKinney, Ursa Labs
   * *Use Case: Build compatibility between the different platforms of R, Python, Matlabs, etc *
7. **rnn**: Recurrent neural network
   * [Documentation](https://www.rdocumentation.org/packages/rnn/versions/0.8.1)
   * Speaker: Dr. Michelle Gill, Benevolent AI
   * *Use Case: AI driven drug discovery*
8. **glmnet**: Fit a generalized linear model via penalized maximum likelihood.
   * [Documentation](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html)
   * Speaker: Dr. Adam Chekroud, Spring Health
   * *Use Case: In the process of personaling mental health care, fit a model to measure risk by predicting suicide attempts and suicide deaths following outpatient visits *
9. **xgboost**: Extreme Gradient Boosting
   * [Documentation] (https://xgboost.readthedocs.io/en/latest/R-package/xgboostPresentation.html)
   * Speaker: Dr. Adam Chekroud, Spring Health
   * *Use Case: In the process of personalizing mental health care, rank most likely reasons why an individual won’t get treatment*
