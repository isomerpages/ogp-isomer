---
title: Before you onboard
permalink: /onboard-to-isomer/getting-started/important-info/
description: ""
third_nav_title: Getting started
---
##### Read through this before deciding to onboard to Isomer
It's important to understand our limitations and ensure that we are a good fit for your use case. Here are some key points to consider:

~We do not provide pages specific restricted access but do note that all changes are tracked (even a single full stop you add to or remove from the page). That being said, do make changes to your site responsibly as all these changes are being tracked.~

~All isomer team members are admin users (with the ability to create new site, add and remove users, and grant permissions to users)~

### Technical considerations
> Should this be about Isomer tech stack? As well as type of websites + info level e.g. open closed or wtv?


- **Isomer hosts all website content on Github – making them publicly available.** This includes the URL of your staging and production site. Isomer has [security measures](https://guide-cms.isomer.gov.sg/faq/security) to avoid unauthorized changes to your live site, and generally these links are hard to find unless specifically looked for. 
(?Repo privatisation?)

- **All site edits and configurations must be done on IsomerCMS**, and we may drop support for websites that make edits through other means.
    
- **We limit each image or file size uploaded to 5MB** to ensure fast loading times, but you can upload larger files to [go.gov.sg](https://go.gov.sg/#/) and link to them on a page.

- **Isomer does not support any form of Javascript or animations.** We are designed for informational and static websites only.
		
- **Isomer follows government compliance regulations, and has placed restrictions on certain actions** such as disallowing the deletion of required pages (e.g. privacy, terms of use).
   
- **Isomer uses [KeyCDN](https://www.keycdn.com/about) as our CDN provider** to make sure sites are always up. It also helps protect us against DDOS attacks. (Is this necessary)
    
- **All content hosted on Isomer is passed to ~~Netlify~~ Amplify** to be deployed as staging and production sites, which is how staging links are produced. (Is this necessary)
    

### Support and cost
- Enquiries sent to [support@isomer.gov.sg](mailto:support@isomer.gov.sg) may take 3-5 working days to respond, but you can also refer to our guide for answers to common questions.
    
- Isomer is free to use, but agencies must bear the cost of the domain URL and custom SSL. Alternatively, you can onboard to the free Isomer provisioned 'LetsEncrypt' SSL cert, which lasts 3 months and auto-renews itself. (Do we enforce letsEncrypt now????)

- Public officers can add a vendor as a collaborator on IsomerCMS, but are responsible for their actions and usage cleanliness following the 60-day inactive rule. (??? I forgot what this clause is called)

If you have any doubts, please contact us at [support@isomer.gov.sg](mailto:support@isomer.gov.sg) for clarification.


---

[from FAQ] 

Isomer is an **informational static website builder** which means Isomer is unable to support any Javascripts or animation required on the website.
    

2. Upon onboarding, we strongly recommend you try out the CMS to see if it suits your use case.
    

3. Isomer can only able to accept files/image up to 5MB
    

4. All edits and configurations have to be done **on the CMS**. The only time Isomer users have to visit Github is to raise [pull requests](https://guide.isomer.gov.sg/guide/publish-your-changes).
    

5. Enquiries sent to support@isomer.gov.sg will take about 3-5 working days to respond as our team operates in a lean manner. You may also look at the guide on some of the FAQs to get answers to your enquiry.
    

6. Agencies hiring vendors to help with their website development must get a government email to access [Isomer](/isomer-announcements). FAQ [here](/faq/vendor-management).
    

7. The Isomer team has put in a place several restrictions on what you can or cannot do on the CMS concerning compliance. For example, if you wish to delete pages but you're not able to, that just means you're not allowed to delete those pages. A few examples are the privacy and terms of use page which you're not allowed to delete.
    

8. Onboarding to Isomer is free, the only items you are required to pay for are the domain URL and custom SSL.
    
	a. Alternatively, you may wish to onboard to the free Isomer provisioned '[LetsEncrypt](https://letsencrypt.org/about/)' SSL cert, it lasts 3 months and auto-renew itself at the end of every cycle, which means it last 'forever' along with your Isomer site.
        
    
	b. If you wish to use LetsEncrypt, you may let the team know when your site is ready to launch.
        
    

9. Isomer comes with a monitoring system to monitor whether the website is up or down using [uptime-robot](https://uptimerobot.com/).
    

10. Isomer is using [KeyCDN](https://www.keycdn.com/about) as our CDN provider to make sure sites are always up and it also serves as a protection to DDOS attack
    

11. All website contents of Isomer are hosted on [Github](https://github.com/about). This means, all contents and information uploaded by users will be available on the internet including the URL of your **staging and production site**. However, the chances of public users finding the content is relatively low and we have also put up security measures to avoid random users from pushing changes to your live site. You may read more about it [here](https://guide-cms.isomer.gov.sg/faq/security).‌
    

12. All the contents hosted on Isomer will be passed to [Netlify](https://www.netlify.com/) to be deployed as staging and production sites. Netlify acts as a virtual server to serve the content from Github to an informational site which is how staging links were being produced.
    

13. You may click [here](/publish-changes-and-site-launch/new-site-launch/what-to-expect-for-site-launch) to find out what should you expect for the site launch.
    

14. If you have any doubts, do refer to the guide or may choose to seek clarification with us at [support@isomer.gov.sg](mailto:%20support@isomer.gov.sg)