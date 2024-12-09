# README

## Project Overview
In this project, our group designed and developed a comprehensive cybersecurity system for a government organization. We applied concepts and techniques such as: use case diagrams, mapping UML, python automation, data analysis, and risk management. Throughout the development of our cybersecurity system, it was challenging to implement the system's incident response and were faced with missed functionality within the code. Our objectives were to apply system engineering concepts such as automation and data analytics to design the cybersecurity system, utilize UML to model the system processes, implement python automation scripts for various cybersecurity tasks, integrate data analytics for threat detection/response, and finally to develop risk management plans. These concepts are significant in cybersecurity because they are used in order to ensure the security and strength of a cybersecurity system. 

## Installation
First to initially plan our system we used UML to create use case and activity diagrams to model the system requirements and user interactions. Then we used SysML to develop block definition diagrams and internal block diagrams in order to detail system components and their interaction. When creating the python scripts to automate the tasks, tools like Pandas and Github were used. The python scripts were created to monitor system analysis and log file analysis. During the data analysis, we collected and processed data relevant to the systems security and applied anomaly detection to enhance threat detection. In response to the detections the psutil library was utilized as well as nmap scan, in order to identify entry points for unauthorized users. 

## Usage
The Admin gained access to view documents, send documents, and complete/logout

An authentication and access tracker has access to view documents and complete/logout

The log file analysis script read log files from the given URL, analyzed, and searched and found keywords such as “failed” or “unauthorized”.  This identified any potential security threats by filtering logs.

Performance data is logged by the use of psutil library, having the script track CPU and memory usage in real-time 

The script also used an alert system using smtplib that sends email notifications when high CPU usage or multiple log entries occur 

There is a nmap scan used to identify points of entry for unauthorized access by generating a list of open ports and service information for a specified target

Scapy was used in the code to capture network packets with TCP and IP layers that filtered relevant traffic and displayed source and destination IP addresses.  Vulnerabilities detected included high cpu usage and open ports for unauthorized access.

We gained a full range of monitoring functions for network scanning, system performance monitoring, and log analysis.  
## Team Members 
### Nora (Project Manager) 
### Ryan (Developer)
### Eun (Developer)
### Dana (Data Analyst)
### Tias (System Modeler)
### Isaiah (System Modeler) 
