# Failed Login Investigation

## Objective

The objective of this exercise was to investigate failed authentication attempts in a Windows environment using Event Viewer and Windows Security logs.

## Tools Used

- Windows Server
- Event Viewer
- Windows Security Logs

## Steps Performed

1. Opened Event Viewer
2. Navigated to Windows Logs → Security
3. Filtered logs using Event ID 4625
4. Generated failed login attempts using invalid credentials
5. Reviewed audit failure events
6. Compared local versus domain authentication behavior

## Findings

- Event ID 4625 was generated for failed authentication attempts.
- Local authentication attempts generated immediate log entries.
- Domain authentication behavior differed from local authentication logging.
- Windows auditing policies were verified to ensure failed logon events were enabled.

## Skills Practiced

- Security log analysis
- Authentication troubleshooting
- Windows administration
- Event filtering
- Basic incident investigation
