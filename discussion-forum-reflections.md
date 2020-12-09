---
layout: page
title: "Discussion forum reflections"
permalink: /discussion-forum-reflections/
---

## Discussion forum 1 - The need for Cybersecurity

To keep exploring the theme of Seminar 1 on Shell Global, in this first Discussion forum I expanded on the reasons to invest in cybersecurity in the energy sector, choosing ENI as a company to analyze. ENI is an Italian energy company with a worldwide footprint. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Intro post - Cybersecurity in the energy sector

Network and information systems have been recognized as playing a vital role in society by supporting key sectors such as energy. (EU Parliament & Council of the European Union, 2019) ENI is an example of a company operating in the oil and gas industry in sixty-six countries worldwide. The nature of its business covers the whole energy lifecycle from extraction, to end user delivery. (ENI, 2019)

Investing in cybersecurity in the energy sector is vital to ensure business continuity at every organizational level. Preventing attacks on control systems is the main focus in this industry since it relies on these systems to manage refining operations at plant sites, to monitor and control pipelines remotely, and to support the business logistic chain. (Cardenas, 2019) Being a service provider also means storing customers’ data. Data from a 2019 survey show that six out of ten of large firms have identified breaches. (Government of the UK, 2019)

In addition to the financial cost associated with the breach itself, consequent loss of reputation is harder to quantify. (Poneman Institute, 2018)
ENI is a good example of strategic positioning and investment in cybersecurity. It has closely monitored political and legal developments, echoing policy recommendations, mainly European law and G7 meetings. (Comes, 2019)

 
*Reference list*
* Cardenas, A. (2019) Cyber-Physical Systems Security Knowledge Area Issue 1. The Cyber Security Body of Knowledge. Available from: https://www.cybok.org/media/downloads/Cyber Physical_Systems_Security_issue_1.0.pdf 
* Comes, E. (2019) Step change in Big Data security. In the complex world of cyberspace, it is becoming increasingly difficult to protect the enormous database of which we are all part. Available from: https://www.eni.com/en-IT/digital-transformation/cybersecurity-act.html 
* ENI (2019) Global Presence. Available from: https://www.eni.com/en-IT/global-presence.html 
* European Parliament & Council of the European Union (2019) Regulation (EU) 2019/881 of the European Parliament and of the Council of 17 April 2019 on ENISA (the European Union Agency for Cybersecurity) and on information and communications technology cybersecurity certification and repealing Regulation (EU) No 526/2013. (Cybersecurity Act) PE/86/2018/REV/1 Available from: https://eur-lex.europa.eu/eli/reg/2019/881/oj 
* Government of the United Kingdom, Department for Digital, Culture, Media & Sport. (2019) Cyber Security Breaches Survey 2019. Available from: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/875799/Cyber_Security_Breaches_Survey_2019_-_Main_Report_-_revised.pdf 
* Poneman Institute (2018) 2018 Cost of a Data Breach Study: Global overview. Available from: https://www.intlxsolutions.com/hubfs/2018_Global_Cost_of_a_Data_Breach_Report.pdf 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Summary post 

Based on peer responses and what we covered in the first three units, there are great points to address.

Firstly, addressing peer contributions and expanding on the original post, the energy sector is indeed part of what is considered critical infrastructure. Since networks and information systems play a vital role in society by supporting key sectors such as energy, finance, transport and health, a lack of vigilance affects society at large. (EU Parliament & Council of the European Union, 2019)

Arguably, there is a shared responsibility on both privately owned companies and governments to see that effective measures and resiliency are built into critical infrastructure. As we have discussed in Seminar one on Shell Global, problems may arise from something as deceivingly simple as unsynchronised software patching in different plants.

I agree that compliance with regulation does not necessarily mean adequate levels of security, having also experienced it in my work in a highly regulated sector. A great example is firewalls: a company may choose an expensive firewall to check it off an auditor’s list, but that does not necessarily make it the most adequate choice. (Anderson, 2008)

An interesting point about geopolitical motivations for attacks in the sector has been raised. The energy sector has always been geopolitically relevant as it is literally the fuel of a country’s economy and it is tied to its survival. This makes it a particularly tempting geopolitical and geoeconomic target. (Blackwill & Harris, 2016) Very recent examples of this being the Nord Stream 2 pipeline raising tensions between Europe, Russia and the U.S. (New York Times, 2020) and the latest acquisition by Chevron (Reed, 2020), which is bound to affect tensions in the Mediterranean and in the Middle East.
It is vital to highlight the layers of interconnectedness that affect current information systems. As we have explored in these first three units, a simple software bug can have much greater consequences than being just another hack in a statistic.

*Rererences*
* Anderson, R. (2008) Security Engineering: A Guide to Building Dependable Distributed Systems, 2nd ed. Indianapolis: Wiley Publishing. Available from: https://www.cl.cam.ac.uk/~rja14/book.html 
* Blackwell, R. D. & Harris, J. M. (2016) War by other means. Geoeconomics and statecraft. 1st ed. Cambridge: Harvard University Press.
* European Parliament & Council of the European Union (2019) Regulation (EU) 2019/881 of the European Parliament and of the Council of 17 April 2019 on ENISA (the European Union Agency for Cybersecurity) and on information and communications technology cybersecurity certification and repealing Regulation (EU) No 526/2013. (Cybersecurity Act) PE/86/2018/REV/1 Available from: https://eur-lex.europa.eu/eli/reg/2019/881/oj 
* Reed, S. (October 9, 2020) Chevron’s Purchase Could Unlock Israel’s Natural Gas Bonanza. NY Times. Available from: https://www.nytimes.com/2020/10/09/business/eastern-mediterranean-natural-gas-chevron.html 
* New York Times. (2020) Gazprom Topic. Available from: https://www.nytimes.com/topic/company/gazprom 


