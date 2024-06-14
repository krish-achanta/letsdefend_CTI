# letsdefend_CTI
Q&amp;A for the Cyber Threat Intelligence

**CTI LIFECYCLE**

1. At what stage is big data created in cyber threat intelligence?
   ANS: Information Gathering
2. Which of the following is not among the questions that the organization should ask itself during the Planning and Direction phase?

A- Does the organization have a SOC team?
B- Has the organization been attacked before?
C- Do the attacks target the organization or the individuals?
D- Which EDR product is used in the organization?
   ANS: D
3. Tom, the cyber security analyst in the SOC team, wants to collect data from the major intelligence sources for his organization. Tom wants to use decoy systems to detect potential attackers. Which intelligence source is Tom trying to bring in?
  ANS: HoneyPot


**Types of Cyber ​​Threat Intelligence**

1. What type of intelligence is appropriate for a threat hunter in the organization?
   ANS: Operational Cyber Threat Intelligence 
2. What type of threat intelligence is appropriate for an employee working as an L1 analyst in the organization?
   ASN: Technical Cyber Threat Intelligence

**Determining the Attack Surface**

1. How many subdomains does "blueteam.training" have?
  ANS: 0
2. What is the service of the page builder on letsdefend.io/blog/ ?
   ANS: Webflow
3. Which of the following is not one of the subdomain discovery tools?

- Aquatone
- Httpx
- Sublist3r
- SecurityTrails
  ANS: httpx

4. Shodan can be used to detect IP blocks. (True or False)
   ANS: True


**Gathering Threat Intelligence**

1. What is the name of the data that identifies a threat, threat actor, malicious files, and plays an important role in threat intelligence?
   ANS: IOC (Indicators of Comprimise)
2. What is the filter that allows us to search the name of an organization on Shodan?
   ANS: Org
3. Which of the following is not among the messaging applications that threat actors frequently use?

- Telegram
- ICQ
- IRC
- Instagram DM
  ANS: Instagram DM
4. Practice question – Tom is a SOC analyst at “LetsDefend” organization. Tom received a notification stating that malware containing the name of his organization was uploaded to AnyRun. Find the IP address the malware is connecting to?

File MD5 Hash: f6517b0a49bb245e1983d77d2f5b2f98
  ANS: 192.168.50.104
5. How many processes does the malware with the MD5 Hash value "f6517b0a49bb245e1983d77d2f5b2f98" create?
  ANS: 2

**Threat Intelligence Data Interpretation**

1. What is the first data collected in threat intelligence called?
   ANS: Big Data

**Using Threat Intelligence**

1. What part of extended threat intelligence contains vulnerability management?
   ANS: EASM
2. If we receive an alarm from the threat intelligence product we use indicating that an IP address of our organization has been blacklisted. How should we handle the incident?

A- The reason why the IP address is blacklisted should be determined.
B- The reputation should be corrected by contacting the vendor whose IP address is blacklisted.
C- The IP address should be disabled.
D- A search should be made for the server to which the IP address points.
   ANS: C

3.Mike is a SOC analyst at LetsDefend. The organization received intelligence indicating that the "fac941eefc8571e51aef69289b5903c4" MD5 value of one of its systems was found in malicious data. Mike needs to isolate the device from the network. Can you help us, what is the hostname of this endpoint?

The user should go to the Endpoint Security page through the “Go There” option under the question, create a search, and find the hostname of the endpoint.
   ANS: TempHost


**Threat Intelligence and SOC Integration**

1. Which network security tool should be integrated to the threat intelligence products in order to prevent malicious inbound traffic coming into our organization in the fastest way?
   ANS: firewall
2. Which of the following cannot be integrated with threat intelligence?

- EDR
- SIEM
- SOAR
- Nmap
  ANS: Nmap
