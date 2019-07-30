# PRRTE overheads

## RP Stack
```
  python               : 2.7.15
  virtualenv           : /autofs/nccs-svm1_home1/mturilli1/experiments/ve/jsrun_prte
  radical.pilot        : 0.70.0-v0.70.0@master
  radical.saga         : 0.70.0-v0.70.0@master
  radical.utils        : 0.70.0-v0.70.0@master
```

## RP Configuration
- \# (sub-)Agent: 1

## Workload
- Executable: stress
- \# cores: 1
- \# GPU: 0
- I/O: None
- Runtime: 15 minutes
- Concurrency: 0--2048

## Measures
As per RADICAL-Analytics and RP events:

### RP Agent overhead
```
(rp.AGENT_STAGING_OUTPUT_PENDING - rp.AGENT_EXECUTING) -
(cu_exec_stop - cu_exec_start) -
900
```

### PRRTE overhead
```
(cu_exec_stop - cu_exec_start) - 900
