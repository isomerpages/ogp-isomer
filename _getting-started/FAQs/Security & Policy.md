---
title: Security & Policy
permalink: /getting-started/faqs/security-and-policy/
description: ""
third_nav_title: FAQs
---
#### How are sites being monitored? What do I do if my site goes down?

We use monitoring systems such as Pingdom and Uptime Robot on all Isomer sites. These systems send pings to your site every minute to ensure that it's running and responding properly.

If our monitoring systems detect that your site is down, the Isomer team is immediately informed. We will then assess the nature of the situation and act accordingly. You will be notified by email, or in emergency situations, by phone.

You can visit [status.isomer.gov.sg](https://status.isomer.gov.sg/) to check the status of your site.


#### What is our Recovery Point Objective (RPO) and Recovery Time Objective(RTO)?

**RPO**: Our backup job runs once a day   
**RTO**: N/A - Isomer is dependent on other systems (AWS, Netlify, KeyCDN and GitHub). The service recovery time will depend on these external services.

#### What is our service level agreement (SLA)?

<table>
<thead>
  <tr>
    <th>Severity Level</th>
    <th>Definition</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>- A complete unavailability of the website<br>- Security issues, or problems severely impacting the operation of the website<br>- Defacement affecting the website, resulting in negative image or adverse impact on the reputation of the Agency</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Problems which moderately impact the operation of the website</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Problems which have minimal or no impact on the operation of the website</td>
  </tr>
</tbody>
</table>

<br>

|Severity Level|Acknowledgement Time|Status Reporting|Resolution Time|
|-|-|-|-|
|1|Within **60 minutes** of notification|**Every 2 hours** till completion of resolution|Within **24 hours**|
|2|Within **60 minutes** of notification|**Daily** till completion of resolution|Within **3 working days**|
|3|Within **60 minutes** of notification|**Weekly** till completion of resolution|Within **5 working days**|

#### Do accounts have MFA?
All IsomerCMS accounts use an email OTP sent to the email you log in with.

#### Why is my IHP scan result not 100%?
The Isomer team is working closely with the CSA team, and there is assurance that all Isomer root domains are very much aligned with IHP. The Isomer team will be working with the relevant teams to seek alignment on DNSSEC and this can be ignored for now. IHP scan results should be focused on root domains (eg. [isomer.gov.sg](http://isomer.gov.sg/)) and not the www subdomains ([www.isomer.gov.sg](http://www.isomer.gov.sg/)) at the moment.

#### Do I need to perform a CAGE scan?
If you choose Isomer as your hosting platform, you will be informed that a cage scan is not required. However, if you wish to perform one, you may specify the IP address as 18.136.36.203.

#### Will Isomer be onboarding to CAM?
Isomer currently does not have plans to onboard to CAM due to limitations in our technical setup. If you are in contact with a representative from the CAM team, please direct them to us.