---
layout: post
title:  Install SageMath on Linux using Miniconda (or Conda)
cover-img: /assets/img/math-beauty.jpeg
thumbnail-img: /assets/img/math-beauty.jpeg
share-img: /assets/img/math-beauty.jpeg
tags: [SageMath, conda, Miniconda, Linux, Python]
---



# Install SageMath on Linux using Miniconda (or Conda)


In this short instruction, we will proceed with Miniconda. For Conda, the installment  is the same.

**Step 1:** Download Miniconda at the link:  [https://docs.conda.io/en/latest/miniconda.html#linux-installers](https://docs.conda.io/en/latest/miniconda.html#linux-installers)

**Step 2:** Install Miniconda:

       - In the Terminal window, run the command:
       
            $ bash Miniconda3-latest-Linux-x86_64.sh
            
       - Choose the default setting for easy
       - Close and then re-open your terminal window to get affected.
       
**Step 3:** Using conda to install mamba (This way is recommended to get a better speed) as follows:

           $ conda install mamba -c conda-forge
           
**Step 4:** Using mamba to install SageMath

           $ mamba create -n sage sage -c conda-forge
           
**Step 5:** Every time we use SageMath, we activate SageMath in Conda by the command (in Terminal):

           $ conda activate sage 


Note: The image in this post is credited by [https://www.opensourceforu.com/2019/07/introducing-sagemath-a-system-for-algebraic-and-geometrical-experimentation/](https://www.opensourceforu.com/2019/07/introducing-sagemath-a-system-for-algebraic-and-geometrical-experimentation/)
