# ACI ACRIS Passenger Wait Times API

> Repository of ACI ACRIS Passenger Wait Times API interface standard specification

This data interface recommendation was produced by the ACI ACRIS (Aviation Community Recommended Information Services) Working Group and complies with the ACRIS Semantic Model and interface specifications, including the relevant terms and specification of the API (Application
Programming Interface).

## What is ACI ACRIS?

_ACRIS_ is an acronym for “Airport Community Recommended Information Services”, and is one of the working groups under ACI World. Members of the working group are airports, airlines and vendors.
The purpose of this working group is to define standard data models and web interfaces for exchanging operational and passenger related data between the partners in a standardized way.  

Two working group face-to-face meetings are being held each year and additional meetings or conference calls are scheduled as required by the projects and topics. 

The working group is open for airports, airlines and partners from the aviation industry; participation is on voluntary base. All contribution on meetings or projects is done on the own expense of the participants.  
For more information on ACI ACRIS working group visit the [ACRIS website](https://acris.aero).

## ACRIS Passenger Wait Times

It is difficult for passengers and the wider travel industry to obtain information on the actual and expected waiting times at airport security checkpoints.

In the United States of America, the Transportation Security Administration (TSA) has mandated that airports capture and provide information on how long passengers need to wait at security checkpoints.

A set of standard APIs makes this information readily available to passengers and other stakeholders.

## Passenger Wait Time Measurements

The standard describes four Passenger Queue Wait Time metrics:
 
| Measurement | Definition |   
|-----------|:-----------:| 
| Occupancy | The count of people in the queue. The unit of measure is number of people. This metric is updated every five minutes. |  
| Projected Wait Time | The estimated time that a person entering the queue can expect to wait. The unit of measure is seconds. Estimates are updated every five minutes |  
| Throughput | The average number of passengers processed over the past hour. The unit of measure is passengers per hour. This metric is updated every five minutes |  
| Wait Time | The duration that a person exiting the queue has experienced. The unit of measure is seconds. The amount represents the average number of seconds experienced by people exiting the queue in the last five minutes. This metric is updated every five minutes |  


## Release History

| Version | Date | Notes |  
|-----------|:-----------:|-----------:|  
| 1.6.0 | 26th Apr 2023 | Updated for Open API version 3.0.3 <br> Enriched metadata <br> Alignment with ASM terms|  
| 1.5.0 |  3rd Sep 2019 | Initial Release |  


## Contribute to Passenger Wait Times

The ACI ACRIS Passenger Wait Times Standard consist of two components:

1. The API Specification Documentation (PDF)
2. Supporting files that contain implementation details for the interfaces (OpenAPI YAML specification)

Change requests can concern one or more of these components. The change process is described on the [ACRIS website](https://acris.aero).

For any questions use the contacts below

## Links
### ACI World
https://aci.aero

### ACI ACRIS Website
https://acris.aero

