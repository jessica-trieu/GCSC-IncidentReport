<h3>Google Cybersecurity Certification Project: Use the NIST Cybersecurity Framework to respond to a security incident</h3>


**Scenario:**

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

-   A new firewall rule to limit the rate of incoming ICMP packets
-  Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
-  Network monitoring software to detect abnormal traffic patterns
-  An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

<h2>Incident Report Analysis</h2>
<h3>Summary</h3>
Today, the servers experienced a DDoS attack which compromised operations for 2 hours. After stopping the attack and restoring critical network operations, security analysts found that a malicious attacker exploited an unconfigured firewall and used it to flood the network with ICMP packets and overwhelm the servers.
<h3>Identify</h3>
The security team investigated the event and found that a malicious actor took advantage of an unconfigured firewall to launch an ICMP flood attack. Normal internal networks could not access server resources and affected operations. This could have impacted the small businesses that use this company to host their website and/or use it for social media marketing. The security team needed to secure the server and restore it to a functioning state. 
<h3>Protect</h3>
The unconfigured firewall needs to be addressed by setting new firewall rules that limit the rate of incoming ICMP packets. IPS should be installed to filter ICMP packets with abnormal characteristics.
<h3>Detect</h3>
Network monitoring software and IDS needs to be installed to monitor for unusual/suspicious traffic. The firewall also needs to be configured to verify source IP addresses to prevent incoming packets from spoofed IP addresses.
<h3>Respond</h3>
While an attack is occuring, the security team will isolate the affected systems and recover critical operations. We then need to analyze the logs for suspicious activity. We also need to inform management of the event and they will contact customers by email and mail to inform them of a possible data breach. If necessary, law enforcement will also be notified. 
<h3>Recover</h3>
The team would need to recover the network to normal operating levels. Non-critical functions should be stopped to allow for more internal network traffic flow. Next plan of action would be to restore critical operating services before non-critical functions can be allowed. Once the ICMP packet flood has stopped, non-critical functions can go back online.


