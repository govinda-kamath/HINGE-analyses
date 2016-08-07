# HINGE-analyses
Analysis accompanying  "HINGE: Long-Read Assembly Achieves Optimal Repeat Resolution" http://biorxiv.org/content/early/2016/07/05/062117

Stuff needed to be installed

```
build-essential
libhdf5-dev
libboost-all-dev
cmake-3.2
g++-4.9
gcc-4.9
```


```
git clone https://github.com/govinda-kamath/HINGE-analyses.git
git submodule foreach --recursive git submodule update --init
git submodule update --init --recursive
```

The results of the paper can be reproduced in [this](https://github.com/govinda-kamath/HINGE-analyses/blob/master/HINGE_pipeline_NCTC.ipynb) notebook.
