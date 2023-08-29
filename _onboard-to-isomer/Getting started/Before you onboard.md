---
title: Before you onboard
permalink: /onboard-to-isomer/getting-started/important-info/
description: ""
third_nav_title: Getting started
---
##### Read through this before deciding to onboard to Isomer
It's important to understand our limitations and ensure that we are a good fit for your use case. You can also [read our Onboarding FAQs]() for more information. 

Here are some key points to consider:


### What types of websites are suitable for Isomer?

##### **Isomer best caters to static websites. Characteristics of such websites include:**
    
✅ Content shown on the website is fixed and does not change unless the website owner manually updates it.  
✅ Contains unclassified content that is meant for public consumption.
    
**Common use cases include:**    
✅ **Informational websites:** Provide information to the public, such as information about government services, policies, and regulations using text and media such as images.   
✅ **Campaign websites:** Promote specific initiatives or programs.  
✅ **Corporate websites:** Provides information on an agency
    
Examples include: [towardszerowaste.gov.sg](https://www.towardszerowaste.gov.sg/), boa.gov.sg, switchsg.org
    
##### **Characteristics of websites we do NOT cater for include:**
    
❌ User authentification where users are to “log in” to the service  
❌ Dynamic content where users can interact with a website to get personalised information  
❌ Native interactive elements such as calculators or maps (Note that some such services can be embedded onto Isomer websites, such as data.gov.sg or CheckFirst.gov.sg)  
❌ Calls to a database to store and retrieve information  
❌ Server-side processing???*
    
**Common use cases with these chracteristics include:**  
❌ **Web applications:** Dynamic websites that allow users to interact with the website and perform specific tasks, such as filling out forms or making payments.  
❌ **E-commerce websites:** Allow users to purchase goods or services online. This includes selling products or services, such as park passes or event tickets.  
❌ **Data visualization platforms:** Allow users to explore and interact with data in a visual way using maps or charts.
    
Examples include: cpf.gov.sg, iras.gov.sg



### General considerations

- **Isomer does not support any form of Javascript or animations.**&nbsp;We are designed for informational and static websites only.
- **We limit each image or file size uploaded to IsomerCMS to 5MB** to ensure fast loading times, but you can upload larger files to [go.gov.sg](https://go.gov.sg/#/) and link to them on a page.
- Agencies can only use [IsomerCMS](cms.isomer.gov.sg) to edit their websites. Users only have to visit Github is to raise&nbsp;a [pull request](https://guide.isomer.gov.sg/guide/publish-your-changes).
- We can create subdomain sites if requested. Noted, we can create a site for you as you've shared that the site will be hosted on the domain that you've share.
    

### Support and cost 
- The Isomer platform and service is free for Public Officers to use, but in order to launch their site, **agencies must bear the cost of the domain URL**, which you can procure from IT Service Management (ITSM).

- Isomer allows Public officers to add vendors as collaborators to their website, but **agencies are responsible for all communication with and actions of their vendors.** The Isomer team will not directly liaise with any vendors. [View our FAQs on vendor management]()

- **Agencies are responsible for migrating any existing content from a previous website** to their Isomer website. The Isomer team cannot provide this service for you.

- Isomer Support is able to help with technical assistance of the CMS and simple markdown or HTML debugging, **but does not entertain debugging requests for complex customisations of the Isomer template CSS.**

- Each website should have at least 2 Public Officers added to it. To publish changes to your website, a colleague needs to approve your changes. The Isomer team does not do this approval for you. [Learn more about review requests]()


### Compliance
- **Agencies do not need to be responsible for any IM8 clauses. By using Isomer, your site is _by default compliant_ to all applicable IM8 clauses.** The Isomer Team manages all security centrally, including any security testing (i.e. VAPT etc) and audits/tests. In the event that any IM8-related queries come along, we will sort it out separately with the IM8 team. 
You can reach out to [Isomer Support](mailto:%20support@isomer.gov.sg) for further clarification on specific clauses.
- Internal Risk Assessment Checklist is not applicable to Isomer (?) as part of the security review for compliance with IM8

- **Isomer has placed restrictions on certain actions to follow government compliance regulations,** such as disallowing the deletion of required pages (e.g. privacy, terms of use).


View the Isomer Tech Stack

Still not sure about your use case? Ask us at [support@isomer.gov.sg](mailto:%20support@isomer.gov.sg)




---


<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# [from FAQ] 

1. Isomer is an **informational static website builder** which means Isomer is unable to support any Javascripts or animation required on the website.
    

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