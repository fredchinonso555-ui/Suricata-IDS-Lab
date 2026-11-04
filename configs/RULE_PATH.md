# Suricata Rule Path

## Documented Rule Directory

```text
/var/lib/suricata/rules/
```

## Directory Navigation

```bash
cd /var
ls
cd lib
ls
cd suricata
ls
```

The lab involved exploring the Suricata directory structure and
configuring the absolute default rule path in `suricata.yaml`.

## Why the Rule Path Matters

Suricata needs to locate its detection rules to inspect network
traffic and generate alerts.

A correct rule path helps ensure that the configured rules can
be loaded by Suricata.
