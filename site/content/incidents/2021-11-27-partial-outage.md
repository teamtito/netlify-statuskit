+++
title = "Partial outage"
date = 2021-11-27T09:40:17.000Z
severity = "partial-outage"
affectedsystems = ["Checkout", "API"]
resolved = true
+++
Currently investigating an issue affecting checkout, widgets and API
{{< track "2020-11-27T12:30:00.000Z" >}}An unintended CORS misconfiguration caused requests to fail. We're still looking in to the root cause, but we've rolled back to our previous working configuration.