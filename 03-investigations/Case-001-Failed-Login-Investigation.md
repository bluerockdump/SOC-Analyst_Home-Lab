# Case 001 - Failed Login Investigation

## Executive Summary

This investigation documents the analysis of repeated failed login attempts within the SOC Analyst Home Lab environment.

The objective was to identify the source of the failed authentication attempts, determine potential impact, and recommend mitigation actions.

---

## Investigation Details

| Field | Value |
|---------|---------|
| Case ID | CASE-001 |
| Analyst | Pedro Rivera |
| Date | October 2026 |
| Severity | Low |
| Status | Closed |

---

## Objective

Investigate repeated failed login attempts and determine whether the activity represents a potential security concern.

---

## Environment

| System | Role |
|----------|---------|
| Windows 11 | User Workstation |
| Parrot OS | Analyst Workstation |

---

## Initial Alert

Multiple failed login attempts were observed against a local Windows account.

---

## Evidence Collected

Evidence sources included:

- Windows Security Event Logs
- Login Event Records
- Local User Account Information

---

## Analysis

The failed authentication attempts were reviewed to determine:

- Source account
- Frequency
- Target system
- Potential indicators of malicious activity

---

## Findings

The investigation identified multiple failed login attempts against a test account.

No successful authentication events were observed.

The activity was determined to be a lab-generated event for security monitoring practice.

---

## Recommendations

1. Enable account lockout policies.
2. Monitor repeated authentication failures.
3. Review privileged account usage.
4. Continue log monitoring.

---

## Lessons Learned

This investigation improved understanding of authentication events and the process of reviewing failed login activity.

---

## Skills Demonstrated

- Security Monitoring
- Log Analysis
- Incident Documentation
- Windows Security
- Cybersecurity Investigation
