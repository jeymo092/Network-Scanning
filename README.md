### Updated Markdown:
```markdown
# ![Network Security Scan Banner](./images/NETWORK SCANNING.png)

# Network Security Portfolio - Nmap Scans

This portfolio demonstrates my use of Nmap for various network security scans, from basic to advanced. Each scan includes a proof of concept (PoC) using screenshots of my real-world scans.

---

## 1. **Basic Ping Scan**

### Description
Determines if a host is up using ICMP echo requests.

### Command
```bash
nmap -sn <target-ip>
```

### PoC
![Basic Ping Scan](./images/SCAN 1.png)

---

## 2. **Basic Port Scan**

### Description
Scans the top 1000 TCP ports on a target to identify open ports.

### Command
```bash
nmap <target-ip>
```

### PoC
![Basic Port Scan](./images/SCAN 2.png)

---

## 3. **Service Version Detection**

### Description
Detects the version of services running on open ports.

### Command
```bash
nmap -sV <target-ip>
```

### PoC
![Service Version Detection](./images/SCAN 3.png)

---

## 4. **OS Detection**

### Description
Determines the operating system of the target.

### Command
```bash
nmap -O <target-ip>
```

### PoC
![OS Detection](./images/SCAN 4.png)

---

## 5. **Aggressive Scan**

### Description
Combines OS detection, version detection, script scanning, and traceroute.

### Command
```bash
nmap -A <target-ip>
```

### PoC
![Aggressive Scan](./images/SCAN 5.png)

---

## 6. **UDP Scan**

### Description
Scans UDP ports to identify services running over UDP.

### Command
```bash
nmap -sU <target-ip>
```

### PoC
![UDP Scan](./images/SCAN 6.png)

---

## 7. **Vulnerability Scan with NSE Scripts**

### Description
Runs Nmap scripts to detect vulnerabilities.

### Command
```bash
nmap --script vuln <target-ip>
```

### PoC
![Vulnerability Scan](./images/scan 7.png)

---

## 8. **Firewall Evasion and Spoofing**

### Description
Evasion techniques to bypass firewalls or IDS systems.

### Command
```bash
nmap -D RND:10 <target-ip>
```

### PoC
![Firewall Evasion](./images/SCABN 8.png)

---