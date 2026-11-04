# Suricata IDS Lab Report

## 1. Introduction

This lab involved installing, configuring, and testing Suricata,
an open-source network intrusion detection system.

The exercise focused on local rule configuration, protocol traffic
testing, and inspection of Suricata-generated logs.

## 2. Lab Environment

- Host: Windows 11.
- Virtualization: Oracle VirtualBox.
- Virtual machine: Cyber Ops Lab VM.
- Guest operating system: Ubuntu Server 26.04.1 LTS.
- Network security tool: Suricata IDS.

## 3. Objectives

- Inspect Suricata version and build information.
- Explore the configuration directory.
- Edit the configuration file using Nano.
- Configure the default rule path.
- Test network protocol activity.
- Inspect Suricata logs.
- Format JSON records using jq.

## 4. Configuration

The main configuration file:

```text
/etc/suricata/suricata.yaml
```

The absolute default rule path was configured as:

```text
/var/lib/suricata/rules/
```

## 5. Protocol Testing

The lab involved rule and traffic testing related to:

- TCP
- UDP
- ICMP
- HTTP
- SSH
- DNS

DNS traffic was generated using:

```bash
dig example.com
```

A TCP communication test was also performed using Netcat on port 9999.

## 6. Log Inspection

The lab included inspection of:

- fast.log
- eve.json
- stats.log
- suricata.log

The EVE JSON output was formatted using jq.

## 7. Evidence

Original screenshots will be stored in:

`evidence/screenshots/`

## 8. Conclusion

The lab provided practical experience with Suricata configuration,
rule-based detection, network traffic testing, and security log
inspection.

The screenshots and supporting documentation provide evidence
of the activities performed.
