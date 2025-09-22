[Extra Notes – Nmap: The Basics]

Host Discovery

- `nmap 192.168.1.10` → quick scan, top 1000 ports.
- `nmap -sn 192.168.1.0/24` → ping sweep.

Scanning

- `-sS` → SYN scan (stealth).
- `-sT` → full TCP connect.
- `-sV` → service/version detection.
- `-O` → OS fingerprinting.

Advanced

- `nmap -A target` → aggressive scan (combines detection).
- `--script vuln` → run vulnerability scripts.

Output

- `-oN file.txt` → normal output.
- `-oX file.xml` → XML for automation.

Reflection

- Learned how attackers discover and enumerate services.
- Also valuable for defenders to baseline their own systems.
