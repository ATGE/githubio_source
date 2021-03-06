---
title: "getDiskUsageMetricImageByDate"
description: "Returns a disk usage image based on disk usage specified by the input parameters."
layout: "method"
tags:
    - "method"
    - "sldn"
    - "Account"
classes:
    - "SoftLayer_Account"
aliases:
    - "/reference/services/softlayer_account/getDiskUsageMetricImageByDate"
---
# [SoftLayer_Account](/reference/services/SoftLayer_Account)::getDiskUsageMetricImageByDate

Retrieve an image of the disk usage data on a [SoftLayer_Virtual_Guest]({{<ref "reference/datatypes/SoftLayer_Virtual_Guest">}}) image for the time range you provide. 


## Overview 
Returns a disk usage image based on disk usage specified by the input parameters. 

-----

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|startDateTime| dateTime| datetime of the start date of the graph|
|endDateTime| dateTime| datetime of the ending date of the graph|


### Required Headers
* authenticate


### Return Values
* <a href='/reference/datatypes/SoftLayer_Container_Account_Graph_Outputs'>SoftLayer_Container_Account_Graph_Outputs </a>


### Associated Methods

*  [SoftLayer_Metric_Tracking_Object::getSummaryData](/reference/services/SoftLayer_Metric_Tracking_Object/getSummaryData )




