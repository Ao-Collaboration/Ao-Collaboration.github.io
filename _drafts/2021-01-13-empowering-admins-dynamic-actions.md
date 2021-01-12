---
layout: post
title: Empowering Admins | Dynamic Actions
subtitle: All you need to know about Salesforce Dynamic Actions and how to use them.
cover-img: assets/img/Empowering-Admins-CoverV2.jpg
thumbnail-img: assets/img/2021-01-13-dynamic-actions-thumb.png
share-img: assets/img/2021-01-13-dynamic-actions-share.jpg
tags: [Empowering Admins, Guides, Lightning]
---

After discussing the ever so important (and exciting) Dynamic Forms [in our previous article](https://aocollab.tech/2020-12-16-empowering-admins-dynamic-forms/) it was only natural to continue our **Empowering Admins** series with a closer look at Dynamic Actions.

## What exactly are Dynamic Actions?
With Dynamic Actions, you can now choose which actions appear in the **Highlights Panel** on the Object's record page, based on specific conditions that you will be able to determine. As the name similarity suggests you get best results combining the use of Dynamic Actions and Dynamic Forms, allowing for a streamlined and clean experience to all your users.

## Requirements and Limitations
* Available in: Lightning Experience
* Currently available as Non-GA preview (just like a Beta version) in Summer ’20 release
* Currently available only for desktop
* From [Winter ‘21 release](https://releasenotes.docs.salesforce.com/en-us/winter21/release-notes/rn_lex_dynamic_actions_highlights_panel.htm), Dynamic Actions are beta for mobile.
* Dynamic Actions for custom objects are GA on Desktop and Beta for Mobile. Dynamic Actions for supported Standard objects are Beta on Desktop. 

## Benefits at a Glance
* Reduces number of Pages Layouts needed to cater to different users
* Reduces clutter in the Highlights Panel
* Uses a single assignment model for the Lightning page instead of the dual model of assigning a Lightning page and a Page Layout
* Manages actions in the Lightning App Builder without touching the Page Layout editor
* Improved UX/UI with less information clutter

## Enabling Dynamic Actions
1. Go to **Setup**
2. Find **Object Manager** from the Quick Find box
3. Go to **Opportunity**, then **Lightning Record Pages**
4. Click on the **Opportunity Record Page** and then on **Edit**
5. Select **Enable Dynamic Actions (Beta, desktop only)** in the properties pane, as shown in the screenshot
6. **Save**

![Enable Dynamic Actions](https://aocollab.tech/assets/img/2021-01-13-enable-dynamic-actions-1.png)

Once Dynamic Actions are enabled, the actions that are added to the record page layout in setup are no longer applicable. They are now controlled from Lightning App Builder where you can add, reorder, and/or remove actions with a modern UI and a live preview. 

The introduction of Dynamic Actions has also improved the experience with Cases (Dynamic Actions in Winter ’21 are adding support for Cases). You can now add them to the Highlight Panel there, and also have the modal functionality whereas beforehand you couldn't - it was only possible with different workarounds such as disabling Feed tracking for Case object, or creating a Button.

## Dynamic Actions in action

Salesforce has created a neat video that includes what we described in the **Enabling Dynamic Actions** above, plus a step by step on how to use them.
Rather than giving you a lengthy ordered list with screenshots, we figured it was more effective to just share their video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/AE1J5JSdpdc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Useful Resources
* [Learn MOAR: Try Dynamic Actions in App Builder with the Summer ’20 Release](https://admin.salesforce.com/blog/2020/try-dynamic-actions-in-app-builder-with-the-summer-20-release)
* [Trailblazer Community: Dynamic Forms and Actions](https://trailblazers.salesforce.com/_ui/core/chatter/groups/GroupProfilePage?emkind=chatterGroupMembership&emtm=1587493482205&fromEmail=1&g=0F93A000000TyRh&s1ext=0&s1nid=0DB30000000072L&s1oid=00D300000000iTz&s1uid=0053000000CU5hm)
* [Salesforce Dynamic Actions - How Salesforce Administrators Can Easily Control Visibility of Actions](https://youtu.be/AE1J5JSdpdc)
* [Trail: Empower Your Users with Quick Actions](https://trailhead.salesforce.com/en/content/learn/modules/lex_customization/lex_customization_actions)
* [Release Notes](https://releasenotes.docs.salesforce.com/en-us/summer20/release-notes/rn_lex_dynamic_actions.htm)
 
