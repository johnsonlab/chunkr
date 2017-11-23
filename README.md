# chunkr
R code chunk database and handling package

chunkr ("chunk-er") is an R package that creates a central repository for R code chunks. chunkr can keep code chunks synced between separate files, or, allows for forking chunks so you can easily import and re-use code.

Copying and pasting code chunks between projects is simple and effective, and version control for .R or .Rmd files keeps your project moving forward. However, some data analyses truly "belong" to more than one project. For example, a single code chunk might produce a dataset analysis that's relevant both to a basic ovary project and an ovarian cancer project. In such a case, it is undesirable to repeat the same analysis in two different places (e.g., two separate .Rmd files in two different projects that import and process the same data). Essentially, chunkr is a method for 1) storing useful code chunks in a "central" location, the chunkbase file. 2) symlinking code chunks between files, and/or 3) pulling code into a new file a la "forking" and re-use.
