# Honeypot-Project

## Objective
The Honeypot Project aimed to set up and deploy a honeypot using Teapot on the Vultr cloud platform. The goal was to capture and analyze cyberattack data while demonstrating proficiency in honeypot deployment, firewall configuration, and data analysis through visualization tools like Kibana.

### Skills Learned
<ul>
  <li>Learned how to deploy and manage a multi-honeypot system effectively.</li>
  <li>Gained experience in configuring firewalls to control access and improve security.</li>
  <li>Analyzed attack data to identify patterns, track sources, and assess IP reputations.</li>
  <li>Developed a better understanding of cloud platforms and virtualization tools.</li>
  <li>Improved my ability to spot trends in global cyberattacks and interpret data through dashboards.</li>
</ul>

### Tools Used
<ul>
  <li>T-Pot: Multi-honeypot platform for capturing and analyzing attack data.</li>
  <li>Vultr: Cloud service provider for deploying the honeypot.</li>
  <li>Kibana: Visualization tool for analyzing attack patterns, sources, and reputations.</li>
  <li>CyberChef: Swiss-army tool for data analysis.</li>
  <li>Firewall: Configured to control and monitor honeypot access.</li>
</ul>

## Steps
<b>Set Up Vultr Cloud Server</b>
Deploy a virtual machine on Vultr with sufficient resources (e.g., 4 vCPU, 8GB RAM, 160GB SSD).
Install the T-Pot multi-honeypot platform.
Configure T-Pot

Set up the honeypot services (e.g., Cowrie, Honeytrap, Dionaea).
Configure the firewall to control access and protect the honeypot.
Monitor and Collect Data

Use T-Pot’s Elastic Stack (Elasticsearch, Logstash, Kibana) to capture and store attack telemetry.
Ensure real-time monitoring of attacks via Kibana dashboards.
Analyze Attack Data

Examine visualizations in Kibana, such as attack trends, geographic locations, and IP reputations.
Use CyberChef for deeper analysis of raw data.
Generate Reports

Summarize attack patterns, sources, and vulnerabilities targeted.
Provide insights on attacker behavior and potential mitigation strategies.

## Screenshots
Image-1 Vultr cloud platform control panel showing the deployment details of a T-Pot honeypot server, including location, resources, and bandwidth usage.<br>
![1718589034642](https://github.com/user-attachments/assets/eb660db3-ef00-4161-8ae1-f1df3fd648fc)
<br>Image-2 T-pot is being installed on the virtual machine that is being run on vultr.<br>
![1718589041169](https://github.com/user-attachments/assets/b4605fdb-ada5-4177-a1e0-af98b2df382d)
<br>Image -3 This is the image of OS that the user interacts with to use the honeypot.<br>
![1718589050296](https://github.com/user-attachments/assets/cc64cc0b-a18d-456f-8d46-c5b38daa8922)
<br>Image-4 This is a Kibana dashboard visualizing data from the T-Pot honeypot. It includes metrics such as the number of attacks and visual representations like histograms, graphs, and a geographical attack map.<br>
![1718589063361](https://github.com/user-attachments/assets/5d764741-d804-437d-815e-72c5a8da4796)
<br>Image-5 Another Kibana dashboard view, focusing on Cowrie honeypot data. It displays pie charts that break down attacker source IP reputation, attacks by country, and attacks by port. There's also a chart showing the top 10 Cowrie versions used in the attacks and another illustrating hashed IP data.<br>
![1718589057116](https://github.com/user-attachments/assets/bef8c8e5-8bd2-424f-a7ea-88be68c4d866)


