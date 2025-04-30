# cloud-threat-detection
Azure-based security alerting system using Log Analytics and KQL

This project implements a cloud-based security monitoring setup using Microsoft Azure Log Analytics, Kusto Query Language (KQL), and Microsoft Entra ID. It collects sign-in and audit activity from Entra ID, processes the data using custom KQL queries, and generates alerts for defined security events.

Features
Detection of brute-force sign-in attempts based on failed login thresholds

Identification of sign-ins originating from non-local IP geolocations

Monitoring of administrative role assignments and privilege escalations

Alert rules created using Azure Monitor based on query results

Visualization layer planned using Azure Workbooks

Stack
Azure Log Analytics Workspace

Microsoft Entra ID (formerly Azure Active Directory)

Kusto Query Language (KQL)

Azure Monitor Alerts

Structure
/queries/: KQL files for detection rules

/screenshots/: Sample alerts and dashboard captures (pending log ingestion)

Status
Detection queries and alert rules are configured. Waiting on log ingestion for validation and dashboard buildout.
