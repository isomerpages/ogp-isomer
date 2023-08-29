---
title: Isomer Tech Stack
permalink: /what-is-isomer/tech-stack/
description: ""
third_nav_title: For developers
---
[Copied from Before you onboard]


---

- **Isomer hosts all website content on Github – making them publicly available.** This includes the URL of your staging and production site. Isomer has [security measures](https://guide-cms.isomer.gov.sg/faq/security) to avoid unauthorized changes to your live site, and generally these links are hard to find unless specifically looked for. 
	- As of Q4 2023, Isomer will be by default releasing Privisation of Repos. This means that 
    
~~**Isomer uses [KeyCDN](https://www.keycdn.com/about) as our CDN provider** to make sure sites are always up. It also helps protect us against DDOS attacks. **(Is this necessary)**~~
    
Amplify is both hosting platform and CDN, cos it comes with an inbuilt CDN which is cloudfront


**All content hosted on Isomer is passed to ~Netlify~ Amplify** to be deployed as staging and production sites, which is how staging links are produced. **(Is this necessary)**
-> Isomer builds 2 copies of the website, based on a staging and master branch

"Connection is secure" how a website is judged to be secure if we have a valid SSL certificate (Which is an authority that determines that this site is who it claims to be)
-> Last time agencies had to do this themselves
We procure the cert for you as part of your hosting

We help to redirect HTTP to HTTPS traffic through our redirection server

We also help redirect the raw root domain to www cos of government DNS 




- 