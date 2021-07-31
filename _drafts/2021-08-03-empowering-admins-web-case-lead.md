---
layout: post
title: Empowering Admins | web-to-case and web-to-lead
subtitle: Provide customer service with Web Forms and generate Leads from your website
seo-description: Provide customer service and generate Salesforce cases with Web Forms (Web-to-Case function) and generate Salesforce Leads from your website (Web-to-Lead function)
cover-img: assets/img/Empowering-Admins-CoverV2.jpg
thumbnail-img: assets/img/empowering-admins-share.jpg
share-img: assets/img/empowering-admins-share.jpg
tags: [Empowering Admins, Guides, Lightning, Service Cloud, Sales Cloud]
---

## Capture cases from your own website with the Web-to-Case function
Setting up your support platform is one of the very first steps towards a great customer experience - definitely a key requirement more than a 'nice to have'. While emails and phone always seem to do the trick, it's important to make sure you give your clients as many touch points as you can. With that in mind, including your website in your touch points makes for a nice addition, even before you consider portals and chats.

With Salesforce **Web-to-Case** (Service Cloud) you can gather customer support requests directly from your company’s website, it works by generating a snippet of HTML. This can help your organization respond to customers faster while improving your support team’s productivity. Keep in mind that Web-to-Case is exclusively a tool for the initial submission of cases, and that customers will not be able to see the status of their case submission.

It works by generating a snippet of HTML, and it has the sweet ability to add reCAPTCHA to help limit the much dreaded spam.

### Prerequisites
* Salesforce Classic (not available in all orgs) and Lightning Experience
* Essentials, Professional, Enterprise, Performance, Unlimited, and Developer Editions

### Notes and Limitations
* It is limited to receiving 5,000 cases per day
* Attachments are not supported, which means customers will not be able to attach images or files to cases
* Whenever possible, web-generated cases are automatically linked to the relevant contact account based on the customer’s email address with Web-to-Case
* Salesforce will run field validation rules before creating records submitted via Web-to-Case

## Gather visitors' information and turn them into leads with the Web-to-Lead function
Getting people to visit your website and keeping them longer is a key component of digital marketing. Once they visit your website you want them to turn into new leads for your marketing and sales teams. That’s where the Salesforce **Web-to-Lead** forms come into the picture.

It allows a way for you to create a lead record in Salesforce from a form you publish on your website, and the best way to get feedback on your product and services or grow your marketing database. Lastly, much like the previously introduced **Web-to-Case**, it has the sweet ability to add reCAPTCHA.

### Prerequisites
* Salesforce Classic (not available in all orgs) and Lightning Experience
* Group, Professional, Enterprise, Performance, Unlimited, and Developer Editions

### Notes and Limitations
* The format for date and currency fields captured online is taken from your organization’s default settings - `Default Locale and Currency Locale`
* The daily limit for Web-to-Lead requests is 500. After that, the Default Lead Creator (specified in the Web-to-Lead setup page) receives an email containing the additional lead information
* Before creating records submitted via Web-to-Lead, Salesforce runs field validation rules. If any field values are invalid, no lead record is created
* All universally required fields must have a value before a record can be created via Web-to-Lead
* Salesforce doesn’t support rich text area (RTA) fields on Web-to-Lead forms. If you use RTA fields on your forms, any information entered in them is saved as plain text when the lead is created
* Web-to-Lead forms don’t validate the email address field. To validate email addresses of web-generated leads, create a validation rule for the Email field on leads



## Useful Resources
* [Provide Web Forms with Web-to-Case](https://help.salesforce.com/articleView?id=sf.customize_casecapture.htm&type=5)
* [Guidelines for Setting Up Web-to-Lead](https://help.salesforce.com/articleView?id=sf.customize_leadpreparation.htm&type=5)
* [Engage Customers with Service Cloud - Trailhead Module](https://trailhead.salesforce.com/en/content/learn/modules/service_digital_engagement/service_digital_cloud)
* [Lead Generation for Marketers - Trailhead Module](https://trailhead.salesforce.com/en/content/learn/modules/lead-generation-for-marketers)
 
