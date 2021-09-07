---
layout: post
title: Empowering Admins | Setup Facebook Lead Capture integration into Salesforce
subtitle: Learn how to import leads from Facebook Lead Ad campaigns right into your Salesforce org in real time.
seo-description: Learn how to import leads from Facebook Lead Ad campaigns right into your Salesforce org in real time, ready for your sales team to qualify and convert.
cover-img: assets/img/Empowering-Admins-CoverV2.jpg
thumbnail-img: assets/img/empowering-admins-share.jpg
share-img: assets/img/empowering-admins-share.jpg
tags: [Empowering Admins, Guides, Integration, Facebook, Sales Cloud]
---

{:refdef: style="text-align: center;"}
![Facebook for business salesforce integration]({{ 'assets/img/2021-09-07-facebook-salesforce.jpg' | relative_url }})
{:refdef}

Today we are showing you a cool trick that you definitely want to take advantage of [now that you have made a start with your marketing strategy](https://aocollab.tech/2021-08-31-small-businesses-communication-basics/). It involves **Facebook** and your **Salesforce Sales Cloud**.

**Facebook Lead Ads** is a witty solution that makes filling forms quick on easy on mobile. It leverages the data pool of *1.7 billion people* already present on Facebook to pre-populate relevant fields, the forms are optimised for small screens, and the leads are generally higher-quality thanks to the audience selection and optimisation already present on the ads.

> HOT TIP: If you're also a **Marketing Cloud** customer, ensure the sales process is in sync with all other customer messaging across channels like email, mobile, social with Journey Builder and manage your Facebook audiences with Advertising Studio.
<br/>

## Integration Requirements
* Salesforce Edition: Professional, Enterprise, Unlimited, Developer, Performance
* A Facebook for business account to link
* Lightning ready
* Native app
<br/>

## Alternatives: Zapier and Automate.io
In case you already make use of workflows to automate processes and connect third party apps, here are a couple of options that allow you to connect **Salesforce** and **Facebook Lead Ads**:
* [Integrate with Zapier](https://zapier.com/apps/facebook-lead-ads/integrations/salesforce)
* [Integrate with Automate.io](https://automate.io/integration/facebook-lead-ads/salesforce)

The advantage of creating workflows with these platforms - especially if you already have in-house automation specialists - is the freedom to create custom workflows that make sense for your organization.
The other side of the coin is the inability to leverage an out-of-the-box integration or get support for it, so we recommend this solution to companies who already well versed in Zapier or Automate.io and have the capacity to have one of the team build and maintain the automation.
<br/>

## Integration Details

### Download the app
Download and install [**Lead Capture for Sales Cloud** on appexchange](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000DrzmfUAB).

1. Click on **Install in production**
2. Confirm you're installing the package in the correct org, agree to the Terms and Conditions
3. Click on **Confirm and install**
4. Enter your login credentials
5. Select **Install for Admins Only**. Leave the other options as-is.
6. Click on **Install**. The package may take a few minutes to install.
7. Click **Done** to view the package in your org.

### Configure the app
Configure the Lead Capture for Sales Cloud Connected App so that pre-authorized users can access it. You only need to perform this step once.

1. In Setup, enter Connected Apps in the Quick Find box, and then click Manage Connected Apps
2. For the Salesforce Lead Capture connected app, click **Edit**
3. In the “OAuth policies” section, for Permitted Users, select Admin approved users are pre-authorized
4. Confirm the changes and then click **Save**

{:refdef: style="text-align: center;"}
![Facebook for business salesforce integration]({{ 'assets/img/2021-09-07-facebook-salesforce-01.jpg' | relative_url }})
{:refdef}

### Grant access to the app
Grant Access to Lead Capture for Sales Cloud to the users in your org who manage Facebook Lead Ad campaigns. The permission set grants access to the Lead Capture app, plus the ability to: create lead capture tasks, read and update leads, read and update the Facebook Lead ID custom field on leads.

1. In Setup, enter Users in the Quick Find box, and then click **Users**
2. From the list of users, click the username of the person who needs access to the app. In the example below, we’re granting access to a user named John Doe
3. Click Permission Set Assignments and then click Edit Assignments
4. Select the Salesforce Lead Capture permission set and then click Add
5. Click **Save**

{:refdef: style="text-align: center;"}
![Facebook for business salesforce integration]({{ 'assets/img/2021-09-07-facebook-salesforce-02.jpg' | relative_url }})
{:refdef}

> IMPORTANT: we recommend using [Firefox](https://www.mozilla.org/en-US/firefox/new/) for the *initial sync* as other browsers may show a "refused to connect" error in the iframe. When using Firefox it shows a button to **Open Site In New Window** which then allows the component to display the Lead Capture page properly. After that, you may continue to use your preferred browser.

<br/>

## Useful Resources
* [Facebook for Business - Lead Ads](https://www.facebook.com/business/ads/lead-ads)
* [Salesforce Lead Capture - appexchange](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3A00000DrzmfUAB)
