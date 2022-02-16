# DC_new-website-design

## Data Camp competition - Evaluation of Landing Page redesign impact on CTR metric

**Project task:** 
* to analyze the conversion rates for each of the four groups: the new/old design of the landing page and the new/old pictures
* to check the statistical significance of the increases observed
* to recommend the version of the website to use

Data preparation, data analysis, data visualization, A/B testing, statistical significance check

**Language:** Python

**Libraries:** Pandas, SciPy, NumPy, Math, Matplotlib, Plotly

**Conclusions CONVERSION RATES ANALYSIS:**

* The traffic split proved to be correct - each group is represented by equal number of users = 10 121 => stat test has sense.
* Convertion rate leader is group C with 12% / new version with old set of images.
* Convertion rate outsider is group A with 10,71% / old version with old set of images.
* Group D / new version with new set of images / with 11,37% takes the 2-nd place.
* Group B / old version with new set / with 11,25% takes the 3-d place.
* Users appreciate changes.

**Conclusions STATISTICAL SIGNIFICANCE CHECK:**

The statistical significance check proved that the detected differences between:
* Group A (control) & Group B (test) have no statistical significance. The p-value = 0.2163148562938333, which is far bigger than 0.05 - the critical level of statistical significance taken for the test.
* Group A (control) & Group C (test) have statistical significance. The p-value = 0.0037091839675174043 and we can reject H0 in favor of H1 = 'converted rates in groups are not equal & detected differences have statistical significance'.
* Group A (control) & Group D (test) have no statistical significance. The p-value = 0.13294339963478086, which is far bigger than 0.05 - the critical level of statistical significance taken for the test.

**RECOMMENDATION on the version of the website to use:**

* Test group C gained the top convertion rate = 12% / new version with old set of images.
* The statistical significance check proved that the difference in convertion rates between groups A (control) & C (test) has sufficient statistical evidence.
* Users proved typical customer attitude towards changes: "We want something new, but in moderate proportion". Version 'NEW, BUT WITH OLD SET OF IMAGES' is recommended based on the above analysis.
