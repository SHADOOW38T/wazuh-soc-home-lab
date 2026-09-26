# SOC L1 Workflow

## 1. Alert Received

The SOC L1 analyst receives a security alert from a SIEM, EDR, IDS/IPS, email security platform, or another security monitoring system.

Record:

- Alert name
- Alert ID
- Detection time
- Source
- Affected host
- Affected user
- Severity
- Detection rule

---

## 2. Initial Triage

The analyst performs an initial review to determine whether the alert requires further investigation.

Check:

- Source IP
- Destination IP
- Username
- Hostname
- Timestamp
- Event type
- Number of events
- Related alerts
- Existing threat intelligence

---

## 3. Validate the Alert

Determine whether the activity is:

- Expected
- Suspicious
- Malicious
- False Positive

Do not immediately close an alert only because it appears unusual.

Review the available evidence first.

---

## 4. Investigation

Investigate the activity using available logs and security tools.

Examples:

- Windows Event Logs
- Sysmon
- SIEM searches
- EDR telemetry
- Threat intelligence
- Network information
- Authentication logs

---

## 5. Evidence Collection

Document relevant evidence.

Examples:

- Source IP
- Destination IP
- Username
- Hostname
- Process
- Command line
- File hash
- Domain
- URL
- Timestamp
- Event ID

---

## 6. Determine Severity

Consider:

- Type of activity
- Affected asset
- User involved
- Evidence of compromise
- Potential impact
- Number of affected systems

---

## 7. Response

Depending on the SOC procedure, the L1 analyst may:

- Continue monitoring
- Gather additional evidence
- Recommend blocking
- Recommend account investigation
- Create an incident
- Escalate to L2

Actions should follow the organization's authorization and procedures.

---

## 8. Escalation

Escalate when the investigation requires additional expertise, access, or response authority.

Include:

- Summary
- Timeline
- Evidence
- IOCs
- Investigation performed
- Current impact
- Actions already taken
- Reason for escalation

---

## 9. Documentation

Document the investigation clearly.

The report should allow another analyst to understand:

> What happened, what was investigated, what was discovered, and what happened next.

---

## 10. Closure

Before closing the alert:

- Investigation completed
- Evidence documented
- Classification determined
- Required actions completed
- Escalation completed if necessary
- Final conclusion documented
