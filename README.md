# Open Policy Agent Grafana dashboard

![](images/dashboard-image-1.png)

This repo hosts my initial work on the Grafana dashboard for Open Policy Agent.

It visualizes most of the metrics recorded by Open Policy Agent as documented in https://www.openpolicyagent.org/docs/latest/monitoring/

The version of OPA that this is made for is 0.26. I can't promise if it can work on later versions. Should there be any changes from open policy agent, this needs to be updated. 

**Notes:** Before you use this dashboard, please mind the variables and the prometheus labels. It may not be applicable in your case or your K8s cluster may use another name than mine.

Remaining issues:
- [] Avg response time and http response time doesnt seem to be correct. The units of avg response time is really weird. Need more investigation in OPA source code as well as my queries.




