---
layout: post
title: Choosing Parameters for LWE
subtitle: Materials for choosing parameters for LWE
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [LWE, parameters]
---


### LWE Estimator (Documentations): https://lwe-estimator.readthedocs.io/en/latest/ 

### Script on SageMath: 

{% highlight javascript linenos %}
load("https://bitbucket.org/malb/lwe-estimator/raw/HEAD/estimator.py")

n, alpha, q = 256,  0.000976562500000000,  65537

set_verbose(1)

_ = estimate_lwe(n, alpha, q)
{% end highlight linenos %}
#### Estimate all the fLWE, NTRUg schemes: https://estimate-all-the-lwe-ntru-schemes.github.io/docs/ 
