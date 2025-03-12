# 🌐 Network Analysis – Malware Compromise

## Challenge Details

**Scenario:**  
A SOC Analyst at Umbrella Corporation is going through SIEM alerts and sees the alert for connections to a known malicious domain.

**Tools:**  
Wireshark, TCPDump, TShark, Zui

## Scenario

A SOC Analyst at Umbrella Corporation is reviewing SIEM alerts and notices connections to a known malicious domain. The traffic originates from Sara’s computer—an accountant who receives a large volume of emails from customers daily. Although Sara’s email gateway logs appear normal, when contacted, she reveals that a customer sent her an invoice with a document containing a macro. Upon opening the document, her program crashed, prompting the SOC Team to retrieve a PCAP for further analysis.

---

## Question and Answers

1. **What’s the private IP of the infected host? (4 points)**  
   **Answer:** `10.11.27.101`

2. **What’s the malware binary that the macro document is trying to retrieve? (4 points)**  
   **Answer:** `spet10.spr`

3. **From what domain are HTTP requests with GET /images/ coming? (4 points)**  
   **Answer:** `cochrimato.com`

4. **What’s the full URL ending in .rar where Ursnif retrieves the follow-up malware from? (4 points)**  
   **Answer:** `http://95.181.198.231/oiioiashdqbwe.rar`

5. **What is the Dridex post-infection traffic IP address beginning with 185.? (4 points)**  
   **Answer:** `185.244.150.230`

---

## Screenshots

**Screenshot 1: SIEM Alert / Network Traffic Capture**  
![Screenshot 1](https://imgur.com/q2LCUgw.png)

**Screenshot 2: Email Gateway Logs**  
![Screenshot 2](https://imgur.com/Aq3ygJH.png)

**Screenshot 3: PCAP Analysis in Wireshark/TCPDump/TShark**  
![Screenshot 3](https://imgur.com/Lyj5hPP.png)

**Screenshot 4: Macro Document Triggering the Crash**  
![Screenshot 4](https://imgur.com/QOyICr1.png)

**Screenshot 5: Malware Retrieval / Post-Infection Traffic**  
![Screenshot 5](https://imgur.com/d9q5Llv.png)

---

## Summary

This challenge involved a detailed network analysis to trace a malware compromise incident. Key findings include:

- **Infected Host Private IP:** `10.11.27.101`
- **Malware Binary Retrieved:** `spet10.spr`
- **Domain for HTTP GET /images/ Requests:** `cochrimato.com`
- **Follow-up Malware URL:** `http://95.181.198.231/oiioiashdqbwe.rar`
- **Dridex Post-Infection Traffic IP:** `185.244.150.230`

This analysis demonstrates the critical role of tools like Wireshark, TCPDump, and TShark in a SOC environment, enabling analysts to detect and trace malware-related activities.

---

*Explore more cybersecurity challenges and analyses on my GitHub repository!*
