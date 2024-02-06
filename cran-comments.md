## R CMD check results

0 errors ✓ | 0 warnings ✓ | 1 notes ✓

There were no ERRORs or WARNINGs. 

There was 1 NOTE:

❯ checking installed package size ... NOTE
    installed size is  7.3Mb
    sub-directories of 1Mb or more:
      data   7.2Mb

This is a data only package.It will eventually replace the toprdata package. 


## CRAN COMMENTS

1. Size of tarball: 7586078 bytes
--> A CRAN package should not be larger than 5 MB. Please reduce the size.

REPLY: This is a data only package.

2. If there are references describing the methods in your package, please
add these in the description field of your DESCRIPTION file in the form
authors (year) <doi:...>
authors (year) <arXiv:...>
authors (year, ISBN:...)
or if those are not available: <https:...>
with no space after 'doi:', 'arXiv:', 'https:' and angle brackets for
auto-linking.

REPLY: Done.

3. Please always write package names, software names and API (application
programming interface) names in single quotes in title and description.
e.g: --> 'Ensembl'
Please note that package names are case sensitive.

REPLY: Done.