# Question 4

## Command

```bash
tail -f system.log 2>/dev/null | grep "ERROR" >> error_report.txt
```

## Explanation

tail -f monitors the log.

grep extracts ERROR messages.

>> appends to the report.

2>/dev/null suppresses unnecessary output.
