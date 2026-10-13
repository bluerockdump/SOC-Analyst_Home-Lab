Network Diagram

Purpose

This document describes the architecture of my SOC Analyst Home Lab.

The lab is designed to simulate a small enterprise environment for cybersecurity investigations, network analysis, threat detection, and incident response.

Current Environment

Analyst Workstation

  Component          Details
Operating System	Parrot OS
Role	    Security Analyst Workstation
Purpose	Investigation, packet analysis, threat hunting

Current Network Layout

Internet
    │
    │
Home Router
    │
    │
Parrot OS VM

Current Security Tools

  Tool	        Purpose
Wireshark  	Packet Analysis
Nmap	      Network Discovery
Parrot Security Tools	Security Testing
GitHub	    Documentation and Portfolio

Skills Demonstrated

  -Linux Administration
  -Network Analysis
  -Security Documentation
  -Threat Investigation
  -GitHub Portfolio Development
  
Planned Expansion

Phase 1

Add a Windows 11 virtual machine.

Internet
    │
Home Router
    │
───────────────
│             │
Parrot OS   Windows 11

Purpose:

  -Endpoint investigation
  -Event log analysis
  -Security monitoring
  
Phase 2

Add Windows Server.

Internet
    │
Home Router
    │
──────────────────────
│          │         │
Parrot OS  Win11   Windows Server

Purpose:

  -Active Directory
  -User Management
  -Group Policy
  -Authentication
  
Phase 3

Add Security Monitoring.

Internet
    │
Home Router
    │
───────────────────────────
│          │            │
Parrot OS  Win11   Windows Server
                │
                │
              Wazuh
Purpose:

  -Security Monitoring
  -Alerting
  -Threat Detection
  -Incident Response
  
Future Objectives:

  -Build Active Directory Lab
  -Investigate Failed Login Events
  -Analyze DNS Traffic
  -Create Detection Rules
  -Perform Threat Hunting Exercises
  -Develop Incident Response Playbooks
  
Last Updated:

October 2026
