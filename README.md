# Hello, I'm Mohamed Riyas J
<a href="www.linkedin.com/in/mohamed-riyas-9905a3326"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

[Brief Introduction]

I am graduate in M.A.M College of Engineering and Technology Anna University Chennai.

## Objective
[Provide Objective - Remove this afterwards]

My journey in Electronics and Communications Enineering has led me to develop a passion for cybersecurity, and I am now eager to transition into this field, specifically aiming to join a Security Operations Center (SOC) as a Tier 1 Analyst.

## Skills
[Provide skills and associated project. Make sure to hyperlink the project - Remove this afterwards]]

| Skill                                           | Associated Project         |
|-------------------------------------------------|----------------------------|
| SOC ( Security Operation Center                 | SIEM, TIPs, EDR            |
| SIEM Implementation and Log Analysis            | Splunk, Microsoft Sentinel |
| EDR (Endpoint Detection & Response)             | CrowdStrike, Carbon Black  |
| Malware Analysis                                | VirusTotal, McAfee         |
| SOAR Automation                                 | Palo Alto Cortex XSOAR     | 
| Phishing Email Investigation                    | Cofense, HoxHunt           |

## Tools
[Provide tools and break them down into categories. Use ChatGPT to help create the link - Remove this afterwards]]

### Network
<p align="center">
  <a href="#zeek-details">
    <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" width="180"/>
  </a>
</p>

---

## 🧠 Zeek Details <a id="zeek-details"></a>

 What is Zeek?
Zeek (formerly known as Bro) is an open-source network security monitoring tool. It's not like Wireshark that captures everything, and it’s not a firewall that blocks stuff. Zeek just watches the traffic silently and logs what's happening — HTTP, DNS, SSH, FTP, malware activity, etc.

Think of Zeek as a smart CCTV for your network.

🧠 Core Concept of Zeek:
1. Network Traffic Monitoring
Zeek sniffs packets on the network (using something like pcap), and instead of storing all raw packets, it converts it into logs that are easy to analyze.

Example:
If someone visits a website → Zeek logs it into http.log.
If someone does DNS queries → dns.log.
SSH login attempts? → ssh.log.

2. Event-Driven Scripting
Zeek uses its own scripting language. It works based on events like:

A new connection starts → trigger connection_established

An HTTP request is sent → trigger http_request

A file is downloaded → trigger file_downloaded

You can write custom detections using this logic.

3. Log Files = The Goldmine
After Zeek runs, it generates log files like:


Log File	What It Tracks
conn.log	All TCP/UDP connections
http.log	HTTP requests and responses
dns.log	DNS queries
ssh.log	SSH login attempts
weird.log	Suspicious or unexpected behavior
notice.log	Custom alerts (like potential threats)
These logs help in forensics, incident response, and threat hunting.

4. Passive, Not Active
Zeek doesn’t block or interfere with the traffic. It just monitors silently like a ninja 🥷

🔧 Example Use Case:
Imagine you’re doing a pentest:

Victim machine: 192.168.1.10

Attacker: 192.168.1.5

Zeek is running in between on a defensive VM

You start a DoS or exploit from attacker → Zeek logs all the suspicious traffic.
You later check conn.log, dns.log, notice.log etc., to see how the attack happened.

⚡ Why Zeek is Powerful:
Lightweight but powerful

Custom scripts

Works great with other tools like ELK, Splunk, or SIEMs

Real-time alerting possible

If you want, I can also help you write a basic Zeek script or show how to analyze logs after an attack. Just tell me what vibe you’re going for bro 😎




### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Velociraptor-4B275F?&style=for-the-badge&logo=Velociraptor&logoColor=white" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
</div>



## Certifications
[Provide certifications that you have obtained. Use ChatGPT to help create the link - Remove this afterwards]]
<div>
<img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-Network%2B-007ACC?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-A%2B-4D4D4D?&style=for-the-badge&logo=CompTIA&logoColor=white" />
<img src="https://img.shields.io/badge/-CDSA-006400?&style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/-CCD-000080?&style=for-the-badge&logoColor=white" />
</div>

## Projects
- Detection Lab
- SOC Automation Project
- sec
- fggg
- gggg

- gg
- g
- gg

- g
- g
- g
- g
- g

- g
- g
- g
- 
