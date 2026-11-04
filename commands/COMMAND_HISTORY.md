# Command History

This file records commands associated with the lab.

## 1. Package Management

```bash
sudo apt update
sudo apt install suricata
sudo apt install jq
```

Package installation commands are included for reference.
The lab author should retain actual installation screenshots
as evidence.

## 2. Suricata Version and Build Information

```bash
suricata -V
suricata --build-info
```

These commands display Suricata version and build information.

## 3. Directory Navigation and Configuration

The directory exploration was performed step by step:

```bash
cd /etc
ls
cd suricata
ls
nano suricata.yaml
```

The configuration file was opened using Nano.

## 4. Rule Directory Exploration

The directory exploration continued through:

```bash
cd /var
ls
cd lib
ls
cd suricata
ls
```

The Suricata rule directory was explored.

Documented rule path:

```text
/var/lib/suricata/rules/
```

## 5. Network Interface Inspection

```bash
ip addr
```

Displays network interfaces and their assigned addresses.

## 6. DNS Traffic Generation

```bash
dig example.com
```

Generates a DNS lookup for example.com.

## 7. Log Inspection

```bash
cat fast.log
```

Displays the contents of fast.log from the current working directory.

The actual location depends on the working directory and configuration.

## 8. EVE JSON Formatting

```bash
sudo cat /var/log/suricata/eve.json | jq
```

Reads the EVE JSON log and pipes the output into jq for formatting.

## 9. TCP / Netcat Testing

A Netcat TCP communication test was performed using port 9999.

The exact original command line is not reproduced here because
it has not been independently confirmed.

## Accuracy

This is a documentation record, not a claim that every command
was executed in precisely this order or that every installation
attempt succeeded.
