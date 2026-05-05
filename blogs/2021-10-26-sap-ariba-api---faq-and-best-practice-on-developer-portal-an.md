---
title: "SAP Ariba API - FAQ and Best Practice on Developer portal and Gateway"
url: "https://community.sap.com/t5/spend-management-blog-posts-by-sap/sap-ariba-api-faq-and-best-practice-on-developer-portal-and-gateway/ba-p/13512565"
date: "Tue, 26 Oct 2021 22:25:59 GMT"
author: "yoswisnu"
feed_url: "https://community.sap.com/khhcw49343/rss/message?board.id=spend-management-blog-sap&message.id=1514"
---
<em>In this blog, I will be discussing the best practice and FAQ to the SAP Ariba API Developer portal and gateway. I will briefly lists the basic overview of SAP Ariba Developer Portal and lists several key process to be considered in order to avoid the common API issues related to SAP Ariba Developer Portal and API gateway itself.</em><br />
<br />
<span class="lia-unicode-emoji" title=":high_voltage:">⚡</span> If you are familiar with the Developer Portal or this blog is TL;DR, you can skip to the Access Token and Rate Limit validation section, which I think is a must read for API developers.<br />
<br />
I will divide this into Two sections: Developer portal and API Gateway.<br />
<h3>Developer portal:</h3><br />
<ul><br />
 	<li>As of October 2021, There are several SAP Ariba Developer portals divided into region: United States, Europe, Russia, China, Kingdom of Saudi Arabia, United Arab Emirates, Australia, and Japan. Customer access will depends on which API are going to used and also where the customer realm(s) resides.</li><br />
 	<li>Ariba Network APIs and CIG are only available from United States Developer Portal.</li><br />
 	<li>Customer access are given with registration to the respective portal, with Customers being classified as organizations within the Developer portal. There are two types of users in customer organization: Administrator and Developer users. Customer organization must have a minimum of one administrator user, but additional administrator and developer users are allowed. Typically, Designated Support Contact (DSC) will be assigned the role of administrator users.</li><br />
 	<li>Customer organization's administrator role is to maintain the users of their organization, along with finalizing any API application requests from the developer users by submitting the API application to SAP Ariba for approvals, and when approved, generating the client secret for API consumption. Administrator users can also delete existing application(s) within the customer organization.</li><br />
 	<li>Ariba Network API typically require ANID and the API use will involve configuration within the Ariba Network Admin page. APIs related to specific realms will either be auto approved or enabled by API support team. Some would need to be configured via Intelligent Configuration Manager (ICM) by customer realm administrator Prior to requesting specific API, customer organization must have their valid realm(s) listed with proper name and ANID in the Developer portal.</li><br />
