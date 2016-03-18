# alpine

![alpine](http://mike-love.net/img/alpine.jpg)

(the [Sassolungo](https://en.wikipedia.org/wiki/Langkofel) mountain in the Dolomites)

`alpine` is an R/Bioconductor package for modeling and correcting fragment
sequence bias for RNA-seq transcript abundance estimation. There is a
minimal example in `vignettes/alpine.Rmd`.

The code is still in development. Expect changes in the user-facing 
functions in particular, where a wrapper function will replace the 
lower-level bias modeling and abundance estimation steps in the
current vignette.

`alpine` is currently designed for un-stranded paired-end RNA-seq
data, and future work will allow support for strand-specific data.

A manuscript explaining the methods and the background behind fragment 
sequence bias is posted to [bioRxiv](http://biorxiv.org/content/early/2015/08/28/025767).
