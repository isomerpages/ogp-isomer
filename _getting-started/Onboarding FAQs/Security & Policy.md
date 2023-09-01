---
title: Security & Policy
permalink: /onboard-to-isomer/onboarding-faqs/security-and-policy/
description: ""
third_nav_title: Onboarding FAQs
---
##### How are sites being monitored? What do I do if my site goes down?

We us monitoring systems such as Pingdom and Uptime Robot on all Isomer sites. These systems send pings to your site every minute to ensure that it's running and responding properly.

If our monitoring systems detect that your site is down, the Isomer team immediately receives a phone call to rectify the issue. The team will also notify you through email, or in emergency cases, by phone.

You can visit [status.isomer.gov.sg](https://status.isomer.gov.sg/) to check the status of your sites, or subscribe to the RSS feeds.

##### How are account logs managed?

Accounts on isomer are managed by Github (note: Isomer subscribe to the free tier of Github). On Isomer Organisation, [we enforce all users to have their 2FA set up](https://docs.github.com/en/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization).

We do not monitor account log in behaviour on Isomer. Any abnormal log in will be handled at Github's level.

If you have any questions regarding how [Github keeps your account secure here.](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure)

##### Do I need to perform a CAGE scan?

By default, you don't have to. If you select Isomer as your hosting platform, you will be prompted that you're not required to perform cage scan. But if you do, you can specify this IP address **18.136.36.203.**

##### What is our RPO (Recovery Point Objective) and RTO (Recovery Time Objective)**

**RPO**: our backup job runs once a day

**RTO**: N/A - Isomer is dependent on other systems (AWS, Netlify, KeyCDN and GitHub), hence the service recovery time will be dependent on these external services

**What is our SLA?**

##### Will Isomer be onboarding to CAM?

Isomer currently does not have plans to onboard to CAM due to limitations in our technical setup. If you are in contact with a representative from the CAM team, please direct them to us.

##### Why is my IHP scan result not 100%?

The Isomer team is working closely with the CSA team, and there is assurance that all Isomer root domains are very much aligned with IHP. The Isomer team will be working with the relevant teams to seek alignment on DNSSEC and this can be ignored for now. IHP scan results should be focused on root domains (eg. [isomer.gov.sg](http://isomer.gov.sg/)) and not the www subdomains ([www.isomer.gov.sg](http://www.isomer.gov.sg/)) at the moment.

##### My Accessibility Scores on WOGAA are below 100%, how do I fix this to meet the Digital KPI requirements for reporting?

The Isomer team has obtained a waiver for Digital KPIs for all Isomer sites until end March 2023. Hence if your Isomer site does not meet the minimum score requirements for Accessibility and SEO scores, do report back that your site is an Isomer site and there is a waiver obtained until end March 2023.