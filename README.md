# summit_jsrun_prte
Performance characterization and comparison of JSRUN and PRTE on Summit

# Analysis
Wrangling of the raw data requires `radical-analytics-wrangler.py -d ../ -t exp -e 1 -o ../exp1/` with radical-stack:
```
$ radical-stack 
  python               : 2.7.16
  pythonpath           : 
  virtualenv           : /Users/mturilli/Virtualenvs/hyperspace

  radical.analytics    : 0.70.0-v0.70.0@master
  radical.pilot        : 0.70.3-v0.70.3-5-g16c14e7c@master
  radical.saga         : 0.70.0-v0.70.0@master
  radical.utils        : 0.70.1-v0.70.1@master

```

Plotting requires `jupyter` and radical-stack:
```
$ radical-stack 
  python               : 2.7.16
  pythonpath           : 
  virtualenv           : /Users/mturilli/Virtualenvs/summit_jsrun_prte

  radical.analytics    : 0.70.0-v0.70.0-51-g6528353@feature-experiment
  radical.pilot        : 0.70.3-v0.70.3-170-g2588ec3d@feature-ra_metrics
  radical.saga         : 0.62.0
  radical.utils        : 0.70.0-v0.70.0-15-gd281574@devel

```
