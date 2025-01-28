# AWS-cybersecurity-Homelab

Project: Deploying Security Onion on AWS for SOC Learning

Objective:
This project demonstrates a Proof of Concept (PoC) for deploying Security Onion on AWS to gain hands-on experience in building a Security Operations Center (SOC) environment. Security Onion is an open-source Linux distribution designed for intrusion detection, network security monitoring, and log management.

The aim is to explore how cloud-based security tools can monitor network traffic, detect threats, and provide actionable insights for incident response.

Key Deliverables:

Deploy a Security Onion Instance:

Configure Security Onion in a public subnet within an AWS VPC.
Monitor and analyze network traffic flowing within the virtual cloud environment.
AWS Configuration:

Create a Virtual Private Cloud (VPC) with a CIDR block suitable for the PoC.
Configure subnets (public and private) and associated security groups.
Enable proper routing and access controls using internet gateways and route tables.
Threat Detection Capabilities:

Use Security Onion to detect simulated network threats.
Generate logs and alerts for analysis in a SOC workflow.
Log Management and Analysis:

Collect and analyze network telemetry logs.
Validate the setup with sample traffic and threat scenarios.
Steps to Complete the Project:

AWS Environment Setup:

Create a VPC with a public subnet for Security Onion.
Assign an Elastic IP and attach it to the instance for remote accessibility.
Configure appropriate security groups to allow inbound traffic (e.g., SSH and monitoring ports).
Security Onion Deployment:

Launch a Linux-based EC2 instance and install Security Onion.
Configure Security Onion to monitor specific network interfaces and capture traffic within the VPC.
Set up tools such as Kibana and Elasticsearch for log visualization and analysis.
Validation and Testing:

Simulate malicious network activities using tools like Kali Linux or Metasploit.
Verify that Security Onion generates alerts and logs accurately.
Documentation and Results:

Document the deployment process, configurations, and lessons learned.
Include screenshots of logs, alerts, and dashboards from Security Onion.
Key Technologies Used:

AWS Services: EC2, VPC, Security Groups, Subnets, Internet Gateway.
Security Onion: Tools like Suricata, Zeek (formerly Bro), Kibana, Elasticsearch.
Networking: CIDR, routing tables, and firewall rules.
Outcome:
This project provides a foundational understanding of how to deploy and manage a network monitoring solution in the cloud. It showcases the use of AWS and Security Onion to simulate a cloud-based SOC environment, preparing you for real-world cybersecurity monitoring tasks.

Future Enhancements:

Integrate AWS Security Hub or Amazon Detective for advanced threat analytics and a centralized security view.
Automate threat detection using AWS Lambda to process and analyze Security Onion logs, triggering alerts for identified threats.
Leverage AWS CloudTrail and Amazon GuardDuty to enhance monitoring and detect anomalies across AWS resources.
