📡 SOHO Firewall: NAT • PAT • ACL • DNS Spoof • DHCP • Port Forwarding (LAB2)

This lab simulates a secure SOHO (Small Office/Home Office) network with firewall features like NAT, PAT, ACLs, DNS spoof detection, DHCP IP assignment, and port forwarding. It builds directly on LAB1 (Ping, HTTP, HTTPS) and continues training in real-world packet logic.

🧪 Skills Practiced

    ✅ Dynamic + Static NAT

    ✅ Port Address Translation (PAT)

    ✅ Extended Access Control Lists (ACLs)

    ✅ DNS spoofing (phishing simulation)

    ✅ DHCP server setup + exclusions

    ✅ Port forwarding with security logic

    ✅ VLAN tagging + inter-VLAN routing

💡 Lab Tools

    Cisco Packet Tracer (Simulation Mode ON)

    Protocol Filters: ARP, ICMP, TCP, UDP, DNS, HTTP, HTTPS

    show ip nat translations, show access-lists, ip dhcp binding, etc.

    Manual DNS spoofing and phishing simulation

    Router-on-a-Stick for Inter-VLAN Routing

    VLAN ACL to isolate subnet access

🛰️ Packet Flow Walkthrough

    Ping from PC0 → Server0 = NAT + PAT + ICMP round-trip (with ARP lookup)

    DNS Request → Spoofed A Record = Hijack TCP session

    TCP 3-Way Handshake → Fake HTTP login page = Visual phishing

    PAT Table fills with port mappings = Real-time stateful tracking

    ACLs block bad flows and simulate DDoS filtering

    DHCP assigns dynamic IPs per VLAN

    VLAN ACL blocks web while allowing ping

    Static port forwarding connects external users to internal web server

👉 SOHO Firewall NAT PAT ACL DNS DHCP LAB2.pkt
🧠 Real-World Concepts

    Routers translate traffic using NAT/PAT so devices can access the internet securely.

    ACLs act as a basic firewall to block or allow traffic based on rules.

    DNS spoofing can hijack trusted web traffic—real attack.

    Port forwarding enables web apps from the outside world.

    VLANs isolate departments or roles inside an org.

    DHCP enables large-scale dynamic IP allocation.

    All this simulates what your home router does—just with CLI-level transparency.
