---
creation date:
last modified date:
aliases: []
tags: [misc]
status: todo
---

# [[Active Information Gathering]]

### Port Scan

**Top ports:**

```shell
nmap-def-top.sh HOST 100
```

**Regular scan:**

```shell
nmap-def-regular-scan.sh HOST
```

**Full TCP scan with `-A`:**

```shell
nmap-def.sh HOST
```

**Full UDP scan with `-A`:**

```shell
nmap-def-udp.sh HOST
```

### Basic Enumeration

```
whatweb-def.sh HOST
```

### Find Directories & Files

```shell
todo
```

### Vulnerability Scan

```shell
nikto-def-ports.sh HOST
```

**Specific ports:**

```shell
nikto-def-ports.sh HOST 80,443
```

### SSL Certificates

**TEST Env:**

```shell
testssl-def.sh https://HOST test
```

**PROD Env:**

```shell
testssl-def.sh https://HOST prod
```