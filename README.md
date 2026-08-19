# 🔎 Task 1 — Passive Reconnaissance Using theHarvester

![Cybersecurity](https://img.shields.io/badge/Field-Cybersecurity-blue)
![Tool](https://img.shields.io/badge/Tool-theHarvester-green)
![Version](https://img.shields.io/badge/Version-4.8.2-orange)
![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Information

| Information | Details |
|---|---|
| **Course** | NetworkWalks Cybersecurity Lab |
| **Week** | Week 2 |
| **Task** | W2-PM4-Week2 - Project Module4 - Footp with the Harvester v1. |
| **Activity** | Passive Reconnaissance |
| **Tool** | theHarvester |
| **Version** | 4.8.2 |
| **Operating System** | Kali Linux |
| **Target** | `networkwalks.com` |
| **Author** | Nura Muhammad Ibrahim |
| **Status** | ✅ Completed |

---

## 🎯 Objective

The objective of this practical is to perform **passive reconnaissance**
using theHarvester against the authorized training domain:

`networkwalks.com`

The purpose of this exercise is to understand how **OSINT
(Open-Source Intelligence)** techniques can be used to collect
publicly available information about a domain.

The activity is limited to information gathering and does not involve
exploitation or unauthorized access.

---

## 🛠️ Tool Used

### theHarvester

**theHarvester** is an OSINT and reconnaissance tool used during the
information-gathering phase of a cybersecurity assessment.

It can search multiple publicly available sources for information
related to a target domain.

Depending on the available sources, theHarvester can identify:

- IP addresses
- Hosts and subdomains
- Email addresses
- People
- Autonomous System Numbers (ASNs)
- Interesting URLs
- Other publicly available information

---

## 💻 Laboratory Environment

The practical was performed in the following environment:

```text
Operating System : Kali Linux
Tool              : theHarvester
Version           : 4.8.2
Target            : networkwalks.com
Activity          : Passive Reconnaissance
```

---

## ⌨️ Command Used

The following command was executed:

```bash
theHarvester -d networkwalks.com -l 50 -b all
```

### Command Breakdown

#### `-d networkwalks.com`

Specifies the domain that will be investigated.

#### `-l 50`

Requests a maximum of 50 results where supported by the selected
information source.

#### `-b all`

Instructs theHarvester to use all supported data sources available
in the installed version.

---

## 🔎 Methodology

The practical was completed using the following procedure:

1. Started Kali Linux.
2. Opened the terminal.
3. Started theHarvester.
4. Specified the authorized training domain.
5. Selected all available information sources.
6. Allowed the tool to perform passive information gathering.
7. Observed the information returned by the different sources.
8. Reviewed the results and source errors.
9. Captured a screenshot of the terminal output.
10. Documented the practical in this GitHub repository.

---

## 📊 Results

TheHarvester successfully started the reconnaissance process and
attempted to query multiple publicly available information sources.

The results demonstrated that reconnaissance data can include:

- IP addresses
- Hosts
- Subdomains
- Autonomous System Numbers (ASNs)
- Interesting URLs
- Other publicly indexed information

Some sources also reported errors, connection problems, or missing
API keys.

These messages are important to document because the availability of
information depends on the individual data source.

---

## 🔑 API Key Messages

During the scan, some providers reported messages such as:

```text
Missing API key
```

This does **not** automatically indicate a vulnerability.

It means that the particular information provider requires an API
credential before theHarvester can access that source.

Other sources may also return connection errors, HTTP errors, or no
results because of provider restrictions or availability.

---

## ⚠️ Important Observation

The results returned by reconnaissance tools should not automatically
be interpreted as security vulnerabilities.

For example:

- A missing API key does not indicate a vulnerability.
- An empty result does not mean that information does not exist.
- A discovered host does not automatically mean that the host is
  vulnerable.
- A discovered IP address does not automatically mean that it can be
  attacked.

Different OSINT sources have different databases, capabilities,
limitations, and availability.

Therefore, reconnaissance information should be carefully reviewed
and verified before making security conclusions.

---

# EVIDENCE 
![theHarvester Screenshot](images/harvester.png)

The following screenshot provides evidence of the practical execution.

### theHarvester Terminal Output

harvester.png

**Evidence file:** `hervester.png`

The screenshot shows the terminal execution of theHarvester and the
information returned during the passive reconnaissance exercise.

---

## 🧠 What I Learned

This practical helped me understand:

- What passive reconnaissance means.
- What OSINT means.
- How to use theHarvester.
- How to specify a target domain.
- How multiple information sources can be used for reconnaissance.
- How IP addresses can be identified.
- How hosts and subdomains can be discovered.
- What Autonomous System Numbers (ASNs) are.
- Why some information sources require API keys.
- Why reconnaissance results must be interpreted carefully.
- How to document cybersecurity activities professionally.

---

## 🔐 Security and Authorization

This practical was performed for **cybersecurity education and
training** against an authorized training target.

The activity was limited to passive information gathering.

No attempt was made to:

- Exploit vulnerabilities
- Guess passwords
- Bypass authentication
- Access private accounts
- Modify systems
- Disrupt services
- Gain unauthorized access

The purpose of the practical was to learn reconnaissance and OSINT
techniques in an authorized educational environment.

---

## 📝 Conclusion

This practical demonstrated how **theHarvester** can be used to
perform passive reconnaissance and collect publicly available
information from multiple OSINT sources.

The exercise also demonstrated that different information sources
have different capabilities, availability, API requirements, and
limitations.

Understanding these limitations is an important part of performing
professional cybersecurity reconnaissance.

The practical was successfully completed and documented with terminal
evidence.

---

## 📁 Project Structure

```text
Task-1-theHarvester/
│
├── README.md
└── hervester.png
```

---

## 📚 Skills Practiced

- Passive Reconnaissance
- OSINT
- Domain Enumeration
- Information Gathering
- theHarvester
- Linux Command Line
- Cybersecurity Documentation
- Security Awareness

---

## 👨‍💻 Author

**Nura Muhammad Ibrahim**

Cybersecurity Student  
**NetworkWalks**

---

## ✅ Task Status

### Task 1 — Passive Reconnaissance

**Status: COMPLETED**

---

⭐ This project is part of my cybersecurity learning journey with
NetworkWalks.How to document cybersecurity activities.
Why reconnaissance results should be verified.
## 🔐 Security and Authorization
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
## 📝 Conclusion
This practical demonstrated how theHarvester can be used for passive reconnaissance and OSINT information gathering.
The exercise also demonstrated that different information sources may have different capabilities, availability, and API requirements.
Understanding these limitations is an important part of professional cybersecurity reconnaissance.

## 📁 Project Structure
Task-1-theHarvester/
│
├── README.md
└── hervester.png
## 👨‍💻 Author
Nura Muhammad Ibrahim
Cybersecurity Student
NetworkWalks
## 📚 Skills Practiced
Passive Reconnaissance
OSINT
Domain Enumeration
Information Gathering
theHarvester
Linux Command Line
Cybersecurity Documentation
## ✅ Task Status
Task 1 — Completed
