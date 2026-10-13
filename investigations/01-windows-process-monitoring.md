# Investigation 01: Windows Process Monitoring

## 1. Objective

Validate whether Windows process creation activity on the monitored Windows 11 endpoint is collected and available for investigation through Wazuh.

## 2. Test Environment

- Endpoint: Windows 11 virtual machine
- SIEM: Wazuh
- Log source: Windows process creation events
- Test activity: Launching a benign application in the lab

## 3. Hypothesis

If the required Windows auditing and Wazuh collection settings are configured correctly, launching a test application should generate relevant endpoint telemetry that can be located and reviewed.

## 4. Investigation Steps

1. Launch the test application on the Windows endpoint.
2. Record the test time and identify the corresponding Windows event, if generated.
3. Review the event in Windows Event Viewer.
4. Check whether the relevant event is available in Wazuh.
5. Compare timestamps and process details to validate the event.
6. Record any missing telemetry and troubleshoot the collection configuration.

## 5. Evidence Collected

- Test timestamp:
- Windows event ID:
- Process name:
- Windows event successfully generated: Yes / No
- Event visible in Wazuh: Yes / No
- Relevant Wazuh alert generated: Yes / No / Not applicable
- Supporting screenshots:

## 6. Findings

Document what was actually observed. Distinguish between a Windows event being generated, an event being collected by Wazuh, and a security alert being triggered.

## 7. Conclusion

Summarize whether the test objective was achieved and identify any remaining configuration or investigation gaps.

## 8. Recommended Next Steps

- Validate any missing Windows auditing or log collection settings.
- Repeat the test after making configuration changes.
- Confirm that timestamps and process details match.
- Explore additional detection scenarios after successful telemetry validation.