</ul><br />
Frequently Asked Question on Developer Portal:<br />
<br />
<strong>Q:</strong>&nbsp;Can I hire an outside consultant to manage my organization/apps?<br />
<strong>A:</strong> Initially, only Designated Support Contact (DSC) can be set as administrator user of customer organization. After the administrator has been set up, they can invite members to customer organization and later designate the new member to be an administrator of customer organization. This decision is made within customer organization's discretion, not SAP Ariba. Non-administrator users (developers) within the organization can only create API applications and request for which API the application is for.&nbsp; Activities such as whitelisting IPs, requesting for API approvals, and secret key generation have to be done by the customer organization administrator users.<br />
<br />
<strong>Q:</strong>&nbsp;I'm just testing the API as a partner or consultant, can a customer's realm be added to my organization?<br />
<strong>A:</strong> No. API application(s) must be created within customer's organization. Access to the app can be shared by the administrator user of the organization to you as their partner or consultant. To their discretion, they can either add you to their organization as regular member, administrator, or simply sharing with you the secret key of the app. This is because the customer is in control of the API access to their realm(s) whether it is their test, production, or development realm.<br />
<br />
<strong>Q:</strong>&nbsp;Can we increase the API call limit for a specific application?<br />
<strong>A:</strong> The SAP Ariba Customer Support team does not have the ability to increase the rate limit for an API or application. As of 2023, most of SAP Ariba APIs are designed as a back-end integration, not a front end one. Data retrieval should be stored in your local database, not a direct call showing real time data on the fly and repeated for different users/UIs. You might have to spread your calls over some days or weeks if you have a lot of data, so plan for this accordingly.<br />
Depending upon your integration design, your account executive can reach out to the product owner and approval to increase call limit will be reviewed on a case by case basis. Rate limit existed to ensure that your nodes performance are not affected.<br />
<br />
<strong>Q:</strong> Should there be a different API application created for both test and production?<br />
<strong>A:</strong> Yes. There is a policy which we follow - One application for one realm and one API, which includes test realm. Every application is mapped for a particular API using the application apiKey. So to prevent an authorization error, use different applications for different API.<br />
<br />
<strong>Q:</strong> I completed my development in my test realm, can I migrate the API application for my development realm?<br />
<strong>A:</strong> No. Separate API Application must be created for your Production realm. The only changes to your development code would be the apiKey in the header portion of the API call and the key used to generate the Access Token. On Reporting API, if view being access require a custom field, recreation of the custom view will be required. This is because custom field name would differs between Test and Production realm.<br />
<br />
<strong>Q:</strong> Are we affected when there is a Certificate renewal on Developer Portal?<br />
<strong>A:</strong> Depending on your setup to consume the API, certificate update on Developer portal might affect your ability to consume SAP Ariba APIs.<br />
New certificate should be installed prior to the expiration date. One week prior to the update, certificate update notification will be shown upon connecting to Connect Portal and a link to the certificate will be provided. <strong>New in 2023: Please avoid doing certificate pinning as it will no longer supported</strong><br />
<h3>API Gateway:</h3><br />
<ul><br />
 	<li><strong>Access Token validation</strong><br />
Make sure that there is a process in place to handle Access Token validation, this include a process to generate new access token utilizing refresh token and a process that will store timestamp variable to check whether any given token needs to be refreshed prior to making the next/subsequent API call to the final end point. These two processes will avoid 401 error - unauthorized access.</li><br />
 	<li><strong>Rate Limit validation</strong><br />
A process should be made where rate limit available and remaining values(per second, minute, hour, and day) for any given API end points are stored in variables along with the timestamp of the last API call being made. These stored variables must be checked prior to making the next/subsequent API call to the specific end point to avoid 429 error - Rate Limit exceeded.<br />
<br />
<span class="lia-unicode-emoji" title=":high_voltage:">⚡</span>If you share the apiKey with other teams, these variables must also be updated by everyone who made calls to the API end points using the same apiKey, otherwise your stored variables are not reflecting the real remaining rate limit to the API end point in SAP Ariba API Gateway.</li><br />
 	<li><strong>Header size Limit</strong><br />
As of October, 2021, SAP Ariba API Gateway will only accept a maximum of 4KB or 32kb of data in the Request Header. Complying with this will avoid 502 error - Bad Gateway.Check this blog: <a href="https://blogs.sap.com/2021/03/03/facing-an-http-502-error-in-the-sap-ariba-apis-here-is-how-to-prevent-it/" target="_blank">How to prevent 502 error with SAP Ariba APIs</a>also this help manual on <a href="https://help.sap.com/viewer/368c481cd6954bdfa5d0435479fd4eaf/Cloud/en-US/4ec27d358d844c96b3ae11febd440eac.html" target="_blank">Tracing the execution of an integration flow</a> in SAP Cloud Integration</li><br />
</ul><br />
Frequently Asked Question on API Gateway:<br />
<br />
<strong>Q:</strong> Why do I get 403 error: Access Denied. Please contact your Organization admin?<br />
<strong>A:</strong> This error is returned because the application use the whitelisting IP feature that will block the use of the application unless it is coming from the specified IP addresses. Your organization admin must add the proper IP addresses on the whitelisting IP feature.<br />
<br />
<strong>Q:</strong> Why do I get&nbsp;400 error - grant type should not be null&nbsp;error?<br />
<strong>A:</strong> This error is due to the missing grant_type value of openapi_2lo that is required. This value should be spelled out in the body of the request: --data-urlencode 'grant_type=openapi_2lo'<br />
<br />
<strong>Q:</strong> Why do I get error: You cannot consume this service?<br />
<strong>A:</strong> The cause of this error is the API application attempted to access API end point(s) outside the API that the application was requested for. In other words, wrong apiKey.
