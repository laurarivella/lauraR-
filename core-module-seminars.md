---
layout: page
title: "Core Module Seminars"
permalink: /core-module-seminars/
---

## Seminar 1 - 02/10/2020 - Shell Global Case Study (Security Threats)

We have looked at Shell Global and reviewed the security considerations for a company that size with branches across various continents. 

Task: Investigate the various security concerns this company has had, and might have in the future.

ICS architecture 
Industrial control system 
Categories of vulnerabilities are in scope and we are interested in:
	• Remote Code Execution
	• SQL injection vulnerabilities
	• Authentication or authorization flaws
	• Server-side code execution bugs
	• Encryption vulnerabilities

Task: Provide exemplars of how these concerns have been or can be dealt with by the company.  

2010 Data breach related to shell's activity in Nigeria.
Contact details of more than 170,000 Royal Dutch Shell employees and contractors have become public after a group claiming to be Shell staff concerned about the oil company's activities e-mailed them to eco and corporate activists.

Based on this example, what issues do you foresee as a Cyber Security professional if employed by multinational companies? How does this compare with issues faced by small and medium-sized companies? A unified approach to security.

2015 Shell Works with Yokogawa and Cisco on a Unified Cybersecurity Approach
The three companies will implement the joint SecurePlant initiative at about 50 Shell plants over the next three years to standardize cybersecurity measures for the global oil producer. Shell Oil Company has partnered with Cisco and Yokogawa Electric Corporation to increase its cybersecurity at plants around the world in an attempt to insulate themselves from “hackers intent on tampering with physical infrastructure.”
Shell plans on launching its comprehensive security program, SecurePlant system, at fifty locations around the world over the next three years. The system “is designed to eliminate the vulnerabilities that often arise when equipment, software and patches vary by location. By protecting plants with a program from a single team of vendors, Shell hopes to standardize security throughout its system and gain the ability to monitor threats in real time.”

	• Standardization to eliminate vulnerabilities arising when equipment, software and patches vary by location
	• Real time monitoring
	• Preventing physical infrastructure tampering

## Seminar 2 - 16/10/20 - Hospital diagnostics web-based information system Case Study (Threat Modelling Techniques) 

The problem: NHS Scotland has an xray service that stores exams digtally, to access to this service you need a referral from a doctor. We are focusing on PACS, Picture Archiving Communicatios System, which a national system accessible across all health boards by both radiology staff and clinicians.
The system integrates with Image Exchange Portal IEP for safe and secure transfer of imaging to specialized healthcare institutions around the UK.

The CIA triangle model (Confidentiality, Integrity, Availability) has to be applied to the system 

The UK national cyber security center 2019 has put together some security design principles:
	1. Establish the context, determine all system components and have no blind spots
	2. Make compromise difficult, penetration must be difficult
	3. Make disruption difficult, resilient to DoS attacks
	4. Make compromise detection easier
	5. Reduce the impact of compromise 

In our case the context is that we need to determine all system components, there must be no blind spots for PACS
	• Hardware
	• Software
	• Databases
	• Networks (is it cloud or not?)
	• People and procedures 

Network security
Hospitals don't store on the Cloud, Hospitals store in their own data centers
The data stays within a data center could be either local or a national center
Firewall implementation question? 
	• Firstly packet filtering, then all the ports to be blocked on the server, another firewall goes on the domain?
	• Each department is a separate segment with a separate WLAN, from each domain to the other get the firewalls to check the information 

Define and implement access level policies 

Software security
Identify what needs protection, from who and for what peros
Specify what the system must and must not do 


## Seminar 3 - 30/10/20 - UML Diagrams

We were asked to review the case study of Seminar 2 and think about UML diagrams to apply to it. 

To prepare for the seminar I researched what is being implemented nowadays as data structures in hospitals and what the regulations are. 

* Plethora of data coming from medical devices
* Growing reliance on cloud based IT infrastructure -> SADA's 2016 survey shift to the cloud for apps and tools https://sada.com/pdf/2016-digital-transformation-survey-infographic.pdf
* The UK's National Health Service (NHS) has given the green light for hospitals and social care agencies to move healthcare data to the public cloud.
* The UK government implemented a "cloud first" policy for public sector IT back in 2013. Services such as NHS Choices and NHS England's Code4Health project are already successfully using the cloud, ZDNet noted.
* Healthcare facilities and hospitals largely prefer on-premise data storage because allegedly they can have more control over the in-house data. 2018 NHS guidance on off shoring and use of public cloud services.
* Public cloud services, defined as cloud infrastructure provisioned for open use by the general public
* NHS and Social care providers may use cloud computing services for NHS data. Data must only be hosted within the European Economic Area (EEA), a country deemed adequate by the European Commission, or in the US where covered by Privacy Shield.
* The UK Government introduced a ‘cloud first’ policy for public sector IT in 2013. The use of cloud services was also endorsed in the National Information Board’s Personalised Health and Care 2020 framework, published in November 2014 https://www.gov.uk/government/publications/personalised-health-and-care-2020
* NHS and social care organisations can safely put health and care data, including non-personal data and confidential patient information, into the public cloud. Many NHS organisations and government departments have already made this decision based on risk management assessments and having put appropriate safeguards in place.
https://www.gov.uk/government/publications/data-security-and-protection-for-health-and-care-organisations
	
	Advantages:
	- Budget 
	- lower IT costs and the ability to develop, test and deploy services quickly without large capital expense
	- As more services for patients and staff move to the Internet and the need for better data interoperability increases
	
	However, there are some potential downsides to cloud services that need to be considered when making a risk-based decision:
	a) If your Internet access is disrupted or is unreliable, you may lose access to your data and services.
	b) change the way you budget for technology as cloud services usually operate on a pay-as-you-go (revenue) model 
	c) need to recruit the right capability to deliver and manage cloud services if your organisation has no prior experience 
	d) Some systems may not be compatible.
	e) Use of the cloud increases the portability of data, meaning data can be distributed across multiple devices both within and without the boundary of your organisation. The right cultural understanding and behaviours need to be in place to manage this portability appropriately mitigate any risks.

