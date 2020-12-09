---
layout: page
title: "Wiki"
permalink: /wiki/
---

## Wiki contributions

### RAID Memory

RAID (Redundant Array of Independent Disks) 

RAID is a way of storing the same data in different places on multiple hard disks, or solid-state drives, to protect data in the case of a drive failure. 
It works on having a large disk array comprising an arrangement of several independent disks that are organized to increase performance and improve reliability. Connelly & Begg, 2015) The use of multiple disks increases the mean time between failures and storing data redundantly increases fault tolerance. (Gillis et. al., 2020) 

RAID can be divided in different levels according to the way data is spread on the disks. Not all RAID levels have the goal of providing redundancy. 
Regardless of the way data is divided and spread, RAID appears to the Operating System as a single logical drive. 

The two main techniques employed by RAID are disk mirroring or disk striping.
Mirroring will copy identical data onto more than one drive. Striping partitions will help spread data over multiple disk drives. The stripes of all the disks are interleaved and addressed in order. (Gillis et. al., 2020) 

Samples of basic levels of RAID and techniques employed:
	• RAID 0 – striping
	• RAID 1 – mirroring
	• RAID 5 – striping with parity
	• RAID 6 – striping with double parity
	• RAID 10 – combining mirroring and striping

See Connelly & Begg, 2015 for in depth description of basic RAID levels.

It is worth noting that RAID is not a substitute for backups.

*References*
* Connolly, T. M. &  Begg, C. E. (2015) Database Systems. A Practical Approach to Design, Implementation and Management. Pearson Education/Addison Wesley. Available via the Vitalsource Bookshelf. 
* Gillis, A., Sullivan, E., Posey, B., Diamantis, C. & Yamamura, Y. (February 2020) RAID (redundant array of independent disks). Techtarget. Available from: https://searchstorage.techtarget.com/definition/RAID

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Web Application Firewall (WAF)

A Web Application Firewall (WAF) is an application firewall for HTTP applications. It performs a deep packet inspection of network traffic that occurs between the client and the server sides. By analyzing the data transferred between the client and the server, WAF can identify possible attacks even if the implementation may be missing such a detection. (Clincy & Shahriar, 2018) It applies a set of rules to an HTTP conversation. Generally, these rules cover common attacks such as Cross-site Scripting (XSS) and SQL Injection. While proxies generally protect clients, WAFs protect servers. A WAF is deployed to protect a specific web application or set of web applications. (OWASP) 

WAFs may come in the form of a server plugin, or filter, and may be customized to an application. The effort to perform this customization can be significant and needs to be maintained as the application is modified.
Nowadays, reliance on web applications is essential in our daily activities such as online banking, ticket booking, and sharing of data with others, not to mention e-sciences and e-health. These applications are a prime vector of attack for criminals and WAFs can help mitigate that threat. 

A number of WAFs are already available in the market. These include Barracuda, Bee Ware, Breach Security, Citrix, F5, Fortinet, and Imperva. One of the most common WAFs is Apache's Mod Security. (OWASP) 

*Reference list and further resources*
* Clincy, V. & Shahriar, H. (2018) 'Web Application Firewall: Network Security Models and Configuration', 2018 IEEE 42nd Annual Computer Software and Applications Conference (COMPSAC). Tokyo, Japan 23-27 July. IEEE. 835-836.
* OWASP Web Application Firewall. Available from: https://owasp.org/www-community/Web_Application_Firewall [Accessed 7 November 2020].
* Razzaq, A., Hur, A., Shahbaz, S., Masood, M. & Ahmad, H. F. (2013) 'Critical analysis on web application firewall solutions', 2013 IEEE Eleventh International Symposium on Autonomous Decentralized Systems (ISADS). Mexico City, Mexico, 6-8 March. IEEE.
