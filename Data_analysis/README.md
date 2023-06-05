# Analysis of data
--- 

## Linear models (LMs)

- [Common statistical tests (t-test, chi-square test) are linear models](https://lindeloev.github.io/tests-as-linear/#9_teaching_materials_and_a_course_outline), which is relevant when it comes to teaching statistics.

## Linear mixed models (LMMs)

- An interesting visualization of how [mixed models pool information and the effect of shrinkage.](https://www.tjmahr.com/plotting-partial-pooling-in-mixed-effects-models/)

## Generalized linear mixed models (GLMMs)

- [Frequently asked questions](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html) on Generalized Linear Mixed Models (GLMM).

## Generalized additive models (GAMs)

- GAMMs: using [random effects](https://fromthebottomoftheheap.net/2021/02/02/random-effects-in-gams/) in GAMs
- [Interactive course](https://noamross.github.io/gams-in-r-course/) on GAMs by Noam Ross


## Ecological niche models (ENMs) - Species distribution models (SDMs)

- [Sillero et al. (2023) A curated list of R packages for ecological niche modelling.](https://doi.org/10.1016/j.ecolmodel.2022.110242)
- [Peterson et al. (2022) ENM2020: A free online course and set of resources on modeling species niches and distributions.](https://doi.org/10.17161/bi.v17i.15016)

## Causality

- Simpson's paradox: a trend revealed by a dataset can reverse when the dataset is split into groups. It is related to the [ecological fallacy](http://lineardigressions.com/episodes/2016/5/28/ecological-inference-and-simpsons-paradox): a mistaken deductive reasoning, in which we try to draw conclusions about individuals based on data collected at the group level. Some claim that the paradox [does not exist](https://wildetruth.substack.com/p/simpsons-paradox-and-existential).
- Lecture: [The foundations of causal inference.](https://www.youtube.com/watch?v=nWaM6XmQEmU)
- Lecture: [Science before statistics: causal inference.](https://www.youtube.com/watch?v=KNPYUVmY3NM&t=4937s)

## Community ecology

- David Zelený's [webpage](https://www.davidzeleny.net/anadat-r/doku.php/en:start) contains theory, and R functions and examples on ordination analysis, numerical classification, community-weighted-mean, fourth corner methods & RLQ, and diversity analysis.


## Spatial - GIS (Geograhpical Information System)

- [Overview](https://geocompx.org/post/2023/rgdal-retirement/#fn3) of how the R ecosystem for performing GIS operations has changed, including equivalencies among packages. Note that some packages are scheduled to "retired" in October 2023, and learning to use the modern alternatives is important.

## Fast code

- Measure [**how much time**](https://www.alexejgossmann.com/benchmarking_r/) it takes for a chunk of code to run, tictoc and microbenchmark are good options.
- [Multiple ways to optimize running time](https://www.r-bloggers.com/2016/01/strategies-to-speedup-r-code/).
- Some functions run models in a fast way, particularly useful when dealing with large datasets: glmmTMB::glmmTMB() (generalized linear mixed models with Template Model Builder), mgcv::bam() (big additive models).
- Some processes can be **parallelized**. [For instance,](https://stackoverflow.com/questions/74222940/parallelize-both-model-fitting-and-dredging-glmmtmb-dredge) glmmTMB::glmmTMB() (a fast way to fit GLM(M)s) and MuMIn::dredge() (fit all combinations of explanatory variables, can be combined with multimodel inference).
