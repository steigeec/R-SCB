# R-SCB

2 hour workshop for UC Berkeley Society for Conservation Biology

## Installations

#### Download R and RSTudio

Before the workshop be sure to download these three items:

1. [Click here to download R version 3.6.1](https://cloud.r-project.org/)  

2. [Click here to download RStudio Desktop Open Source License Free](https://rstudio.com/products/rstudio/download/)  

3. [Click here to download workshop materials](https://github.com/EastBayEv/R-SCB)

- Git users can simply clone this repository

- Otherwise, click the green "Clone or download" button, click "Download ZIP", then extract the contents of this file someplace familiar such as your Desktop. 

#### Package installation

Be sure to run lines 7 through 21 in the file "1-package-installation.Rmd" to install the packages to be used in this workshop. 

## Topics

1. Navigating RStudio
- Top left window pane = input (script or markdown); enter your code here - it is easy to save :^)  
- Bottom right = output (console); noodle around down here - this is difficult to save :^(  
- Upper right = global environment (saved variables/data live here)  
- Bottom right = File structure, plots, package installation, help  

2. Variable assignment

- How to save data in R's memory. Variables are simply placeholders for variables and data! 

3. The data

- [Aquastat datasets for Mexico, USA, and Canada](http://www.fao.org/nr/water/aquastat/data/query/index.html?lang=en)  

- [GBIF ](https://www.gbif.org/occurrence/download?dataset_key=8a863029-f435-446a-821e-275f4f641165) (Observation.org, Nature data from the Netherlands simple occurrences; login required)
- gbif data user agreement: https://www.gbif.org/terms/data-user  
- gbif citation guidelines: https://www.gbif.org/citation-guidelines  
- citation: GBIF.org (23 October 2019) GBIF Occurrence Download   https://doi.org/10.15468/dl.jgjalb

4. Data types

- Numeric, integer, character, logical, factor

5. Data structures

- Emphasis on vectors and data frames

6. Data visualization with ggplot2
- Histograms  
- Boxplots  
- Scatterplots  
  - Facetting
  - Subplotting
- PCA example
- Clustering example

7. Maps
- ggplot2  
- ggmap
  - How to enable Google Maps Static API key (bring credit card - do not worry you will not be charged!)
- simple features (going further)

## Web resources

#### Basic statistics

Kerns GJ. 2010. [Introduction to Probability and Statistics Using R](http://www.atmos.albany.edu/facstaff/timm/ATM315spring14/R/IPSUR.pdf)  

Everitt BS and T Hothorn. 2005. [Handbook of Statistical Analyses Using R](https://cran.r-project.org/web/packages/HSAUR/vignettes/Ch_introduction_to_R.pdf)  

#### Machine learning

James G, D Witten, T Hastie, R Tibshirani. 2000. An Introduction to Statistical Learning - with Applications in R. [Amazon](https://www.amazon.com/Introduction-Statistical-Learning-Applications-Statistics/dp/1461471370). [Free PDF](http://faculty.marshall.usc.edu/gareth-james/ISL/ISLR%20Seventh%20Printing.pdf)  

Chollet F, JJ Allaire. 2018. [Deep Learning with R](https://www.amazon.com/Deep-Learning-R-Francois-Chollet/dp/161729554X)  

#### Community ecology 

Lai J, CJ Lortie, RA Muenchen, J Yang, K Ma. 2019. [Evaluating the popularity of R in ecology](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1002/ecs2.2567)  

Kindt R, R Coe. 2005. [Tree diversity analysis: A manual and software for common statistical methods for ecological and biodiversity studies](http://old.worldagroforestry.org/downloads/Publications/PDFS/b13695.pdf)  

Rózsa L, J Reiczigel, G Majoros. 2000. [Quantifying parasites in samples of hosts](http://zoologia.hu/list/quant_large.pdf)  

Bush AO, Lafferty KD, Lotz JM, Shostak AW. 1997. [Parasitology meets ecology on its own terms: Margolis et al. revisited](https://www.ncbi.nlm.nih.gov/pubmed/9267395) (broken link)  

Komonen A, M Elo. 2017. [Ecological response hides behind the species abundance distribution: Community response to low‐intensity disturbance in managed grasslands](https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.3395)  

Mensh B, K Kording. 2017. [Ten simple rules for structuring papers](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619)  

#### R resources

Oksanen J. 2019. [Vegan: an introduction to ordination](https://cran.r-project.org/web/packages/vegan/vignettes/intro-vegan.pdf)  

[Vegan functions](http://cc.oulu.fi/~jarioksa/softhelp/vegan/html/)  

Zelený D. 2019. [Analysis of community ecology data in R](https://www.davidzeleny.net/anadat-r/doku.php/en:start)  

Bates D, M Mächler, BM Bolker, SC Walker. 2015. [Fitting Linear Mixed-Effects Models Using lme4](https://cran.r-project.org/web/packages/lme4/vignettes/lmer.pdf)  

Paradis E and K Schliep. 2019. [ape homepage](http://ape-package.ird.fr/)  

Paradis E. 2019. [Moran's Autocorrelation Coefficient in Comparative Methods](https://cran.r-project.org/web/packages/ape/vignettes/MoranI.pdf)  

[Oklahoma State University - Ordination Methods for Ecologists](http://ordination.okstate.edu/)  

BIOL 540 [Montana State University R Labs for Community Ecologists](http://ecology.msu.montana.edu/labdsv/R/)  

## D-Lab workshops

[D-Lab workshops can be found on our calendar](https://dlab.berkeley.edu/calendar-node-field-date)  

- [R-Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals)  
- [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang)  
- [R Graphics](https://github.com/dlab-berkeley/R-graphics)  
- [Geospatial Fundamentals in R with sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)  
- [Introduction to Machine Learning in R](https://github.com/dlab-berkeley/Machine-Learning-in-R)  
- [Introduction to Deep Learning in R](https://github.com/dlab-berkeley/Deep-Learning-in-R)  

## D-Lab consulting services

D-Lab offers FREE one-to-one coaching sessions for your individual research projects. [Click here to learn more](https://dlab.berkeley.edu/consulting). 
