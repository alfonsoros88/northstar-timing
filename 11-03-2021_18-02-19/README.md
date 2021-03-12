# Test results (Thu, 11 Mar 2021 18:02:19 +0000)


Git Revision | Test Duration (seconds)
------------ | -----------------------
northstar@5a34008e3ebe681982cb84c16f1cbfaf001d51e2 | 43200

### Test configuration
```yaml
---
time:
  secs: 43200
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
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 60
      nanos: 0
    action: sleep
  - name: test01
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 30
      nanos: 0
    action: sleep
  - name: test03
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 30
      nanos: 0
    action: sleep
  - name: test04
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 60
      nanos: 0
    action: sleep
  - name: test05
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 30
      nanos: 0
    action: sleep
  - name: test06
    start_after:
      secs: 30
      nanos: 0
    stop_after:
      secs: 30
      nanos: 0
    action: sleep
results:
  out_dir: results
  entry_name: ~
error_context_lines: 3
strace: false

```

## Memory consumption

![memory graph](plots/memory.png)
## Files open

![file descriptors graph](plots/fd.png)
## Log Errors

