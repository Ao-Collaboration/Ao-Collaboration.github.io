---
layout: post
title: Empowering Admins | Dynamic Forms
subtitle: All you need to know about Salesforce Dynamic Forms and how to use them.
cover-img: /assets/img/Empowering-Admins-Cover.png
thumbnail-img: /assets/img/2020-12-16-dynamic-forms-thumb.jpg
share-img: /assets/img/2020-11-30coverV6.jpg
tags: [Empowering Admins, Guides, Lightning]
---

If you already are a Salesforce user, you will know that with the [Summer 20 Release Note](https://releasenotes.docs.salesforce.com/en-us/summer20/release-notes/rn_forcecom_lab_dynamic_forms.htm), Salesforce announced what was probably the number one feature request - over 10,000 votes and a 13 years timeline, people!

So, now that the hot stuff is finally out in the world, we figured it would be good to give you a general run-down and some step by step how-tos.

## What exactly are Dynamic Forms?
Dynamic Forms let users add fields and sections on custom object page layouts as individual components within the Lightning App builder. The goal is to create more intuitive pages that display the relevant information at the right time

With Dynamic forms we see a new standard Lightning component called “Field Section”. With this, you can add components to the page and select the fields to add in the section - and create a filter if necessary.

## Requirements and Limitations
* Available in: Lightning Experience
* Available in: Group, Professional, Enterprise, Performance, Unlimited, and Developer Editions
* Currently available as Non-GA preview (just like a Beta version) in Summer ’20 release, will be GA (fully released) in [Winter '21 release](https://releasenotes.docs.salesforce.com/en-us/winter21/release-notes/rn_forcecom_lab_dynamic_forms_ga.htm).
* Currently available only for Custom objects
* The component 'Field section' is not mobile supported
* The order and visibility of any related list on the objects would still be governed by the design established on the page layout edito

## Benefits at a Glance
* Better page UX and UI
* Visibility rules: fields and components appear and disappear based on criteria
* Layout management that better suits your business requirements
* Smarter layouts mean reduced number of page layouts
* Improve page load times
* Show and hide fields and sections

## Enabling Dynamic Forms
As mentioned in the **Requirements and Limitations** section, this feature is currently available as a Non-GA feature only. Simply put, you can test it and play around with it for now, but you cannot use it in your org. until the full release in Winter '21. Given the innumerous benefits the feature provides, we recommend you get a head-start and begin trying things out with it. 

To enable Dynamic Forms:
1. Go to **Setup**
2. Find **Record Page Settings** from the Quick Find box
3. Click **Enabled** (right hand side of the page)
4. **Save**

![Enable Dynamic Forms](https://aocollab.tech/assets/img/2020-12-16-enable-dynamic-forms.png)

For existing pages Salesforce implemented a special function that allows you to upgrade old record pages to Dynamic Forms automatically.
Just click the **Record Details** component and look for the **Upgrade Now** button at the top of the properties pane on the right hand side, and follow instructions.

![Upgrade Existing Pages](https://aocollab.tech/assets/img/2020-12-16-upgrading-existing-pages-to-dynamic-forms.png)

For brand new pages, you will see an additional tab labeled **Fields** in the left-hand components pane.
That’s where you find all the fields available for putting on the page. Before dragging any of those onto the page, you need to use the **Field Section** component to create an area to place your fields.

![New Pages](https://aocollab.tech/assets/img/2020-12-16-new-pages-dynamic-fields.png)

## Useful Resources
[Trailhead: Be An Innovator With Dynamic Pages Trailmix](https://trailhead.salesforce.com/users/strailhead/trailmixes/be-an-innovator-with-dynamic-pages)

[Break Up Your Record Details with Dynamic Forms](https://admin.salesforce.com/blog/2019/break-up-your-record-details-with-dynamic-forms)

[Dynamic Forms Tips and Considerations](https://help.salesforce.com/articleView?id=dynamic_forms_considerations.htm&type=5)

[Dynamic Forms Known Issues](https://help.salesforce.com/articleView?id=dynamic_forms_known_issues.htm&type=5)

[Release Notes](https://releasenotes.docs.salesforce.com/en-us/summer20/release-notes/rn_forcecom_lab_dynamic_forms.htm)
