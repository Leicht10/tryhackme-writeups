[Extra Notes – Networking Core Protocols]

TCP vs UDP

- TCP: connection-oriented, reliable (3-way handshake).
- UDP: connectionless, faster but no delivery guarantees.

ICMP

- Used for diagnostic tools like `ping` and `traceroute`.
- Can be abused for reconnaissance or covert channels.

ARP

- Maps IP addresses to MAC addresses on a local network.
- `arp -a` shows current ARP table.

Netcat

- `nc -vz host 22` → check if port is open.
- `nc -lvp 4444` → listen for connections.

Reflection

- Protocol fundamentals explain how services work under the hood.
- This knowledge helps recognize unusual traffic during analysis.
