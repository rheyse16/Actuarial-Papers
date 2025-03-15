# Actuarial-Papers
My repository for going through various actuarial papers I find interesting and creating examples in python. I may organize them further over time. For instance, I am currently interested in bayesian methods and I work in pricing. Early papers are likely to be around frequency/severity fitting, large account pricing, trends, indications. 

## Getting setup
I am trying to just use one environment for all papers, which could be a generally useful actuarial environment.

conda env create -f environment.yml
conda activate act-pap-env

## Papers
### Bayesian Claim Severity with Mixed Distributions - Benedict Escoto
[Paper Link](https://variancejournal.org/article/120820) 
This paper contains a bayesian approach to severity distribution fitting. It focuses on the mixed exponential for something like XoL reinsurance pricing. I work with mixed exponential distributions, particularly for XS pricing and I am interested in testing this method of fitting out.

### Severity Curve Fitting in Long Tail Lines - Greg McNulty
[Paper Link](https://www.casact.org/sites/default/files/2021-07/Severity-Curve-Fitting-McNulty.pdf)
This paper contains a bayesian approach to fitting severity distributions to a triangle. It is essentially developing parameters, but using a bayesaian approach to guide the fit. I'm not sure how practical it actually is. The underlying model is actually quite simple and reminds me of my bootstrap severity curve fitting technique.