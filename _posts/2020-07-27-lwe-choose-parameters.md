

Choose Parameters for LWE
LWE Estimator (Documentations): https://lwe-estimator.readthedocs.io/en/latest/ 

Script on SageMath: 

load("https://bitbucket.org/malb/lwe-estimator/raw/HEAD/estimator.py")

n, alpha, q = 256,  0.000976562500000000,  65537

set_verbose(1)

_ = estimate_lwe(n, alpha, q)

Estimate all the fLWE, NTRUg schemes: https://estimate-all-the-lwe-ntru-schemes.github.io/docs/ 
