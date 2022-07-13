---
title: "Investigating the use of screens in Super Learner ensembles"
date: 2018-01-28
tags: [machine learning, data science, data visualization]
header:
  image: "/images/lasso_vs_sl.png"
excerpt: "Machine Learning, Data Science, Data Visualization"
mathjax: "true"
---

# Investigating the use of screens in Super Learner ensembles

## Andrew King<sup>1</sup>; Brian Williamson, PhD<sup>2</sup>; and Ying Huang, PhD<sup>2</sup>

### <sup>1</sup>Seattle Central College & <sup>2</sup>Fred Hutchinson Cancer Research Center

**Abstract**

Clinical research trials often generate "big data"
* Examples: vaccine and cancer early detection research
* Large number of participants = good
* Large number of variables -> challenging
Machine learning increasingly used in biomedical research
* Helpful with a large number of variables
* Can identify complex relationships with outcome of interest
* Issue: performance can vary across algorithms
Potential solution: use an ensemble of algorithms
* Combine results across procedures
* Allows enhanced flexibility
* Issue: no formal guidelines for combining certain procedures
Goal: establish guidelines around ensemble procedures
Potential impact in vaccine, cancer research


*Methodology of this research will be available upon peer review*


**Results**
Lasso + SL not always a helpful combo; surprising result!
* SL with screens or SL with lasso and screens = safe choice
* Lasso by itself = unreliable in most cases
* Lasso + SL with no screens = unreliable in many cases

*Code will be available on GitHub once the paper is published*
* Open source under the MIT license

**Next steps:**
Train researchers to follow our guidelines + practices.
Conduct further research including:
* Building a study to address why the lasso alone is not ideal for variable selection
* Testing other algorithms that process biomedical data.
* Building this experiment in other programming language such as
C or Python for better performance

Following publication, results will be replicable by others with scientific computing tools
