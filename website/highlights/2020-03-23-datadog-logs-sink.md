---
last_modified_on: "2020-04-13"
$schema: "/.meta/.schemas/highlights.json"
title: "New Datadog Logs Sink"
description: "Sink logs to the Datadog logging service"
author_github: https://github.com/LucioFranco
pr_numbers: [1832]
release: "nightly"
importance: "low"
tags: ["type: new feature", "domain: sinks", "sink: datadog_logs"]
---

In addition to our [`datadog_metrics` sink][docs.sinks.datadog_metrics], we've
introduced a new [`datadog_logs` sink][docs.sinks.datadog_logs]. This is part
of our broader effort to expand Vector's integrations.


[docs.sinks.datadog_logs]: /docs/reference/sinks/datadog_logs/
[docs.sinks.datadog_metrics]: /docs/reference/sinks/datadog_metrics/
