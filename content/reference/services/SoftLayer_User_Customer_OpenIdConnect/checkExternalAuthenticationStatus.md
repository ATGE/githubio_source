---
title: "checkExternalAuthenticationStatus"
description: "This service checks the result of a previously requested external authentication. [[SoftLayer_Container_User_Customer_Ex... "
layout: "method"
tags:
    - "method"
    - "sldn"
    - "User"
classes:
    - "SoftLayer_User_Customer_OpenIdConnect"
aliases:
    - "/reference/services/softlayer_user_customer_openidconnect/checkExternalAuthenticationStatus"
---
# [SoftLayer_User_Customer_OpenIdConnect](/reference/services/SoftLayer_User_Customer_OpenIdConnect)::checkExternalAuthenticationStatus

Checks if an external authentication is complete or not


## Overview 
This service checks the result of a previously requested external authentication. [[SoftLayer_Container_User_Customer_External_Binding_Phone|Phone external binding]] container can be used for this service. Make sure to set the [[SoftLayer_Container_User_Customer_External_Binding_Phone::authenticationToken|authenticationToken]] that is generated by [[SoftLayer_User_Customer|initiateExternalAuthentication]] service. 

### Parameters 
|Name | Type | Description |
| --- | --- | --- |
|authenticationContainer| <a href='/reference/datatypes/SoftLayer_Container_User_Customer_External_Binding'>SoftLayer_Container_User_Customer_External_Binding </a>| The authentication container with the external authentication information.|


### Required Headers
* authenticate

### Optional Headers

### Return Values
<a href='/reference/datatypes/SoftLayer_Container_User_Customer_Portal_Token'>SoftLayer_Container_User_Customer_Portal_Token </a>
