1. Project Title
Packet Sniffer and Fake WiFi Login (Phishing Simulation) using Flask and Scapy
2. Objective
- To monitor and analyze network traffic using packet sniffing
- To demonstrate how sensitive data can be intercepted over unsecured HTTP connections
- To create awareness about phishing attacks using fake WiFi login pages
- To understand cybersecurity concepts such as packet sniffing, data interception, and network vulnerabilities
3. Tools & Technologies Used
- Python 3.12
- Flask (Web framework)
- Scapy (Packet analysis tool)
- Npcap (Packet capture driver)
- HTML/CSS
- Windows 10
4. Project Components
wifi.py: Basic fake WiFi login page (captures username & password)
mal_wifi.py: Malicious version capturing credit card info
network_sniffer.py: Captures HTTP packets and displays sensitive data
styles.py: Provides styled HTML interface

5. Methodology / Working
Step 1: Environment setup (Anaconda, dependencies, Npcap)
Step 2: Run Flask server (host=0.0.0.0, port=8080)
Step 3: Connect phone and computer on same WiFi
Step 4: Run network_sniffer.py to capture traffic
Step 5: Submit form → HTTP POST request captured
Step 6: Malicious version captures financial data
6. Result\Output
- Usernames and passwords can be intercepted
- Credit card information can be captured
- HTTP traffic is unencrypted and readable
- Real-time packet sniffing is possible
7. Conclusion
- HTTP is insecure
- Data can be intercepted easily
- Phishing attacks are dangerous
- Secure practices (HTTPS, VPN) are necessary
8. Future Improvements
- HTTPS interception simulation
- Improved UI
- Data logging system
- Phishing detection system
- Machine learning integration
9. References
- Flask Documentation
- Scapy Documentation
- Npcap Official Website
- Cybersecurity resources
