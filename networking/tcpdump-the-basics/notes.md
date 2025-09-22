[Extra Notes – Tcpdump: The Basics]

Capturing

- `sudo tcpdump -i eth0` → capture traffic live.
- Save to file with `-w capture.pcap`.

Filters

- `tcpdump -i eth0 host 192.168.1.10` → only one host.
- `tcpdump -i eth0 tcp port 80` → HTTP only.
- Supports powerful BPF expressions.

Analysis

- Read capture later with `tcpdump -r capture.pcap`.
- Output is concise, no GUI required.

Reflection

- Tcpdump is essential on servers without a desktop environment.
- Great for quick triage before using Wireshark.
