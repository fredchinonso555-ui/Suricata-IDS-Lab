# Local Rules Documentation

## Overview

This document describes portfolio rule examples corresponding
to the protocol activities recorded in the lab.

## Rule Categories

| SID | Protocol / Activity |
|---|---|
| 1000001 | ICMP |
| 1000002 | TCP SYN |
| 1000003 | UDP |
| 1000004 | HTTP GET |
| 1000005 | SSH |
| 1000006 | DNS |

## Rule Structure

A Suricata rule generally contains:

- Action: What Suricata should do.
- Protocol: The protocol being inspected.
- Source address and port.
- Direction operator.
- Destination address and port.
- Rule options, including message, SID, and revision.

## Accuracy Note

These signatures are reconstructed examples for documentation.
They must not be described as the exact original rules used
in the practical exercise unless verified against the original
rule file or screenshots.

Check protocol keywords, rule syntax, variables, and configuration
compatibility against the installed Suricata version.
