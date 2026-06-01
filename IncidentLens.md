# Problem:

Outrage Happens.
Engineer jumps between prometheus, grafana, deployment history, kubectl logs, dashboards
due to which this goes more to the manual side

We need to automate this 

### Problems:
Not: Too Many Tools
Instead: Too many context switching

This problem is known as:
#### Context fragmentation during incidents

# Users



# Pain

# Solution: 

## IncidentLens

System automatically:

Collect:
- Metrics
- Logs
- Deployments
- Infra Events

Correlate.

Generate:
Incident Timeline

Example output:
```
10:00 Deploy Started
↓
10:02 API latency ↑
↓
10:03 CPU spike
↓
10:04 DB timeout
↓
10:06 Pod restarted
↓
10:08 Recovery
```

# Architecture

# Metrics

# Future
