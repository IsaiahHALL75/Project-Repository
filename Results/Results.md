# Project Results

The Admin gained access to view documents, send documents, and complete/logout

An authentication and access tracker has access to view documents and complete/logout

The log file analysis script read log files from the given URL, analyzed, and searched and found keywords such as “failed” or “unauthorized”.  This identified any potential security threats by filtering logs.

Performance data is logged by the use of psutil library, having the script track CPU and memory usage in real-time 

The script also used an alert system using smtplib that sends email notifications when high CPU usage or multiple log entries occur 

There is a nmap scan used to identify points of entry for unauthorized access by generating a list of open ports and service information for a specified target

Scapy was used in the code to capture network packets with TCP and IP layers that filtered relevant traffic and displayed source and destination IP addresses.  Vulnerabilities detected included high cpu usage and open ports for unauthorized access.

We gained a full range of monitoring functions for network scanning, system performance monitoring, and log analysis.  
