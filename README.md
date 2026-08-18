# Ethical-Hacking-Lab
Configured a beta website for one of our Nigerians' cyber security analyst and performed a small attack on their website.

Generated our home lab with Hyper V Manager. Windows Server 2022, and Kali linux

1. The goal is to first build a foundation on Windows Server 2022.
<img width="843" height="240" alt="Screenshot 2026-08-18 at 12 44 28" src="https://github.com/user-attachments/assets/6f9fb1e8-3af7-463f-92f4-010dd6c70e6e" />

2. We'll be using IIS web server to upload the code for the website.
-  We use port 80, or 8080 for HTTP to give access to our search engine.
-  Must set port as the local host
<img width="843" height="263" alt="Screenshot 2026-08-18 at 13 00 21" src="https://github.com/user-attachments/assets/5bf0f481-f51d-407c-85fe-655d84f5b4bc" />

3. We also have to utilize SQLExpress to add our database for our cyber security analyst.
-  This is for clients to see the data within his courses when it comes to growth between each student.
<img width="839" height="545" alt="Screenshot 2026-08-18 at 13 03 09" src="https://github.com/user-attachments/assets/bf33c5e2-025f-455d-9f65-34605bb48e18" />

4. Type localhost:8080 or localhost:80 for website to show on search engine.
<img width="839" height="409" alt="Screenshot 2026-08-18 at 13 11 36" src="https://github.com/user-attachments/assets/b24e0b8d-a5d9-4caa-a5a3-3d05da9a5ad6" />

5. On Windows Server 2022 we must configure our firewall for port security. ICMP port will allow us to connect from our attacker machine to the windows machine.
-  Ports we want to configure ftp 21, ssh 22, telnet 23, mysql 3306, http 80/8080 
<img width="839" height="268" alt="Screenshot 2026-08-18 at 13 26 38" src="https://github.com/user-attachments/assets/5f1a795d-5d0e-4b88-acfd-51492fdd6802" />

6. Once the firewall ICMP port is online that gives my attacker machine access to see if the windows server is online.
-  Both devices must be on the same network in order for this to work.
-  To find the actual device you could take the Ip address of the router go on kali linux search engine and search for the IP address or get the ip address of the exact device through the computers command prompt.
<img width="839" height="355" alt="Screenshot 2026-08-18 at 13 34 47" src="https://github.com/user-attachments/assets/a70f9c6b-4e9e-418c-b4eb-f085c83ebb7f" />

1.Why is virtualization critical in a SOC environment? 
Virtualization is critical in a SOC environment because it gives the administrator user the run test in the system through a virtual platform. These tests range from threat analysis, detection, and preparation against dangerous attacks through the network.  

2.Which deployed services introduce the highest security risk, and why? 
The deployed services that introduce the highest risk are web facing development pages. Technically anything that has a user interface that can be browsed through the network. 

3.What security logs and telemetry will your environment generate for SOC monitoring? 
The security logs and telemetry that your environment generate for SOC monitoring is packets within the network based off volume and the direction its heading. Also, connectivity within different ports and firewall connectivity. 

4.How does firewall telemetry support detection and investigation? 
Firewall telemetry support detection and investigation by being configured to protect the system from receiving data through programs and ports reducing a chance of compromising the system. This gives SOC analysts an idea of where the problem could be coming from since certain configuration have been executed in the firewall. 

5.Which CompTIA Security+ security principles were applied in your design? 
Confidentiality, Integrity, and Availability. 

 




