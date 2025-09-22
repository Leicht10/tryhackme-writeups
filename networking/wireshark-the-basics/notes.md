[Extra Notes – Wireshark: The Basics]

Capturing

- Start Wireshark on an interface (e.g., wlan0).
- Captures every packet seen by the NIC.

Filters

- Display filters: `http`, `tcp.port == 80`, `ip.addr == 192.168.1.10`.
- Follow streams with `tcp.stream eq n`.

Analysis

- Inspect headers: Ethernet → IP → TCP/UDP → Application.
- Identify suspicious traffic patterns.

CLI Equivalent

- `tshark -i eth0 -w capture.pcap` → save capture.
- `tshark -r capture.pcap -V` → analyze in terminal.

Reflection

- Packet analysis reveals what’s happening on the wire.
- Wireshark makes protocol theory more concrete.
