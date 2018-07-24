# Representational similarity analysis
## Tutorial for Methods in Neuroscience at Dartmouth (MIND) 2018

Representational similarity analysis (RSA) is statistical technique based on analyzing second-order isomorphisms. That rather than directly analyzing the relationship between one measure and another, RSA instead computes some measure of similarity within each measure and then compares these similarities to each other. RSA was pioneered by [Kriegeskorte, Mur, and Bandettini (2008, Frontiers in System Neuroscience)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2605405/) and has since become a popular method for analyzing neuroimaging data. Much of this popularity is driven by the fact that - because RSA focuses on second-order isomorphisms (i.e., similarities) - it is an incredibly flexible analytic technique, capable linking disparate measures of brain and behavior.

![Kriegeskorte, Mur, and Bandettini (2008)](http://www.mrc-cbu.cam.ac.uk//personal/nikolaus.kriegeskorte/fig5_kriegeskorte_RSA_FNS.gif)

In the context of fMRI, RSA usually takes the form of a correlation or regression between neural pattern similarity and a task, rating, or model. In this tutorial we will learn how to conduct these confirmatory RSAs as well as how
to perform complementary exploratory analyses.
