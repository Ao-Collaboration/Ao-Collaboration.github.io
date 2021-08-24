---
layout: post
title: Empowering Admins Tutorial | web-to-case and web-to-lead
subtitle: A deeper dive into the web-to-case and web-to-lead functions. Learn the ropes with this tutorial.
seo-description: A deeper dive into the web-to-case and web-to-lead functions. Learn the ropes with this tutorial.
cover-img: assets/img/Empowering-Admins-CoverV2.jpg
thumbnail-img: assets/img/empowering-admins-share.jpg
share-img: assets/img/empowering-admins-share.jpg
tags: [Empowering Admins, Guides, Lightning, Service Cloud, Sales Cloud, Tutorial]
---

As anticipated in our [previous blog article](https://aocollab.tech/2021-08-03-empowering-admins-web-case-lead/), we are now taking a deep dive to see how the *Web-to-Case* and *Web-to-Lead* actually work. You will see they're both straightforward to setup and they bring immense advantages to your team's work.

## Web-to-case tutorial

### Prerequisites
First of all, it pays off to creeate an *email tmeplate* that will fire to your clients once they submit the case - it's your chance to make it as detailed as possible. It's good practice to remind them of your business hours (or SLA agreement if they have one) and first response time with this email, and any other information that's relevant to them.

Once that's done and dusted, you can create a *Queue* for assigning cases directly to the users. Keep in mind that default owners from the Support Setting will be assigned to all submissions if you don't create your own.

{:refdef: style="text-align: center;"}
![PhoneWagon salesforce integration]({{ 'assets/img/2021-08-24-tutorial-01.png' | relative_url }})
{:refdef}

### Setup
1. in Setup, use the Quick Find box to find the **Web-to-Case** and click on it
2. Tick the **Enable Web to Case** box
3. Choose a **Case of Origin** from the dropdown menu - email, phone, or web
4. Select the **default Response Template** you've created during the *Prerequisites* phase
5. Provide an Email Signature or just use the default one
6. Save

{:refdef: style="text-align: center;"}
![PhoneWagon salesforce integration]({{ 'assets/img/2021-08-24-tutorial-02.png' | relative_url }})
{:refdef}

### Generate HTML

7.  Use the Quick Find box to find the **Web-to-Case HTML Generator** and click on it
8.  Select fields you want to show in your form from the **Available Fields** section and add them to the Selected section
9.  Enter the **Return URL** - best practice is to create a different webpage than the homepage so users have visual confirmation they submitted their form correctly
10.  Click on the **Generate** button

{:refdef: style="text-align: center;"}
![PhoneWagon salesforce integration]({{ 'assets/img/2021-08-24-tutorial-03.png' | relative_url }})
{:refdef}

Once you've completed these steps, **Salesforce** will generate HTML code for you to copy/paste in the page of your website where you want this form to appear. Click on the **Finish** Button once you have saved the code somewhere safe.

And voilà.
<br/>
<br/>

## Web-to-lead tutorial

### Setup
1. in Setup, use the Quick Find box to find the **Web-to-Lead** and click on it
2. Tick the **Web-to-Lead Enabled** box

{:refdef: style="text-align: center;"}
![PhoneWagon salesforce integration]({{ 'assets/img/2021-08-24-tutorial-04.png' | relative_url }})
{:refdef}

### Generate HTML 
4. Click on **Create Web-to-Lead Form** button
5. Select fields you want to show in your form from the **Available Fields** section and add them to the Selected section
6. Enter the **Return URL** - best practice is to create a different webpage than the homepage so users have visual confirmation they submitted their form correctly
7. Click on the **Generate** button

{:refdef: style="text-align: center;"}
![PhoneWagon salesforce integration]({{ 'assets/img/2021-08-24-tutorial-05.png' | relative_url }})
{:refdef}

Once you've completed these steps, **Salesforce** will generate HTML code for you to copy/paste in the page of your website where you want this form to appear. Click on the **Finish** Button once you have saved the code somewhere safe.
<br/>
<br/>

## Useful Resources
* [Provide Web Forms with Web-to-Case](https://help.salesforce.com/articleView?id=sf.customize_casecapture.htm&type=5)
* [Guidelines for Setting Up Web-to-Lead](https://help.salesforce.com/articleView?id=sf.customize_leadpreparation.htm&type=5)
* [Engage Customers with Service Cloud - Trailhead Module](https://trailhead.salesforce.com/en/content/learn/modules/service_digital_engagement/service_digital_cloud)
* [Lead Generation for Marketers - Trailhead Module](https://trailhead.salesforce.com/en/content/learn/modules/lead-generation-for-marketers)
