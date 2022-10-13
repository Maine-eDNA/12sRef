# 12s Reference Library for Maine-eDNA

The Maine-eDNA Reference Library Working Group is working to test and develop a reference library workflow for use in metabarcoding and other applications. This workflow is currently aimed at the 12S DNA region in species that have been recorded as present or potentially invasive to the area now known as Maine. In time, we aim to build this workflow so that it can serve to target any DNA region, taxonomic group, or geographic region.

A succinct summary of our aims and planned methods is in the 'Summary of Goals' issue and will serve as a reference point for this work.


## Guidelines for contributing

If you would like to make contributions, please first check the issues list to see if anyone else is working on the same thing.  Next, if the contribution you'd like to make is new, then write a detailed issue outlining what you're *going* to contribute (before you even contribute it). Then work on whatever you'd like to add, commit it, and push it.  Once pushed, close the issue and reference the commit that resolves the issue.

Add your code to the `12s_figuring.Rmd` document.

Add raw, "read-only" data to the `/data/` directory.  

To read in data, use relative paths (i.e. *do not* use `setwd(".....")`---this will break on other people's machines)

## Key External Resources Used

[AnnotationBustR](https://github.com/sborstein/AnnotationBustR) - "An R package to extract sub-sequences from GenBank annotations"
