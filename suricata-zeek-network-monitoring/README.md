# Network Security Monitoring Lab — Suricata IDS/IPS and Zeek

## Objective
Practice network security monitoring using Suricata for IDS/IPS exercises and Zeek for network-activity logging.

## Environment and tools
- Ubuntu
- Suricata
- Zeek (run using Docker in this lab)
- `jq`
- Nmap
- PCAP files / offline packet analysis

## Work performed

### Suricata
- Installed Suricata and validated its configuration.
- Updated rules and created custom rules to identify selected web traffic.
- Reviewed `fast.log` and `eve.json`.
- Used `jq` to filter alert events and extract signature information.
- Configured an IPS drop rule and NFQUEUE packet redirection as a traffic-blocking exercise.

### Zeek
- Ran Zeek using Docker after encountering package-repository issues.
- Generated and inspected HTTP, DNS, and connection logs.
- Performed offline PCAP analysis.
- Observed connection records during an Nmap SYN-scan exercise.

## Results and limitations
The lab report documents configuration work, log review, custom-rule exercises, Zeek log analysis, and PCAP exercises. Do not describe traffic as successfully blocked, or claim a scan was detected by an alert, unless you have screenshots or logs that verify the outcome.

## Evidence
See [`reports/`](reports/) for the lab report. Add screenshots to [`screenshots/`](screenshots/) after checking them for sensitive information.

## Skills practiced
IDS/IPS configuration, rule-writing practice, alert-log analysis, JSON filtering with `jq`, network telemetry review, HTTP/DNS analysis, and PCAP inspection.

## Safety
Only monitor or test traffic in a lab or on systems/networks for which you have authorization.
