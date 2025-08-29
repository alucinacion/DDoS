# DDoS coded by github.com/alucinacion

Enjoy this free version /v1.0

#  DDoS Attack Simulation using User Agents 
This repository contains a **Proof of Concept (PoC)** for simulating a **Distributed Denial of Service (DDoS)** attack by leveraging multiple **User Agents**. This PoC demonstrates how an attacker can flood a target web server with HTTP requests using a variety of User Agents, making it difficult to differentiate between real and malicious traffic.

##  Disclaimer 
This project is intended for **educational** and **research** purposes **only**. The goal is to raise awareness of DDoS vulnerabilities and to help security professionals test and improve the resilience of their systems. **Unauthorized use against live or production systems is illegal and unethical.** Always ensure you have explicit permission before testing.

##  Features
- Simulates a **DDoS attack** using randomized **User Agents** to mimic legitimate traffic.
- Executes an **HTTP GET Flood** with custom or predefined User Agents.
- Customizable parameters to modify:
  - Target URL
  - Number of requests
  - Custom pool of User Agents

##  Technologies Used
- **Python** 
- **Requests** library (for sending HTTP requests with varied User Agents) 
- **Randomized User Agents** to simulate different browsers and devices 

##  How it Works
This PoC generates a large volume of **HTTP GET** requests to the target server, each containing a unique or random **User Agent** string. The goal is to simulate legitimate traffic from different devices and browsers, overwhelming the server's capacity and making it difficult for basic filters to block malicious requests.


##  Social Media

**Follow me on TikTok:**     https://www.tiktok.com/@v2arias/

