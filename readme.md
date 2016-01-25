Andrew Fairless, January 2011
modified May 2015 for posting onto Github
This script calculates intracluster correlation coefficients for the effects
of litter membership on sociability as described in Fairless et al 2012
Fairless et al 2012, doi: 10.1016/j.bbr.2011.12.001, PMID:  22178318, PMCID:  PMC3474345

The fictional data in "altereddata.txt" were modified from the original 
empirical data used in Fairless et al 2012.
I am using fictional data instead of the original data because I do not have 
permission of my co-authors to release the data into the public domain.  
NOTE:  Because these data are fictional, several important characteristics of
these data may be different from those of the original data.

Each row is a separate mouse.
The left-most 3 columns are quasi-independent variables (mouse strain, sex, and age).
The right-most 5 columns are dependent variables describing behaviors of the
mice during the Social Approach/Choice Test.

analysis as described in Fairless et al 2012:
"We first investigated litter membership by asking whether littermates were 
more alike in their degree of sociability than non-littermates, after 
controlling for strain, sex, and age. In other words, does the sociability of 
mice cluster according to litter membership? . . . We analyzed social cylinder 
investigation (which consisted predominantly of sniffing of the social cylinder) 
in a linear mixed effects model for each strain as y = β0 + β1 (sex) + β2 
(age) + β1,2 (sex, age) + b1 (litter) where sex, age, and their interaction 
were modeled as fixed effects and litter was modeled as a random effect. . . .
The intracluster correlation coefficients for C57BL/6J and BALB/cJ mice were 
0.60 and 0.30, respectively. Thus for both strains, some factors that affect 
the litter as a whole cause the littermates to resemble each other in sociability 
more closely than do non-littermates."
