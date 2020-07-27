---
layout: post
title: Choosing Parameters for LWE
subtitle: Materials for choosing parameters for LWE
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [LWE, parameters]
---


For choosing parameters, we can use the following tools:

1. **LWE Estimator (Documentations):**
[Documentations](https://lwe-estimator.readthedocs.io/en/latest/) 
---

2. **Script on SageMath:** 

{% highlight javascript linenos %}
load("https://bitbucket.org/malb/lwe-estimator/raw/HEAD/estimator.py")
n, alpha, q = 256,  0.000976562500000000,  65537
set_verbose(1)
_ = estimate_lwe(n, alpha, q)
{% endhighlight %}

---
3. **Estimate all the LWE, NTRU schemes:** 
Can see [here](https://estimate-all-the-lwe-ntru-schemes.github.io/docs/) 