## Discussion forum 2 - Threat Mitigation 

In this Discussion forum we were asked to propose two kinds of mitigations to potential threats. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Intro post - Packet filtering and WAFs

We shall first consider packet filtering against Spoofing and DoS attacks. Packet filtering allows one to leverage the routers as protection since they are a useful choke point for network traffic. (Howard & LeBlanc, 2003)

Conceptually, positioning is crucial with this security solution both at the level of router and within the network architecture, it also doesn't require user knowledge or cooperation so there is less chance if user interference. The disadvantages of packet filtering are that the filtering rules can be hard to configure, hard to test and some protocols are not particularly suited to security via packet filtering. (Chapman & Zwicky, 1995)

Web Application Firewall can be used to defend against SQL injections. A WAF operating in front of the web servers is essentially a barrier put between the web application and the Internet which monitors the traffic which goes in and out of the web servers. (Russel, 2018)

Flexibility is an advantage in a WAF, e.g. the ease with which policy modification can be enforced. A disadvantage not to overlook is that it is blind to what happens inside the application by design as it only examines network traffic at its perimeter. Lastly, a firewall uses CPU cycles interpreting each packet and reviewing it, so there is the chance of network bottlenecking. (Zadeh & DeVolder, 2007)

*Reference list*
* Chapman, D. B. & Zwicky, E. D. (1995) Building internet firewalls. O'Reilly. Available from: http://web.deu.edu.tr/doc/oreily/networking/firewall/ch06_01.htm 
* Howard, M. & LeBlanc, D. (2003) Writing Secure Code. Redmond: Microsoft Press. Available via the Vitalsource Bookshelf. 
* Russell, R. (2018) Web Application Firewalls. O'Reilly Media, Inc. Available from: https://www.oreilly.com/library/view/web-application-firewalls/9781492032311/ 
* Zadeh, J., DeVolder, D. (2007) 'Software development and related security issues', Proceedings 2007 IEEE SoutheastCon. Richmond, VA, 22-25 March. IEEE. 746-749.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Summary post 

Thanks to all peer contributions, this discussion thread led to a well-rounded description of the advantages and disadvantages of packet filtering and WAFs, trying together concepts we have covered throughout the module units so far.  

Highlighting the shortcomings of WAFs allowed the discussion to zoom in on stateless and stateful WAFs, thereby reconstructing a history of their development, from first generation static rules to second generation stateful and agile WAFs capable of enriching collected data with a relevant context. (Liu, Miller, Lucas, Singh & Davis, 2006; Rapid7, N.D.)

Focusing on the three ways WAFs can be implemented offered a comprehensive view of advantages and disadvantages of these solutions and highlighted two key components of our work in cybersecurity: cost-benefit analysis and solution implementation.

In addition to bringing real world applicability to the conversation by discussing costs and benefits, the various implementation solutions served as a review of network security in all of its components.

A closer look at cloud based WAFs has been an excellent reminder of the potential security issues arising from third-party service providers, while at the same time allowing us to consider the advantages of using third-party providers, such as aiding compliance to data protection standards.

Delving deeper into cloud-based WAFs allows us to explore cutting edge solutions while attempting to answer the question of whether WAFs alone are enough to ensure web application security.

A distributed cloud solution has the major advantage of consolidating threat intelligence from multiple sources, therefore allowing one to construct new rules based on the new vulnerabilities and facilitating patching. (Pereira, 2018) The lower costs of a cloud-based WAF solution can unlock resources to invest in pairing WAFs to complementary security solutions, mitigating classic WAF shortcomings and creating an overall more solid security posture. Notable examples of auxiliary solutions are API gateways to inject and enforce uniform security rules, Runtime Application Self-Protection (RASP) to respond to runtime attacks, and Content Delivery Networks (CDNs) to help absorb DDoS attacks and minimize the performance impact on the website servers. (Hamilton, 2018)


*References*
* Hamilton, R. (April 24, 2018) Application Security - Securing Modern Web Applications: WAF Technology. Imperva. Available from: https://www.imperva.com/blog/securing-modern-web-applications-waf-technology/ 
* Liu, D., Miller, S., Lucas, M., Singh, A., Davis, J. & Henmi, A. (2006) ‘Defining a Firewall’, in: Hemni, A. (eds) Firewall Policies and VPN Configurations. Syngress. 73-122. 
* Pereira, F. (2019) Web Application Firewall. Oracle Cloud Infrastructure. Oracle. Available from: https://www.oracle.com/a/ocom/docs/cloud/waf-100.pdf 
* Rapid7 (N.D.) Fundamentals: Web Application Firewall (WAF) Available from: https://www.rapid7.com/fundamentals/web-application-firewalls/ 




