# Suricata IDS Cyber Operations Lab

## Project Overview

This project documents a practical Intrusion Detection System (IDS)
lab using Suricata on Ubuntu Server 26.04.1 LTS.

The lab focuses on configuring Suricata, working with local detection
rules, generating network traffic, monitoring protocol activity,
and examining security events recorded in Suricata logs.

## Objectives

- Install and inspect Suricata.
- Examine Suricata version and build information.
- Explore the Suricata configuration directory.
- Configure the default rule path.
- Work with local detection rules.
- Test TCP, UDP, and ICMP traffic.
- Examine HTTP, SSH, and DNS-related activity.
- Inspect fast.log and eve.json.
- Format JSON log output using jq.
- Document observations and preserve lab evidence.

## Lab Environment

| Component | Details |
|---|---|
| Host operating system | Windows 11 |
| Virtualization | Oracle VirtualBox |
| Lab virtual machine | Cyber Ops Lab VM |
| Guest operating system | Ubuntu Server 26.04.1 LTS |
| Suricata | Version and build details captured during lab |
| JSON processor | jq |

## Project Structure

- `commands/` - Commands used during the lab.
- `configs/` - Configuration documentation.
- `docs/` - Lab reports and technical documentation.
- `rules/` - Local rules and rule documentation.
- `scripts/` - Automation and script documentation.
- `evidence/` - Original screenshots and supporting evidence.
- `logs/` - Log file documentation.
- `reports/` - Traffic and rule analysis.
- `research/` - Additional research.
- `notes/` - Lab notes.

## Evidence

Screenshots are maintained in `evidence/screenshots/`.

Only genuine screenshots and outputs from the actual lab should be
added. No fabricated evidence is included in this repository.

## Important Accuracy Note

The rule examples in this repository are reconstructed portfolio
examples based on the documented protocol-testing activities.
They are not claimed to be byte-for-byte copies of the original
terminal rules. Confirm them against the actual lab configuration
before using them in a live environment.

## Learning Outcomes

This exercise provides practical exposure to IDS configuration,
network protocol monitoring, rule-based detection, JSON log analysis,
and security documentation.

## License

This project is released under the MIT License.
