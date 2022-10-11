# 12s Reference Library for Maine-eDNA

We're working on putting together a reference library for the 12s RNA region for metabarcoding.

## Guidelines for contributing

If you'd like to make contributions, please first check the issues list to see if anyone else is working on the same thing.  Next, if the contribution you'd like to make is new, then write a detailed issue outlining what you're *going* to contribute (before you even contribute it). Then work on whatever you'd like to add, commit it, and push it.  Once pushed, close the issue and reference the commit that resolves the issue.

Add your code to the `12s_figuring.Rmd` document.

Add raw, "read-only" data to the `/data/` directory.  

Use relative paths to read-in data (i.e. *do not* use `setwd(".....")`---this will break on other people's machines).
