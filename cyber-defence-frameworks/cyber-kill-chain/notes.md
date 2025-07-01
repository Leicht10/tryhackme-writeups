# 🎯 Notes — Cyber Kill Chain

## The 7 Phases

1. Reconnaissance — Information gathering (WHOIS, Nmap, etc.)
2. Weaponization — Pair exploit with payload (e.g., reverse shell + macro)
3. Delivery — Send exploit (email, USB, malicious site)
4. Exploitation — Trigger exploit to gain access
5. Installation — Drop malware, set persistence
6. Command & Control — Adversary gains control (e.g., beaconing, C2 server)
7. Actions on Objectives — Exfiltration, destruction, persistence

## Detection Opportunity

- Early detection = less damage
- Kill Chain helps map alerts and logs to attacker intent

## My Reflection

This is the backbone of understanding how intrusions work. It’s useful to think where each log or alert fits into this model.
