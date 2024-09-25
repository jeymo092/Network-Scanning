# Network Security Portfolio - Nmap Scans

This Project demonstrates my use of Nmap for various network security scans, from basic to advanced. Each scan includes a proof of concept (PoC) using screenshots of my real-world scans.
---
# ![Network Security Scan Banner](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/NETWORK%20SCANNING.png)


---

## 1. **Basic Ping Scan**

### Description
Determines if a host is up using ICMP echo requests.

### Command
```bash
nmap -sn <target-ip>
```

### PoC
![Basic Ping Scan](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCAN%201.png)

---

## 2. **Basic Port Scan**

### Description
Scans the top 1000 TCP ports on a target to identify open ports.

### Command
```bash
nmap <target-ip>
```

### PoC
![Basic Port Scan](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCAN%202.png)

---

## 3. **Service Version Detection**

### Description
Detects the version of services running on open ports.

### Command
```bash
nmap -sV <target-ip>
```

### PoC
![Service Version Detection](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCAN%203.png)

---

## 4. **OS Detection**

### Description
Determines the operating system of the target.

### Command
```bash
nmap -O <target-ip>
```

### PoC
![OS Detection](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCAN%204.png)

---

## 5. **Aggressive Scan**

### Description
Combines OS detection, version detection, script scanning, and traceroute.

### Command
```bash
nmap -A <target-ip>
```

### PoC
![Aggressive Scan](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCAN%205.png)

---

## 6. **UDP Scan**

### Description
Scans UDP ports to identify services running over UDP.

### Command
```bash
nmap -sU <target-ip>
```

### PoC
![UDP Scan](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/scan%206.png)

---

## 7. **Vulnerability Scan with NSE Scripts**

### Description
Runs Nmap scripts to detect vulnerabilities.

### Command
```bash
nmap --script vuln <target-ip>
```

### PoC
![Vulnerability Scan](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/scan%207.png)

---

## 8. **Firewall Evasion and Spoofing**

### Description
Evasion techniques to bypass firewalls or IDS systems.

### Command
```bash
nmap -D RND:10 <target-ip>
```

### PoC
![Firewall Evasion](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/SCABN%208.png)

---

## 9. **Comprehensive Scan**

### Description
Scans all ports with service detection, OS detection, and vulnerability scanning.

### Command
```bash
nmap -p- -sV -O --script vuln <target-ip>
```

### PoC
![Comprehensive Scan](https://your_image_host.com/comprehensive_scan.png)

---
