---
id: visualize-experiment
title: Visualize the Chaos Experiment Execution
sidebar_label: Visualize Chaos Experiment
---

---

Visualization is an important aspect while doing chaos engineering. It allows the user to discover and inspect different changes that occur during a Chaos Experiment execution. <br/>
With ChaosCenter, the real-time data and status of the chaos experiments can be observed. Valuable information like pod logs, chaos experiment status, chaos results can also be viewed.

## Prerequisites

The following should be required before creating a Chaos Experiment:

- ChaosCenter
- [Chaos Experiments](chaos-workflow.md)

## Litmus Chaos Experiment

If the user chooses to 'Save' and 'Run' the experiment, they will be redirected directly to the experiment execution page where the experiment can be visualised else they will be taken Chaos Experiment Page.

## Visualize a Litmus Chaos Experiment

To observe a chaos experiment, user needs to select the highlighted experiment run box from the heatmap, it will redirect to experiment run execution page.<br/>
<img src={require('../assets/workflow-observe-select.png').default} width="800" />

In the chaos experiment a realtime graph of the chaos experiment is displayed. This graph contains valuable information regarding the status of individual steps of the chaos experiment.<br/><br/>
<img src={require('../assets/workflow-observe-running.png').default} width="800" /><br/><br/>
To view the details of each step, user can click on the individual nodes and right side pane will display the node details, results(once the execution is complete) and the logs related to it.
<br/><br/>
<img src={require('../assets/workflow-observe-log.png').default} width="800" />
<img src={require('../assets/workflow-observe-completed.png').default} width="800" />

## Summary

After scheduling a chaos experiment, a user can view the details of the running chaos experiment from the ChaosCenter. ChaosCenter provides a realtime graph that is used to visualise the chaos experiment and get the details of individual step of the chaos experiment. Important details like the logs and target applications can be viewed from ChaosCenter. Once the chaos experiment exection is completed, the resiliency score is calculated and the ChaosResult for the ChaosEngine pods are available.

## Learn More

- [Explore Probes](probes.md)
- [What is a Chaos Experiment](chaos-workflow.md)
- [Examine the ChaosResult](chaos-result.md)