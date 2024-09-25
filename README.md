# ![Network Security Scan Banner](https://github.com/jeymo092/Network-Scanning/blob/b8c576520a3d0621aad9c7a0a5429f372589b4ca/NETWORK%20SCANNING.png)

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
![Basic Ping Scan](https://your_image_host.com/basic_ping_scan.png)

---

## 2. **Basic Port Scan**

### Description
Scans the top 1000 TCP ports on a target to identify open ports.

### Command
```bash
nmap <target-ip>
```

### PoC
![Basic Port Scan](https://your_image_host.com/port_scan.png)

---

## 3. **Service Version Detection**

### Description
Detects the version of services running on open ports.

### Command
```bash
nmap -sV <target-ip>
```

### PoC
![Service Version Detection](https://your_image_host.com/service_detection.png)

---

## 4. **OS Detection**

### Description
Determines the operating system of the target.

### Command
```bash
nmap -O <target-ip>
```

### PoC
![OS Detection](https://your_image_host.com/os_detection.png)

---

## 5. **Aggressive Scan**

### Description
Combines OS detection, version detection, script scanning, and traceroute.

### Command
```bash
nmap -A <target-ip>
```

### PoC
![Aggressive Scan](https://your_image_host.com/aggressive_scan.png)

---

## 6. **UDP Scan**

### Description
Scans UDP ports to identify services running over UDP.

### Command
```bash
nmap -sU <target-ip>
```

### PoC
![UDP Scan](https://your_image_host.com/udp_scan.png)

---

## 7. **Vulnerability Scan with NSE Scripts**

### Description
Runs Nmap scripts to detect vulnerabilities.

### Command
```bash
nmap --script vuln <target-ip>
```

### PoC
![Vulnerability Scan](https://your_image_host.com/vuln_scan.png)

---

## 8. **Firewall Evasion and Spoofing**

### Description
Evasion techniques to bypass firewalls or IDS systems.

### Command
```bash
nmap -D RND:10 <target-ip>
```

### PoC
![Firewall Evasion](https://your_image_host.com/firewall_evasion.png)

---

## 9. **IPv6 Scan**

### Description
Scanning IPv6 addresses using Nmap.

### Command
```bash
nmap -6 <target-ipv6>
```

### PoC
![IPv6 Scan](https://your_image_host.com/ipv6_scan.png)

---

## 10. **Comprehensive Scan**

### Description
Scans all ports with service detection, OS detection, and vulnerability scanning.

### Command
```bash
nmap -p- -sV -O --script vuln <target-ip>
```

### PoC
![Comprehensive Scan](https://your_image_host.com/comprehensive_scan.png)

---

## Conclusion

This portfolio highlights a range of Nmap scans from basic to advanced, showing real-world use cases and PoCs. It reflects my network security scanning expertise using Nmap.
```

### Instructions to Complete:
1. **Take screenshots** of each scan, name them accordingly, and upload them to a hosting service like GitHub.
2. **Replace the placeholder URLs** (e.g., `https://your_image_host.com`) with the actual image links from your upload.
3. **Save the Markdown file** as `README.md` or any other suitable name.

Let me know if you'd like further adjustments or clarifications!
