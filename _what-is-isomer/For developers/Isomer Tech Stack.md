---
title: Isomer Tech Stack
permalink: /what-is-isomer/tech-stack/
description: ""
third_nav_title: For developers
---
[Copied from Before you onboard]


---

- **Isomer hosts all website content on Github.** This includes the URL of your staging and production site. Isomer has [security measures](https://guide-cms.isomer.gov.sg/faq/security) to avoid unauthorized changes to your live site, and generally these links are hard to find unless specifically looked for.
	- As of Q4 2023, Isomer will be by default releasing Privisation of Repos. This means that 
	- **Isomer builds 2 copies of your website, based on a staging and master branch.** These links are publically available, though hard to find


- As of 2023, Isomer websites use [Amplify](https://aws.amazon.com/amplify/) as both our hosting platform and CDN. Amplify comes with an inbuilt CDN, CloudFront. A CDN helps to make sure sites are always up and also helps protect us against DDOS attacks.

- Isomer uses LetsEncrypt for our SSL certs. We procure this cert on behalf of all Isomer websites as part of our hosting services.
"Connection is secure" how a website is judged to be secure if we have a valid SSL certificate (Which is an authority that determines that this site is who it claims to be)
-> Last time agencies had to do this themselves
We procure the cert for you as part of your hosting

We help to redirect HTTP to HTTPS traffic through our redirection server

~~We also help redirect the raw root domain to www cos of government DNS 
~~



-