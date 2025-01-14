---
description: StackPack description
---

# StackPack name

## Overview



![Data flow](/.gitbook/assets/stackpack-NAME.png)



## Setup

### Prerequisites

### Install

### Configure


### Status

To check the status of the DynaTrace integration, run the status subcommand and look for DynaTrace under `Running Checks`:

```
sudo stackstate-agent status
```

## Integration details

### Data retrieved

#### Events



#### Metrics



#### Topology



| Data | Description |
|:---|:---|
|  |  |
|  |  | 

#### Traces



### REST API endpoints


### Open source


## Troubleshooting

Troubleshooting steps for any known issues can be found in the [StackState support Knowledge base](https://support.stackstate.com/hc/en-us/search?category=360002777619&filter_by=knowledge_base&query=DynaTrace).

## Uninstall


## Release notes


## See also

-



=============
# stackpack template

Start with an intro. Include a high level overview (diagram!!) of how the StackPack works and where it sits in the StackState ecosystem.

![Diagram](/.gitbook/assets/dummy-diagram.png)

Describe what happens in the diagram (data flow). This should cover the type of information it produces:

- topological components and relations
- metrics, events and traces

## Install

{% hint style="info" %}
To decide - Should all the page be included in the UI StackPack or should basic steps completed in UI be covered there and link out to docs for remaining? (e.g. include pre-requisites, install and uninstall only).
{% endhint %}

#### Pre-requisites

Networking requirements and pre-requisites should be named here. If there are none, also state that here.

#### Installation

The steps to taken to install. It's ok if that is just 'click to install', also name it here. If there is more than one step, write as a process of numbered steps.

## Configure

Extra steps that need to be carried out to activate the StackPack. This can be a collection of headings or actions. For example, from the [Google Analytics StackPack](/stackpacks/integrations/google_analytics.md) page:

### Common configuration

Parameters should be described in a table. If there are steps to follow number these as a process. Include an example.

### Core reporting API

...

### Real-time reporting API

...

### Google Analytics integration

...

## Troubleshooting

Describe any common issues/misunderstandings or troubleshooting steps here. Note that known issues should also be covered in the StackState support site.

## Uninstall

If the uninstall includes manual or extra steps these should be included here. If it is a standard 'click to uninstall', also describe that here - don't leave the reader to guess.

## See also

End the page with pointers to relevant, further info. This might just be a list with any links already included in the page. If the StackPack is used in a tutorial, include that here.

- link 1
- link 2
- link 3
