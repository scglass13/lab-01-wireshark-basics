# Home Lab Write-Up: Lab 01 - Wireshark basics

> 📅 Date: 03/17/2026  
> 🧪 Lab Type: Environment Setup / Attack-Defense Simulation   
> 🎯 Objective: The purpose of this lab is to gain practice in using Wireshark for traffic capture and analysis.
> 🗂️ Category: SOC
> ⏱️ Time Spent: ~X hours

---

## Lab Overview

*Write 3–5 sentences describing what this lab is about. What scenario or problem were you simulating? What does it help you practice as an analyst?*

> Example: "This lab simulates a basic attacker-victim network using two VirtualBox VMs — a Kali Linux attacker and a Windows 10 target. The goal was to practice detecting a port scan and reverse shell using Wireshark and Windows Event Logs. This mirrors a common early-stage intrusion scenario seen in SOC environments."

---

## Environment Setup

### Host Machine Specs
| Property | Details |
|----------|---------|
| OS | Ubuntu |
| RAM | 2 GB |
| CPU | 4 |
| Disk | 20 GB |

### Virtual Machines

| VM Name | OS | Role | RAM Allocated | Network Adapter |
|---------|----|------|---------------|-----------------|
|    lab01-Wireshark-basics     |  Ubuntu  |   user   |       16 GB        |         NAT        |
|         |    |      |               |                 |

### VirtualBox Network Configuration

*Describe how your VMs are networked together. This is important for reproducibility and shows you understand network segmentation.*

- **Network Mode Used:** NAT / NAT Network / Host-Only / Internal Network / Bridged
- **Reason for this choice:** *Why did you pick this network mode for this lab?*
- **IP Addresses:**
  - VM 1: 
  - VM 2: 

> 💡 Tip: For attack/defense labs, Host-Only or Internal Network keeps malicious traffic contained to your host machine. Always note this for safety and reproducibility.

### Snapshots Taken

| Snapshot Name | VM | Purpose |
|---------------|----|---------|
| Clean Baseline | | Taken before any changes |
|               |  |         |

---

## Tools & Software Used

| Tool | Version | Purpose |
|------|---------|---------|
|   Wireshark   |         |     Capture and analyze network traffic    |
|      |         |         |
|      |         |         |

---

## Lab Walkthrough

### Phase 1: Environment Setup

**Goal of this phase:**  
Get VM setup for the lab

**Steps taken:**

1. Create new VM with Ubuntu image
2. Allocate RAM and disk size
3. Set network adapter to NAT so traffic flows through the host
4. Install Ubuntu 22.04.5 LTS (Jammy Jellyfish)

**Commands used:**
```bash
# Paste commands here with brief inline comments
# Example:
# nmap -sV 192.168.56.101   # Service version scan against target VM
```

**Screenshot / Output:**  
*(Optional) Embed a screenshot or paste relevant terminal/log output.*  
`![Description](images/phase1-screenshot.png)`

**What happened / What I observed:**  
*Describe the result. What did you see? Did it behave as expected?*

---

### Phase 2: [Phase Title]

**Goal of this phase:**  


**Steps taken:**

1. 
2. 
3. 

**Commands used:**
```bash

```

**What happened / What I observed:**  


---

### Phase 3: [Phase Title]

**Goal of this phase:**  


**Steps taken:**

1. 
2. 
3. 

**Commands used:**
```bash

```

**What happened / What I observed:**  


---

## Detection & Analysis *(For Attack/Defense Labs)*

*Skip this section if this was a pure setup lab.*

### What Attack Activity Was Generated?

*List the attacker actions that would leave traces for a defender to find.*

- 
- 
- 

### Where Was It Detected?

| Evidence Type | Location | What It Showed |
|---------------|----------|----------------|
| Windows Event Log | Event Viewer / Security Log | |
| Network Traffic | Wireshark / pcap | |
| Process Activity | Task Manager / Sysmon | |

### Key IOCs (Indicators of Compromise)

| IOC Type | Value | Significance |
|----------|-------|--------------|
| IP Address | | |
| Port | | |
| Process Name | | |
| File Hash | | |

### MITRE ATT&CK Mapping

*Map what happened in the lab to real-world TTPs. Even one or two entries here is powerful for your portfolio.*

| Tactic | Technique | Technique ID | Observed In Lab |
|--------|-----------|--------------|-----------------|
| | | | |
| | | | |

> 🔗 Reference: [MITRE ATT&CK Framework](https://attack.mitre.org/)

---

## Mistakes & Troubleshooting

*Note anything that broke, confused you, or required extra research. This is one of the most valuable sections for demonstrating real analytical thinking.*

- **Problem:** 
  **Root Cause:** 
  **Fix:** 

- **Problem:** 
  **Root Cause:** 
  **Fix:** 

---

## Lessons Learned

*What did you actually take away from this lab? Be specific. Connect it to real SOC or CTI work.*

1. 
2. 
3. 


---

## How This Applies to SOC Work

*2–4 sentences connecting this lab to what an analyst does on the job. This is a key section for job applications.*

---

## If I Were to Repeat This Lab

*What would you do differently? What would you add? This shows a growth mindset and self-awareness.*

- 
- 

---

## References

- 
- 
- 

---

*Write-up by [Your Name] | [GitHub Profile Link]*
