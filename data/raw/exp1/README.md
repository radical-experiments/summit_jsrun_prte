# JSRUN overheads

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

### JSRUN overhead 
```
(cu_exec_stop - cu_exec_start) - 900
```