Key Challenges of on-premise data storage in healthcare
* Cannot afford to have downtimes
* Need for larger infrastructure
* As the amount of healthcare data to be stored and managed escalates, it demands more and more physical storage space. 
* Added maintenance costs
* Data security
The on-premise data infrastructure is connected to the local network, and hence one could consider this as the most secure option for maintaining critical patient data. The highly sensitive data is vulnerable to phishing attacks and malware attacks. In the due process of upkeeping the security of on-premise healthcare data with reliable anti-virus software, firewalls, encryption, and multi-factor authentication, one cannot ignore the loophole brought-in by the human factor. Since the on-premise data security depends largely on the IT resources, there is always room for error.

## Seminar 4 - 13/11/20 - Python programming and MySQL database management

Topics to be covered in this seminar: creating database and inserting data, altering existing database and updating data.  

Why is OOP more popular? 

An advantage of OOP is that your code resembles real-world examples (we think about objects all the time in the real world) and that code that belongs together is automatically grouped together.

Compare and contrast OOP with two other popular programming paradigms. 

Object-oriented programming (OOP) is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.
Java, C++, PHP

Functional vs Object-Oriented vs Procedural Programming https://medium.com/@LiliOuakninFelsen/functional-vs-object-oriented-vs-procedural-programming-a3d4585557f3

A programming paradigm is a style of programming, a way of thinking about software construction. 
A programming paradigm does not refer to a specific language but rather to a way to program, a methodology.
Programming paradigms are different approaches to the same problems. 

Procedural programming (PP) is also known as inline programming takes a top-down approach. 
It is about writing a list of instructions to tell the computer what to do step by step. It relies on procedures or routines.
C

Object-oriented programming (OOP) is about encapsulating data and behavior into objects. 
An OOP application will use a collection of objects which knows how to perform certain actions and how to interact with other elements of the application. 

Functional programming (FP) is about passing data from function to function to function to get a result. 
In FP, functions are treated as data, meaning you can use them as parameter.

https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/


Helpful code samples to see differences  https://academind.com/learn/javascript/functional-vs-oop-vs-procedural/

Procedural Programming
Procedural programming is all about writing “procedures”. You could kind of translate this with: “Write down the steps your program should execute in order”.
Here’s a brief example (dummy code):

const button = document.querySelector('button');

const doSomething = () => {
  // do something...
}

button.addEventListener('click', doSomething);

In this snippet, we have four steps:
	1. Get access to the first <button> element and store it in a constant (button)
	2. Define a function doSomething
	3. Add an event listener to the button and run doSomething upon a click event
	4. Execute any code inside of doSomething


Object-oriented Programming
If we would follow an object-oriented style, we could re-write (and arguably over-engineer this simple example) in the following way:

class InputArea {
  constructor() {
    this.button = document.querySelector('button');
    this.button.addEventListener('click', doSomething);
  }

  doSomething() {
    // do something
  }
}

new InputArea();

The idea behind object-oriented programming (OOP) is that you organize your code in classes/ objects (objects are based on classes).

Your data is stored in properties, your logic in methods. And properties and methods that work closely together live in the same class.

An advantage of OOP is that your code resembles real-world examples (we think about objects all the time in the real world) and that code that belongs together is automatically grouped together.

As a downside, you have the overhead of writing and using classes as well as maybe some issues with the this keyword in some cases. It is JavaScript after all.

Functional Programming
It’s simply another way of structuring and organizing your code.

Here’s the same example one more time - again over-engineered.

function findElementOnPage(elementTag) {
  return document.querySelector(elementTag);
}

function doSomething() {
  // do something
}

function connectInput() {
  const btn = findElementOnPage('button');
  btn.addEventListener('click', doSomething);
}

connectInput();

The idea behind functional programming is that you organize your code into multiple functions where each function works on its own.

## Seminar 5 - 20/11/20 - Implementation of security measures



## Seminar 6 - 4/12/20 - Django web applications


