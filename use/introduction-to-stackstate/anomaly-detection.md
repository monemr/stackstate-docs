---
description: Use StackState to detect anomalies in your IT infrastructure
---

# Anomaly detection

## Overview

StackState can detect anomalies in your IT infrastructure by monitoring the metric streams attached to elements. There are two methods of anomaly detection available:

* [Autonomous anomaly detection](anomaly-detection.md#autonomous-anomaly-detection) using machine learning models.
* [Baseline anomaly detection \(Deprecated\)](anomaly-detection.md#baseline-anomaly-detection) using configured metric baseline values.

Each metric stream can use either autonomous or baseline anomaly detection. It is not possible to use both types of anomaly detection on one metric stream at the same time. This means that any metric stream configured with a baseline will not be picked up for anomaly detection by the Autonomous Anomaly detector.

## Autonomous anomaly detection

The StackState Autonomous Anomaly Detector \(AAD\) StackPack works fully autonomously to identify anomalies in your IT environment. When installed and enabled, it will determine for itself the best configuration of its machine learning models and the metric streams that should be prioritized for anomaly detection. No configuration is required although you can influence the selection of telemetry streams by giving a them higher priority.

Once the anomalies are identified, they are displayed in the MetricStream charts as in the example below:

![Anomaly example](../../.gitbook/assets/anomaly-chart-write-latency.png)

Additionally, identified anomalies are available as StackState Events and can be viewed in the [Events Perspective](../perspectives/events_perspective.md) when event category `Anomalies` is selected in the filter.

![Anomaly events](../../.gitbook/assets/v43_anomaly-events-in-events-perspective.png)

Finally, [anomaly health checks](../health-state-and-event-notifications/anomaly-health-checks.md) can be configured for the most important metric streams to alert on problems before they occur.

Read more about the [Autonomous Anomaly Detector](../../stackpacks/add-ons/aad.md).

## Baseline anomaly detection

{% hint style="warning" %}
Baseline anomaly detection is **deprecated** and will be removed in the StackState 4.4 release. Please use the [Autonomous Anomaly Detector\)](anomaly-detection.md#autonomous-anomaly-detection).
{% endhint %}

Each metric stream can have metric baselines manually configured or set by a template. The baselines determine the normal operating values of a metric stream and can be used in health checks and to trigger health state changes. Note that any metric stream with a base line configured will not be picked up for autonomous anomaly detection.

Read more about [anomaly detection with baselines](../health-state-and-event-notifications/anomaly-detection-with-baselines.md)

