---
layout: post
title: Collaboration | Integrate Calendly and Salesforce
subtitle: Seamlessly schedule meetings with team members and clients with this powerful integration 
cover-img: assets/img/integrations-cover-v2.jpg
thumbnail-img: 
share-img: 
tags: [Collaboration, Calendly, Integrations]
---

{:refdef: style="text-align: center;"}
![slack salesforce integration]({{ 'assets/img/2021-04-27-calendly-salesforce.jpg' | relative_url }})
{:refdef}

This integration  

<br/>
<br/>

## Integration Requirements
To integrate Calendly with Salesforce you will need a:
* **Calendly Pro** account with admin or owner privileges
* **Salesforce Enterprise** or higher edition with admin privileges
<br/>
<br/>

## Alternatives: Zapier and Automate.io
In case you already make use of workflows to automate processes and connect third party apps, here are a couple of options that allow you to connect **Salesforce** and **Calendly**:
* [Integrate with Zapier](https://zapier.com/apps/calendly/integrations/salesforce)
* [Integrate with Automate.io](https://automate.io/integration/calendly/salesforce)

The advantage of creating workflows with these platforms - especially if you already have in-house automation specialists - is the freedom to create custom workflows that make sense for your organization. The other side of the coin is the inability to leverage an out-of-the-box integration or get support for it, so we recommend this solution to companies who already well versed in **Zapier** or **Automate.io** and have the capacity to have one of the team build and maintain the automation.
<br/>
<br/>

## Default flows included
As Calendly meetings are scheduled or canceled, you’ll be able to:
* Cancel Event Flow
* Create Event for Case Flow
* Create Event for Lead Flow
* Create or Update Lead or Contact Flow

### Actions defined in the default flows
* When a Calendly event is created, if a record
  * does *not* exist in **Salesforce** with the invitee’s email  a new lead will be created  
  * does exist, then an event will be added to either a lead or case associated with the invitee’s email address
* Whenever a meeting is canceled, the event will be updated and the word “canceled” will appear next to the event in Salesforce
* All record lookups are defined by the owner of the Calendly event
* When a new lead is created from a Calendly event, the owner of this record will belong to the assigned Calendly user
* When a new event is created, the owner of this record will also belong to the assigned Calendly user
<br/>
<br/>

## Useful Resources
* [Customize Calendly's Salesforce flow | Calendly HelpDocs](https://help.calendly.com/hc/en-us/articles/360035487554-Customize-Calendly-s-Salesforce-flow)
* [Salesforce Integration | Calendly HelpDocs](https://help.calendly.com/hc/en-us/articles/223195548-Salesforce)
* [Integrate with Zapier](https://zapier.com/apps/calendly/integrations/salesforce)
* [Integrate with Automate.io](https://automate.io/integration/calendly/salesforce)
<br/>
<br/>
