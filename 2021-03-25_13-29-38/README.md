# Test results (Thu, 25 Mar 2021 13:29:38 +0000)


Git Revision | Test Duration (seconds)
------------ | -----------------------
northstar@54139bcad182189c1edf7cb596799ec3550d32af | 13909

### Test configuration
```yaml
---
time:
  secs: 28800
  nanos: 0
cpus:
  - 1
  - 2
  - 3
  - 4
metrics:
  memory:
    freq:
      secs: 1
      nanos: 0
  file_descriptors:
    freq:
      secs: 1
      nanos: 0
containers:
  - name: test00
    version: 0.0.1
    start_after:
      secs: 5
      nanos: 0
    stop_after:
      secs: 5
      nanos: 0
  - name: test01
    version: 0.0.1
    start_after:
      secs: 1
      nanos: 0
    stop_after:
      secs: 1
      nanos: 0
  - name: test02
    version: 0.0.1
    start_after:
      secs: 1
      nanos: 0
    stop_after:
      secs: 2
      nanos: 0
  - name: test03
    version: 0.0.1
    start_after:
      secs: 2
      nanos: 0
    stop_after:
      secs: 3
      nanos: 0
  - name: test04
    version: 0.0.1
    start_after:
      secs: 2
      nanos: 0
    stop_after:
      secs: 4
      nanos: 0
  - name: test05
    version: 0.0.1
    start_after:
      secs: 2
      nanos: 0
    stop_after:
      secs: 5
      nanos: 0
  - name: test06
    version: 0.0.1
    start_after:
      secs: 3
      nanos: 0
    stop_after:
      secs: 6
      nanos: 0
  - name: test07
    version: 0.0.1
    start_after:
      secs: 3
      nanos: 0
    stop_after:
      secs: 7
      nanos: 0
  - name: test08
    version: 0.0.1
    start_after:
      secs: 4
      nanos: 0
    stop_after:
      secs: 8
      nanos: 0
  - name: test09
    version: 0.0.1
    start_after:
      secs: 4
      nanos: 0
    stop_after:
      secs: 9
      nanos: 0
  - name: test10
    version: 0.0.1
    start_after:
      secs: 5
      nanos: 0
    stop_after:
      secs: 10
      nanos: 0
  - name: test11
    version: 0.0.1
    start_after:
      secs: 5
      nanos: 0
    stop_after:
      secs: 11
      nanos: 0
  - name: test12
    version: 0.0.1
    start_after:
      secs: 6
      nanos: 0
    stop_after:
      secs: 12
      nanos: 0
  - name: test13
    version: 0.0.1
    start_after:
      secs: 6
      nanos: 0
    stop_after:
      secs: 13
      nanos: 0
  - name: test14
    version: 0.0.1
    start_after:
      secs: 7
      nanos: 0
    stop_after:
      secs: 14
      nanos: 0
  - name: test15
    version: 0.0.1
    start_after:
      secs: 7
      nanos: 0
    stop_after:
      secs: 15
      nanos: 0
  - name: test16
    version: 0.0.1
    start_after:
      secs: 8
      nanos: 0
    stop_after:
      secs: 16
      nanos: 0
  - name: test17
    version: 0.0.1
    start_after:
      secs: 8
      nanos: 0
    stop_after:
      secs: 1
      nanos: 0
  - name: test18
    version: 0.0.1
    start_after:
      secs: 9
      nanos: 0
    stop_after:
      secs: 2
      nanos: 0
  - name: test19
    version: 0.0.1
    start_after:
      secs: 9
      nanos: 0
    stop_after:
      secs: 3
      nanos: 0
  - name: test20
    version: 0.0.1
    start_after:
      secs: 10
      nanos: 0
    stop_after:
      secs: 5
      nanos: 0
results:
  out_dir: results
  entry_name: ~
log_level: INFO
error_context_lines: 3
strace: false

```

## Memory consumption

![memory graph](plots/memory.png)
## Files open

![file descriptors graph](plots/fd.png)
## Log Errors

