# NIST-Incident-Response

## Scenario

You are a cybersecurity analyst working for a multimedia company that provides web design, graphic design and social media marketing solutions for small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization's network services suddenly stopped responding due to a flood of incoming ICMP packets. Normal internal network traffic was unable to access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

Next, the company's cybersecurity team investigated the security incident. They discovered that a malicious actor had sent a flood of ICMP pings to the company's network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company's network through a distributed denial of service (DDoS) attack. 

To address this security issue, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets.
- Source IP address checking on the firewall to check for spoofed IP addresses in incoming ICMP packets.
- Network monitoring software to detect anomalous traffic patterns.
- An IDS/IPS system to filter some ICMP traffic based on suspicious characteristics.

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company's network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of this cybersecurity incident analysis and integrate your analysis into an overall security strategy:

- Identify security risks through regular audits of internal networks, systems, devices and access privileges to identify potential security gaps. 

- Protect internal assets by implementing policies, procedures, training and tools to help mitigate cybersecurity threats. 

- Detect potential security incidents and enhance monitoring capabilities to increase the speed and efficiency of detections. 

- Respond to contain, neutralize and analyze security incidents; implement security process improvements. 

- Recover normal operation of affected systems and restore data and/or system assets that have been affected by an incident. 
