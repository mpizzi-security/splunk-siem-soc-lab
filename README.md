# SOC Monitoring and Threat Detection Using Splunk SIEM

## Overview
This project demonstrates a Tier 1 SOC-style workflow using Splunk SIEM.
It focuses on centralized log ingestion, alert development, alert triage,
and basic incident investigation using realistic authentication-based threats.

## Environment
- Splunk Enterprise (SIEM)
- Windows Event Logs
- Linux authentication logs (SSH)
- Splunk Universal Forwarder
- Virtualized lab environment

## Detection Use Cases
- SSH brute-force login attempts
- Repeated failed authentication attempts
- Suspicious login behavior following multiple failures

## Investigation Workflow
Alerts were investigated by reviewing and correlating:
- Source IP addresses
- Usernames
- Host systems
- Event timestamps and frequency

Each investigation includes evidence review, impact assessment,
and recommended response actions consistent with Tier 1 SOC procedures.

## Artifacts Included
- Architecture diagram
- Log ingestion screenshots (Windows and Linux)
- Alert configuration and triggered alert evidence
- Incident investigation summaries
- SOC monitoring dashboard

## Key Skills Demonstrated
- SIEM log ingestion and normalization
- Alert development and tuning
- SOC-style alert triage
- Basic incident investigation
- Security monitoring dashboards
