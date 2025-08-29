# 🌐 Network Traffic Analysis – Google Cybersecurity Professional Certificate  

This repository contains a **hands-on project on Network Traffic Analysis**, completed as part of the **Google Cybersecurity Professional Certificate**.  
The activity focused on analyzing captured network traffic, identifying error messages, and determining which protocol and service were impacted during a simulated incident.  

---

## 📋 Project Overview  
The task involved:  
- Using a network analyzer tool (**tcpdump**) to capture and inspect traffic.  
- Interpreting UDP and ICMP packet exchanges.  
- Identifying the root cause of a failed DNS query.  
- Reporting findings in a structured and professional format.  

---

## 🔎 Key Findings  
- The client attempted to resolve the domain `yummyrecipesforme.com`.  
- UDP queries were sent to the DNS server `203.0.113.2` on port 53.  
- The DNS server responded with **ICMP error messages**: *“udp port 53 unreachable”*.  
- As a result, the DNS service was unavailable, preventing domain resolution and blocking access to the website.  

---

## ✅ Skills Demonstrated  
- Packet analysis with **tcpdump**.  
- Understanding of **network protocols** (UDP, DNS, ICMP, HTTPS).  
- Ability to interpret **error messages** and link them to service unavailability.  
- Drafting **incident analysis reports** with findings, risks, and recommendations.  

---

## 🎯 Conclusion  
This activity simulated a real-world scenario where a DNS service outage impacted users’ ability to access websites.  
Through packet inspection and error message analysis, I identified the affected protocol and service, providing a clear explanation of the root cause.  

---

## 🧑‍💻 About This Project  
This project is part of my **Cybersecurity Portfolio**, showcasing practical experience in:  
- **Network traffic analysis**  
- **Incident investigation**  
- **Communication of technical findings** in a professional format  

📌 Developed during the **Google Cybersecurity Professional Certificate**.  
