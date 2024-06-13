[Scenario](#Scenario)

[Incident Report Analysis](#Response)

# incident_report_analysis_project
Analyzing a situation and creating a incident report using the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF).

# Scenario:

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 

A new firewall rule to limit the rate of incoming ICMP packets

Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

Network monitoring software to detect abnormal traffic patterns

An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy.

# Response:

|    NIST CSF Framework      |          |
|----------------------------|----------|
| Summary  | The organization experienced a security incident today when network services suddenly stopped responding. The event caused normal internal network traffic to come to a stop since no network resources could be accessed. The security team found it to be caused by a type of distributed denial of service attack (DDoS). This type of attack is called an ICMP flood attack which is evident by the flood of ICMP packets found by the team. The incident management team responded by blocking any more ICMP packets and stopping all non-critical network services to restore the critical network services.   |
| Identify | The security event was caused by a threat actor or malicious group that targeted the organization with an ICMP flood attack. The entire internal network was targeted by this attack which prevented critical network resources from being accessed. The root cause was an unconfigured firewall that allowed a flood of ICMP pings into the network.   |
| Protect  | To protect the network more policies were implemented such as a new firewall rule to limit the rate of incoming ICMP packets. In addition, the security team will add new software and an IDS/IPS system to detect and filter abnormal traffic.   |
| Detect   | The security team has configured source IP address verification on the firewall to combat IP spoofing when receiving future ICMP packets and utilized network monitoring software to watch out for abnormal traffic patterns. These new monitoring procedures will increase the speed and efficiency of detections.  |
| Respond  | When addressing future security incidents, the team will work to restore any disrupted critical systems. Doing this will require the team to isolate all affected components and stop any non-critical network services to bring back critical network services. Next, the team will use tolls to analyze logs to check for abnormal traffic and activity. Communication will also be a priority for the team so they will report all incidents and findings to the appropriate figures.   |
| Recover  | When recovering from a DDoS attack the security team's top priority is to restore critical network services back to a functional state. Stricter firewall rules and procedures will be used in the future to block incoming ICMP flood attacks. Then once the ICMP packets have timed out, all network systems and services can be put back online.   |
