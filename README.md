## ArtofStatistics
Code for 'The Art of Statistics'

by David Spiegelhalter

![](art-cover.png)

Here is its [Amazon page](https://www.amazon.co.uk/Art-Statistics-Learning-Pelican-Books/dp/0241398630)

This repository contains data and R code for the Figures and Tables in Art of Statistics.  They should all work in RStudio.

* It is not yet complete, and will change and improve, including a blogdown web page. 

* The graphics were originally mainly produced in basic R, but (with much appreciated assistance) these have been mainly revised into ggplot2 - sometimes both versions are provided for comparison.  However I do not pretend to have any particular skill in using R or ggplot, and no doubt many improvements could be made.

* Many packages are used and will need to be installed, for example using  install.packages("ggplot2")

* While the individual files can be downloaded, it is probably easiest to download a zipped repository using the green download button.

Suggestions for improvements to david@statslab.cam.ac.uk

# Errata

* page 86. Line -9. "2,190" should read "2,910"
* pages 191 to 200 - see below
* page 212 Figure 8.3 – the label ‘Head’ on the first lower branch should be 'Tail'
* page 222, line -3, '2014' should be '2013'
* page 225 legend to Figure 8.5, '2014' should be '2013'
* page 232. Figure 9.1b is incorrect - the bars should have heights 0.32, 0.64, 0.04, as described in the footnote.  Figures 9.1e and 9.1f are incorrect, the peak should be centred at 0.2, and 9.1e has an apparent layer of probability smeared over the whole range.  The correct version of Figure 9.1 can be found on the Github repository  
* page 235 Legend to Figure 9.2, line 2, after 'UK', add '(except Wales)'
* page 254 In the legend to Figure 10.1 'solid' should be replaced by 'dashed'  
* page 318 line -6, replace 6.7 by 6.5 (6.5 million uses the rounded numbers in the Table, 6.7 million uses unrounded numbers)
* Page 342, start of the last paragraph,'Ioannadis' is misspelled (having spelt it correctly as 'Ioannidis'at the start of the previous paragraph ) 
* page 375 Headings of Table 13.1.  'O' in 'Others' is printed as a zero rather than an 'O'
* page 416 Note 7 ends with 'p.000', which should be 'p.92'

The bootstrap analysis in Chapter 7 contained some errors which have been corrected in the version on Github, where the analysis is clarified by using only data on men reporting less than 50 partners. Corresponding edits to the text are shown below.

* page 191 line -1. “1,100” should be “1,125”
* page 192 line 1. “796” should be “806”
* page 192 para 2, line 5. “of their responses” should be “for the 760 men who reported up to 50 partners.”
* page 192 para 2, line 6. “796” should be “760”
* page 192 para 2, line -4. “high” should be “low”
* page 192 para 2, line -4. “21.1” should be “8.4”
* page 192 para 2, line -1. “796” should be “760”
* page 193 replace Figure 7.1 by the corrected version on the Github repository  
* page 193 Legend to Figure 7.1: replace  “796” should be “760”
* page 194 Table 7.1. Size: replace “796” should be “760”
* page 194 Table 7.1. Mean number of partners: replace by “8.3, 10.5, 12.2, 11.4”
* page 194 Table 7.1. Median number of partners: replace by “9, 7.5, 8, 7”
* page 194 Table 7.1. Legend: “796” should be “760”
* page 195 line 3, replace “15” by “11.4”
* page 195 para 2, line 5. “796” should be “760”
* page 196 replace Figure 7.2 by the corrected version on the Github repository  
* page 196 Legend to Figure 7.2: replace everything after “40” with  “30 partners occurs twice in the original sample. These data-points were sampled once in the first bootstrap sample, not at all in the second, and twice in the third.”
* page 197 para 1, line 2, replace “18.8” by “10.5”
* page 197 para 1, line 5, replace “14.5” by “8.4”
* page 197 para 1, line -1, replace “14.5, 26.5 and 22.5” by “8.4, 9.7 and 9.8”
* page 198 replace Figure 7.3 by the corrected version on the Github repository  
* page 198 Legend to Figure 7.3: replace  “796” should be “760”
* page 199 para 2, line 3, after “contains” add “the central”
* page 200 Table 7.2. Mean number of partners: replace by “8.3, 10.5, 12.2, 11.4”
* page 200 Table 7.2. 95% bootstrap intervals: replace by “5.3 to 11.5, 7.7 to 13.8, 10.5 to 13.8,  10.5 to 12.2”
* page 200 Table 7.2. Legend: “796” should be “760”



