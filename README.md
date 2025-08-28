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

🔗 Download the Lab

You can download and open the Packet Tracer .pkt file here:

👉 SOHO Firewall NAT PAT ACL DNS DHCP LAB2.pkt
🧠 Real-World Concepts

    Routers translate traffic using NAT/PAT so devices can access the internet securely.

    ACLs act as a basic firewall to block or allow traffic based on rules.

    DNS spoofing can hijack trusted web traffic—real attack.

    Port forwarding enables web apps from the outside world.

    VLANs isolate departments or roles inside an org.

    DHCP enables large-scale dynamic IP allocation.

    All this simulates what your home router does—just with CLI-level transparency.

🧢 Author Notes

Part of the BowTiedCyber Zero-to-Hero Bootcamp Labs.
This lab expands your understanding of perimeter defense, address translation, and firewall basics—exactly what a SOC analyst needs.
🧭 How to Upload to GitHub

Follow these steps exactly to update or create the repo:
✅ Option A: Create a New Repo

    Log in to GitHub.com

    Click the ➕ icon in the top-right → New Repository

    Name it something like: soho-firewall-lab2

    Description: SOHO Firewall NAT PAT ACL DNS DHCP Lab (LAB2)

    Check ✅ Add a README file

    Click Create Repository

✅ Option B: Update Existing Repo

If you want to keep both Lab1 and Lab2 in a single repo:

    Navigate to your existing repo

    Click Add File → Upload files

    Drag & drop:

        The SOHO_FIREWALL_LAB2.pkt file

        The new README.md (replace the old one, or rename to LAB2.md)

🔁 Copy + Paste the README

Once the repo is ready:

    In GitHub, go to the repo

    Click README.md

    Click ✏️ (Edit)

    Paste the entire Markdown content from above

    Commit changes at the bottom

Done. Your GitHub repo is now a solid portfolio piece.
