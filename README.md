# Task 1 — Passive Reconnaissance Using theHarvester

## 📌 Project Information

| Item | Details |
|---|---|
| Course | NetworkWalks Cybersecurity Lab |
| Task | Task 1 |
| Activity | Passive Reconnaissance |
| Tool | theHarvester |
| Version | 4.8.2 |
| Operating System | Kali Linux |
| Target | networkwalks.com |
| Author | Muhammad Ibrahim |

---

## 🎯 Objective

The objective of this practical is to perform passive reconnaissance
using theHarvester against the authorized training domain
`networkwalks.com`.

The purpose is to learn how publicly available information can be
collected using OSINT (Open-Source Intelligence) techniques.

---

## 🛠️ Tool Used

### theHarvester

theHarvester is an OSINT and reconnaissance tool used during the
information-gathering phase of a cybersecurity assessment.

It can collect information such as:

- IP addresses
- Hosts and subdomains
- Email addresses
- People
- Autonomous System Numbers (ASNs)
- Interesting URLs

---

## 💻 Environment

```text
Operating System: Kali Linux
Tool: theHarvester
Version: 4.8.2
Target: networkwalks.com

⌨️ Command Used
theHarvester -d networkwalks.com -l 50 -b all
Command Explanation
-d networkwalks.com
Specifies the target domain.
-l 50
Limits the requested results to 50 where supported by the selected information source.
-b all
Instructs theHarvester to use all supported information sources available in the installed version.

🔎 Methodology
The following steps were performed:
Opened Kali Linux.
Opened the terminal.
Started theHarvester.
Specified the authorized target domain.
Selected all available information sources.
Allowed the tool to perform passive information gathering.
Observed the returned results.
Captured a screenshot of the terminal output.
Documented the results in this project.
📊 Results
TheHarvester queried multiple publicly available information sources.
The results included reconnaissance information such as:
IP addresses
Hosts
Subdomains
Autonomous System Numbers (ASNs)
Interesting URLs
Some information sources also reported errors or missing API keys.
These messages do not necessarily indicate a security vulnerability. Some theHarvester providers require separate API credentials or may restrict automated requests.

⚠️ Important Observation
A missing API key means that a particular information source could not be queried without the required credentials.
Similarly, an empty result from one source does not necessarily mean that the information does not exist.
Different OSINT sources have different databases, capabilities, and availability.
Therefore, reconnaissance results should be interpreted carefully and verified before making security conclusions.
📷 Evidence
The following screenshot provides evidence of the practical:
�
🧠 What I Learned
Through this practical, I learned:
The concept of passive reconnaissance.
How to use theHarvester.
How to specify a target domain.
How OSINT sources can provide reconnaissance information.
How IP addresses and hosts can be identified.
The purpose of ASNs in reconnaissance.
Why some OSINT sources require API keys.
How to document cybersecurity activities.
Why reconnaissance results should be verified.
🔐 Security and Authorization
This practical was performed for cybersecurity education and training against an authorized training target.
The activity was limited to passive information gathering.
No attempt was made to:
Exploit vulnerabilities
Guess passwords
Bypass authentication
Access private accounts
Modify systems
Disrupt services
Gain unauthorized access
📝 Conclusion
This practical demonstrated how theHarvester can be used for passive reconnaissance and OSINT information gathering.
The exercise also demonstrated that different information sources may have different capabilities, availability, and API requirements.
Understanding these limitations is an important part of professional cybersecurity reconnaissance.

📁 Project Structure
Task-1-theHarvester/
│
├── README.md
└── hervester.png
👨‍💻 Author
Muhammad Ibrahim
Cybersecurity Student
NetworkWalks
📚 Skills Practiced
Passive Reconnaissance
OSINT
Domain Enumeration
Information Gathering
theHarvester
Linux Command Line
Cybersecurity Documentation
✅ Task Status
Task 1 — Completed
