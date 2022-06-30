# AcademicData

First things first I added numpy and panda data librarys.

I then proceeded to make sure that they were both working by creating a simple data set and using that to test it out.

After that I imported my csv file which is a study about colleges done by the Us department of education, linked below.
https://collegescorecard.ed.gov/data/
The codebook is linked here:
https://collegescorecard.ed.gov/assets/FieldOfStudyDataDocumentation.pdf

I printed the list of column labels.

After I found something I found interesting in the codebook, in this instance the median salary after 3 years after graduation.  I removed the data that was not numeric from the column using "loc", and then made a frequency analysis.

I also made a histogram chart to be able to visualize the data.

Finally after doing that I found the mean, and standard deviation using describe(), and the mean using mean().

The summary is as follows:
mean      47047.696308
std       22473.219252
min           0.0
25%       32482.0
50%       42644.0
75%       57308.5
max      267734.0
median    42644.0
I learned that the standard deviation between college earnings is quite large and that dental/medical schools make by far the most money. Also the college with the most earnings on median after 3 years was the Ohio state university dental school at 267,000.  I actually suspect the statistics is probably off, in the sense that I don't know if the 0 in the column means really the median earning after three years was 0 or if it just means unreported. I didn't find this out in my (quick glance) at the codebook, but I think this is probably good enough for the assignment today.
