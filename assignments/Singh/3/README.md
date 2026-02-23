# Assignment 3: Reading Papers  
**CS 800 Research Methods, Spring 2026**  
**Name : Anurudh Singh**

This submission contains five papers from my research area (**Honeypots, Honeynets, and Deception-Based Defense**).   
Each paper includes:

- Keshav's 1st-pass summary (Problem, Approach, Contributions)  
- Full reference  
- DOI link  
- BibTeX entry  
- Screenshot of Page 1  
- Marked-up PDF with highlighted sections  

---
# Selected Papers
My research focuses on Honeypots, honeynets, and deception-based defense mechanisms. The following papers were selected because they provide foundational and practical insights into these areas.

## Paper 1: *Implementation of Honeynet and Honeypot in Network Infrastructure in Production Network*

**Reference:**  
Provos, N., & Holz, T. *Virtual Honeypots: From Botnet Tracking to Intrusion Detection*. Addison-Wesley Professional, 2007.

**Link:** http://arxiv.org/abs/2512.07180  
**DOI:** 10.48550/arXiv.2512.07180

```bibtex
@misc{evan2025implementationhoneynethoneypotnetwork,
      title={Implementation of Honeynet and Honeypot in Network Infrastructure in Production Network}, 
      author={Nawshad Ahmed Evan and Md Raihan Uddin},
      year={2025},
      eprint={2512.07180},
      archivePrefix={arXiv},
      primaryClass={cs.NI},
      url={https://arxiv.org/abs/2512.07180}, 
}
```

# 1st Pass (Keshav)

## Problem
- The paper addresses the increasing security challenges faced by network infrastructure in production environments due to the growing reliance on the internet and the expansion of the attack surface, particularly with the rise of IoT devices. 
- Traditional security measures like firewalls and intrusion detection systems are insufficient to counter modern cyber threats, such as unauthorized access, data theft, and Distributed Denial of Service (DDoS) attacks. 
- The study highlights the need for proactive security measures to detect, divert, and analyze attacker behavior to protect critical network resources. 


## Approach
- The paper proposes a hybrid network security model that integrates honeypots and honeynets with firewalls to enhance network security.
  The methodology involves:
### 1.	Honeypot and Honeynet Implementation:
- A honeynet is set up as a decoy network with devices mimicking real resources. 
- Two honeypots are deployed: one in front of the honeynet router to act as a fake web server and mislead attackers, and another behind the router to analyze attacker behavior and collect logs. 
### 2.	Simulation and Testing:
- The network topology is designed using the GNS3 open-source simulator, incorporating routers, switches, firewalls, and honeypots.
- Attacker behavior is simulated using tools like Kali Linux and Slowloris to generate random attacks and DDoS scenarios.
- Data is collected and analyzed using tools like Wireshark and KFSensor to understand attack patterns and trace attacker origins. 

## Contributions:
### 1. Hybrid Security Model: 
- The study introduces a three-layer security system combining honeypots, honeynets, and firewalls to provide advanced protection for production networks.
### 2. Proactive Threat Analysis: 
- The honeypots and honeynets are used to mislead attackers, collect their footprints, and analyze their behavior, providing valuable insights into attack patterns and vulnerabilities.
### 3. Real-Time Simulation: 
- The paper demonstrates the effectiveness of the proposed model through a virtual lab setup using GNS3 and VMWare, simulating real-world attack scenarios.
### 4. Enhanced Security Measures: 
- The study highlights the importance of integrating honeypots and honeynets with firewalls to provide additional layers of security, allowing security engineers to prepare for potential attacks.
### 5. Future Work: 
- The paper outlines plans to improve honeypot functionality, implement intrusion protection systems, and automate the integration of honeynets with production networks for enhanced security. 
   

## Screenshot (Page 1)
![Paper 1 Page 1](screenshots/paper1_page1.png)

## Marked-up PDF
[View Marked-up PDF](papers/paper1_implementation_honeynet.pdf)
