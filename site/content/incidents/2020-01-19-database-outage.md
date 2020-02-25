+++
title = "Database Outage"
date = 2020-01-19T11:23:00.000Z
severity = "major-outage"
affectedsystems = ["Database"]
resolved = true
+++
**Issue:** Following a routine maintenance task some customers are reporting that their events no longer appear under their accounts. We are investigating.
{{< track "2020-01-19T11:29:00.000Z" >}}The symptom is that data for some accounts isn’t appearing because of records deleted from a key table.

We’re working on getting this sorted as a matter of urgency.
{{< track "2020-01-19T12:18:00.000Z" >}}Progress is being made — data has been retrieved and we’re just going through the steps needed to restore the affected accounts.
{{< track "2020-01-19T14:23:00.000Z" >}}Preparing the final steps to restore the affected accounts.
{{< track "2020-01-19T14:43:00.000Z" >}}Incident resolved.
{{< track "2020-01-21T21:14:00.000Z" >}}[Link to Incident Report](https://blog.tito.io/posts/incident-report-sunday-19th-january/)