# assignment-7

## **Package Title**

For this assingment, I have chosen to review the Stable Isotope Bayesian Ellipses in R (SIBER) package, created by Dr. Andrew Jackson and Dr. Andrew Parnell.

## **Location**

You can download this package on the web both via CRAN (https://cran.r-project.org/web/packages/SIBER/index.html) and via Andrew Jackson's Github repository (https://github.com/AndrewLJackson/SIBER).

## **Vignette(s)**

The CRAN repository for the SIBER package offers 11 vignettes demonstrating different features of the R code calculations and their interpretation. Topics covered in these vignettes range from vector statistics on stable isotope biplot centroids to plot customization to differences between comparing community and population isotope biplots.

## **Application(s)**

The SIBER package can be used to calculate the overlap in isotopic niche space (e.g., biplots of carbon-13 and nitrogen-15 signatures) between two or more groups of organisms (such as species, populations, or communities) to determine the trophic similarity/difference between these groups. SIBER biplots have appeared in scientific articles in various areas of biology and ecology since the initial creation of the package in 2011.

## **Review**

The primary purpose of the SIBER package is to compare the trophic state of different groups of organisms (e.g., different populations or species) by generating biplots of carbon and nitrogen stable isotopic signatures and producing Bayesian ellipses to statistically compare the overlap in signatures between those different groups. As a coral ecophysiologist, I use SIBER to quantify the overlap in isotopic signatures between corals and their algal symbionts, interpreting higher percent overlap as a higher exchange of resources (i.e., a higher degree of mutualism) between these two members of coral symbiosis (see Conti-Jerpe et al. 2020: https://www.science.org/doi/10.1126/sciadv.aaz5443). 

I really appreciate how easy it is to use this package for both plotting and statistical analysis of isotopic data. The vignettes provide extensive comments explaining every code line and its interpretation, and the generated isotopic biplots are easy to manipulate using your own code. The SIBER model runs relatively quickly (in my experience, being able to process 4000 Bayesian simulations of sample sets of ~50 per each of 2 groups of data in just a few minutes) and the associated Hotelling’s T2 and centroid data for the ellipses are relatively easy to interpret. Having first learned to use SIBER without much background in R or R Studio, I can attest that the package is easy to learn to use, and that the package creators are available by email to answer any further questions. 

My only warning for using the SIBER package would be to keep up to date with the newest discussions of the limitations and applications of the model itself. Especially in coral-centric fields, SIBER applications are still in their infancy, and many isotopic experts (including those reviewing my manuscripts) often have nuanced interpretations of the results that may not be evident from the previous literature. 
