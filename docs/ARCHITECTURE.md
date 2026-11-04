# Lab Architecture

## Environment

The lab uses a Windows 11 host running Oracle VirtualBox.

The Cyber Ops Lab VM runs Ubuntu Server 26.04.1 LTS with Suricata
installed.

## Simplified Traffic Flow

```text
Network Traffic
      |
      v
Ubuntu Server VM
      |
      v
Suricata IDS
      |
      v
Detection Rules
      |
      v
Event and Alert Logs
      |
      +---- fast.log
      |
      +---- eve.json
      |
      +---- stats.log
      |
      +---- suricata.log
```

## Purpose

Suricata examines network traffic against configured detection
rules and records relevant events.

The generated logs can then be inspected for security analysis.
