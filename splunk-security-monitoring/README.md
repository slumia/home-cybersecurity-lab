# Splunk Security Monitoring: Windows Authentication Events

## Objective

The purpose of this lab was to configure Splunk as a centralized security monitoring platform and investigate Windows authentication activity in an Active Directory environment.

## Lab Environment

- VMware Workstation
- Windows Server domain controller: DC01
- Windows 11 domain-joined client
- Active Directory domain: samlab.local
- Splunk Enterprise
- Windows Security Event Logs

## Test Scenario

A domain user account named `jsmith` was used to generate both successful and failed authentication activity. An incorrect password was intentionally entered to generate a failed authentication event.

Windows recorded the failed authentication as Event ID 4625. Splunk ingested the Windows Security log and allowed the event to be searched and investigated centrally.

## Splunk Searches

### Failed authentication events

```spl
index=* EventCode=4625
